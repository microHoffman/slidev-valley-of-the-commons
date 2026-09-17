<script setup lang="ts">
import { useId } from 'vue'
defineProps<{ kind: 'funding' | 'property' | 'dao' }>()
const arrowId = useId()
</script>

<template>
  <svg class="finance-diagram" :viewBox="kind === 'funding' ? '0 0 1152 310' : kind === 'property' ? '0 0 1152 310' : '0 0 1152 290'" role="img" :aria-label="kind === 'funding' ? 'Lenders deposit USDC into a vault. The borrower accepts the credit and locks weETH in escrow.' : kind === 'property' ? 'An SPV owns a property and issues company shares. Legally linked share tokens are pledged as loan collateral.' : 'A DAO treasury lends stablecoins to token holders, who pledge tokens and repay principal plus interest.'">
    <defs><marker :id="arrowId" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="7" markerHeight="7" orient="auto-start-reverse"><path d="M0 0 L10 5 L0 10z" fill="#008F8B" /></marker></defs>
    <template v-if="kind === 'funding'">
      <g><rect class="box" x="1" y="30" width="290" height="113" /><text class="diagram-title" x="22" y="70">Lenders</text><text class="diagram-body" x="22" y="108">Deposit USDC</text></g>
      <g><rect class="box" x="426" y="30" width="300" height="113" /><text class="diagram-title" x="447" y="70">Lending vault</text><text class="diagram-body" x="447" y="108">ERC-4626 pool</text></g>
      <g><rect class="box" x="861" y="30" width="290" height="113" /><text class="diagram-title" x="882" y="70">Borrower</text><text class="diagram-body" x="882" y="108">Receives loan credit</text></g>
      <path class="line" d="M291 87 H426" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="319" y="66">fund</text>
      <path class="line" d="M726 87 H861" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="753" y="66">accept</text>
      <g><rect class="box" x="426" y="209" width="300" height="98" /><text class="diagram-title" x="447" y="247">Collateral escrow</text><text class="diagram-body" x="447" y="281">Holds weETH collateral</text></g>
      <path class="line" d="M1006 143 V258 H726" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="766" y="239">lock collateral</text>
    </template>
    <template v-else-if="kind === 'property'">
      <g><rect class="box" x="1" y="15" width="286" height="103" /><text class="diagram-title" x="23" y="55">Property</text><text class="diagram-body" x="23" y="92">The real-world asset</text></g>
      <g><rect class="box" x="433" y="15" width="286" height="103" /><text class="diagram-title" x="455" y="55">SPV company</text><text class="diagram-body" x="455" y="92">The property owner</text></g>
      <g><rect class="box" x="865" y="15" width="286" height="103" /><text class="diagram-title" x="887" y="55">Company shares</text><text class="diagram-body" x="887" y="92">Ownership rights</text></g>
      <path class="line" d="M433 66 H287" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="331" y="48">owns</text>
      <path class="line" d="M719 66 H865" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="750" y="48">issues</text>
      <g><rect class="box" x="865" y="209" width="286" height="98" /><text class="diagram-title" x="887" y="248">Share tokens</text><text class="diagram-body" x="887" y="282">Legally linked to shares</text></g>
      <g><rect class="box" x="433" y="209" width="286" height="98" /><text class="diagram-title" x="455" y="248">Loan collateral</text><text class="diagram-body" x="455" y="282">Pledged as security</text></g>
      <path class="line legal" d="M1008 118 V209" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="820" y="169">legal link</text>
      <path class="line" d="M865 258 H719" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="744" y="239">pledge</text>
    </template>
    <template v-else>
      <g><rect class="box" x="1" y="148" width="291" height="120" /><text class="diagram-title" x="23" y="192">DAO treasury</text><text class="diagram-body" x="23" y="230">Holds stablecoins</text></g>
      <g><rect class="box" x="861" y="148" width="290" height="120" /><text class="diagram-title" x="883" y="192">Token holders</text><text class="diagram-body" x="883" y="230">Borrow without selling</text></g>
      <g><rect class="box" x="430" y="4" width="292" height="100" /><text class="diagram-title" x="452" y="44">Collateral escrow</text><text class="diagram-body" x="452" y="81">Holds the DAO’s token</text></g>
      <path class="line" d="M292 177 H861" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="463" y="161">stablecoin loan</text>
      <path class="line" d="M861 246 H292" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="450" y="229">principal + interest</text>
      <path class="line" d="M1006 148 V54 H722" :marker-end="`url(#${arrowId})`" /><text class="diagram-label" x="797" y="34">pledge tokens</text>
    </template>
  </svg>
</template>
