<script setup lang="ts">
const years = [0, 1, 2, 3, 4, 5]
</script>

<template>
  <svg class="amortization" viewBox="0 0 1152 355" role="img" aria-label="Illustrative equal principal repayments: debt falls from 100,000 euros to zero over five years. At a constant 200,000-euro collateral value, LTV falls from 50 percent to zero.">
    <text class="chart-label" x="10" y="21">OUTSTANDING PRINCIPAL</text>
    <text class="chart-label" x="822" y="21">LTV AT CONSTANT COLLATERAL VALUE</text>
    <line class="grid" x1="15" y1="276" x2="1140" y2="276" />
    <g v-for="year in years" :key="year" :transform="`translate(${40 + year * 197}, 0)`">
      <rect class="bar" x="0" :y="276 - (100 - year * 20) * 1.75" width="98" :height="Math.max(2, (100 - year * 20) * 1.75)" />
      <text class="chart-value" x="49" :y="276 - (100 - year * 20) * 1.75 - 17" text-anchor="middle">€{{ 100 - year * 20 }}k</text>
      <text x="49" y="309" text-anchor="middle">{{ year === 0 ? 'Start' : `Year ${year}` }}</text>
      <text class="ltv-value" x="49" y="345" text-anchor="middle">{{ 50 - year * 10 }}%</text>
    </g>
  </svg>
</template>
