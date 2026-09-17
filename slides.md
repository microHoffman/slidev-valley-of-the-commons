---
theme: none
title: Financing community needs
info: Community financing, the BORDEL loan, and the next steps for OWN.
layout: cover
section: '00 / Valley of the Commons · Governance & Funding'
author: '@microHoffman'
canvasWidth: 1280
aspectRatio: 16/9
colorSchema: light
fonts:
  sans: Inter
  serif: Newsreader
  mono: Space Mono
  provider: none
  local: [Inter, Newsreader, Space Mono]
drawings:
  enabled: false
  persist: false
transition: none
comark: false
mdc: false
monaco: false
download: false
exportFilename: financing-community-needs
export:
  withClicks: false
duration: 40min
favicon: /images/own-logo.svg
defaults:
  layout: editorial
  section: '01 / Why community financing?'
---

<img class="own-mark" src="/images/own-logo.svg" alt="OWN" />

# Financing<br>community needs

<div class="cover-meta">
<div>Valley of the Commons<br><span class="muted">Governance &amp; Funding Models</span></div>
<div><a href="https://x.com/microHoffman">@microHoffman</a> | <a href="https://own.casa/">own.casa</a><br><span class="muted">17 September 2026</span></div>
</div>

<!--
Open with the practical question: how do we get the money upfront for something the community will use for years? This talk follows BORDEL's crypto-backed financing, then explores tokenized property, DAO credit and undercollateralized loans. The outline is the presenter's, with the loan explanation spread over six slides to leave room to speak.
-->

---
section: '00 / About me'
---

# About me

<div class="two-col bio-grid">
<div class="bio-details">
<h2>Cypherpunk / Solarpunk</h2>
<h3>Exploring how technologies can help us create new ways of collaboration</h3>
<div class="bio-project"><strong>OWN</strong></div>
<div class="bio-project"><strong>Closer / TDF</strong><span>Technical contributor</span></div>
</div>
</div>

<!--
I explore how technologies can help us build new ways of cooperation and more free living. Cypherpunk and solarpunk are useful descriptions of that motivation: privacy and autonomy, together with regenerative, cooperative ways of life. Introduce OWN, then my technical contributions to Closer / Traditional Dream Factory. These personal affiliations come from the supplied outline.
-->

---
---

# Why do we care about financing?

<div class="needs-grid">
<div><span class="index"></span><h2>New land</h2></div>
<div><span class="index"></span><h2>A property</h2></div>
<div><span class="index"></span><h2>Renovation</h2></div>
<div><span class="index"></span><h2>Infrastructure</h2></div>
</div>

<!--
Buying land, buying a building, renovating, and expanding energy, tools or other infrastructure are different projects with the same timing problem. The big expense comes now; the community's income and benefits arrive over time. Invite people to keep their own project in mind through the examples.
-->

---
---

# Every community needs different terms

<div class="needs-grid terms-needs">
<div><span class="label">Security</span><h2>What can we pledge?</h2><p>Available collateral assets.</p></div>
<div><span class="label">Time</span><h2>How long do we need?</h2><p>A duration that fits the project.</p></div>
<div><span class="label">Cash flow</span><h2>How can we repay?</h2><p>A schedule that fits our income.</p></div>
<div><span class="label">People</span><h2>Who wants to support us?</h2><p>Community members and aligned investors.</p></div>
</div>

<!--
Collateral is an asset pledged to secure a loan. Duration is how long the loan lasts; repayment structure is when payments must happen within that time. Both need to fit the community. Some communities want to raise funds from their own members or people who share the mission. Those supporters can play different roles as lenders, investors or collateral contributors.
-->

---
---

# The usual options can be a poor fit

<div class="constraints">
<div><span class="index">01</span><h3>The bank sets the menu</h3><p>Limited choice of terms and duration.</p></div>
<div><span class="index">02</span><h3>Community lending is hard</h3><p>Few simple ways to pool support.</p></div>
<div><span class="index">03</span><h3>Our assets may not qualify</h3><p>Collateral eligibility can be restrictive.</p></div>
<div><span class="index">04</span><h3>Interest leaves the community</h3><p>It goes to the bank, rather than our lenders.</p></div>
<div><span class="index">05</span><h3>We may have to sell</h3><p>Even assets we would prefer to keep.</p></div>
</div>

<!--
These are possible mismatches, not claims that banks never serve communities well. A bank can be the right option. The question is whether we can have more ways to set terms together, mobilize community capital and borrow against assets we want to retain. Keeping assets while borrowing also means pledging them and taking on repayment obligations.
-->

---
layout: blueprint
section: '01 / Trust & technology'
class: trust-slide
---

# Trust each other.<br>Do the rules need to rely on it?

<div class="two-col trust-columns">
<div><p class="eyebrow">Human layer</p><h2>Trust builds a community.</h2><p>Relationships, shared purpose,<br>and care for one another.</p></div>
<div><p class="eyebrow">Financial layer</p><h2>Code can enforce commitments.</h2><p>Clear rules for funds,<br>repayments, and collateral.</p></div>
</div>

<p class="callout">My view: if two systems do the same job, prefer the one<br>that needs less trust to function.</p>

<!--
Is trustless technology a good thing in communities built on trust? My argument is not that trust is bad. If we can achieve the same function without requiring someone to be trusted to follow the financial rules, that reduces a burden on the relationship. It leaves trust for what people are actually good at. Trustless here is shorthand for reducing trust in discretionary intermediaries; code, governance, asset issuers and real-world enforcement still introduce dependencies.
-->

---
section: '02 / Introducing OWN'
---

# OWN: real-world utility for onchain credit

<p class="lead">Tools to structure loans around real needs<br>and connect borrowers with aligned lenders.</p>

<div class="two-col collateral-paths">
<div><p class="eyebrow">01</p><h2>Crypto collateral</h2><p>ERC-20 tokens &amp; NFTs</p><p class="small muted">Digital assets secure the loan.<br>BORDEL is our first example.</p></div>
<div><p class="eyebrow">02</p><h2>Tokenized real-world assets</h2><p>For example, shares tied to real estate</p><p class="small muted">Connect onchain collateral<br>to enforceable rights.</p></div>
</div>

<!--
OWN works on financing tools, structuring and connections between borrowers and lenders. We want onchain finance to help build useful things in the real world. OWN is not itself the lender in this example. Introduce the two broad collateral paths: crypto assets such as ERC-20s and NFTs, and tokenized real-world assets such as real estate interests. Exact asset support depends on the selected product and deployment: this does not claim that every NFT works in the BORDEL installments product. Start with the crypto path and a hackerspace purchase.
Sources: https://own.casa/ ; https://docs.pwn.xyz/ ; https://pilot.own.casa/
-->

---
layout: blueprint
section: '03 / BORDEL · The loan showcase'
class: case-divider
---

<p class="eyebrow">Prague / A community hackerspace</p>

# BORDEL

<p class="statement">Crypto collateral.<br>A permanent home.</p>

<div class="case-meta"><span>Community-funded credit</span><span>Loan active · repayments underway</span></div>
<p class="case-link"><a href="https://loan.bordel.wtf/">loan.bordel.wtf ↗</a></p>

<!--
Introduce the BORDEL loan showcase. A community pooled lenders' money against crypto collateral to help finance a permanent home. If useful, open loan.bordel.wtf or pilot.own.casa for a live demonstration; the deck itself works offline. Do not connect a wallet or submit a transaction during the presentation. The loan is active, not fully repaid.
Sources: https://loan.bordel.wtf/ ; https://pilot.own.casa/ (read 17 September 2026).
-->

---
section: '03 / BORDEL · The community'
class: community-slide
---

# A place to make things together

<div class="photo-split">
<div>
<p class="small">A Prague workshop for hackers, makers,<br>artists, and curious people.</p>
<p class="small muted">Electronics · open-source tools<br>Privacy · experiments · workshops</p>
<br>
<br>
<p class="small">Donation alternative: Support the space, with principal<br>and interest repaid over time.</p>
</div>
<figure>
<img class="project-photo" src="/images/bordel-hackerspace.jpeg" alt="Illuminated BORDEL sign inside the hackerspace" />
</figure>
</div>

<!--
BORDEL combines technology, art, open-source work, privacy, electronics and workshops. People share tools and build projects together. The crowdloan lets people support the space while expecting their money back with interest: another way to help alongside donations. The team's aim is affordable community financing, rather than maximizing lender yield. Do not assert that the rate beats every DeFi or bank offer.
Rate wording is deliberate: on 17 September 2026 pilot.own.casa explicitly shows “Borrower rate: 2.50%” alongside a 4.59% fixed APR; loan.bordel.wtf displays 5%. The slide preserves the supplied 2.5% as the pilot-reported borrower rate, not a lender APR or a reconciled effective cost. A numerical rate comparison would require fee and interest-basis reconciliation.
Sources: https://pilot.own.casa/ ; https://loan.bordel.wtf/
-->

---
layout: blueprint
section: '03 / BORDEL · Onchain coordination'
---

# So how does BORDEL mortgage works?

<p class="lead">Funding, collateral, and repayments are handled by smart contracts.</p>

<!--
For the crypto-backed loan mechanism, the transfers and rule checks run onchain; no offchain loan administrator needs to manually release collateral after repayment. Buying the property and maintaining the company still involve offchain actions.
-->

---
section: '03 / BORDEL · 01 Set the terms'
---

# The borrower proposes the terms

<div class="term-grid">
<div><span class="label">01 / Collateral asset</span><h2>What secures it?</h2><p>e.g. weETH</p></div>
<div><span class="label">02 / Loan to value</span><h2>How much to borrow?</h2><p>Loan ÷ collateral value</p></div>
<div><span class="label">03 / Fixed interest</span><h2>What does it cost?</h2><p>Rate agreed upfront</p></div>
<div><span class="label">04 / Repayment schedule</span><h2>When are payments due?</h2><p>Required amounts &amp; deadlines</p></div>
<div><span class="label">05 / Duration</span><h2>When does it end?</h2><p>The full loan term</p></div>
<div><span class="label">06 / Credit asset</span><h2>What is lent?</h2><p>e.g. USDC stablecoins</p></div>
</div>

<p class="callout">Lenders decide whether those terms work for them.</p>

<!--
The borrower chooses a proposal; lenders choose whether to fund it. Collateral is the pledged security. LTV is the loan amount divided by the collateral's value at the relevant valuation point. weETH is a crypto token representing restaked ETH exposure; it was the collateral in this case. USDC is a dollar-linked stablecoin and was the loan's credit asset. Fixed rate, schedule and duration are separate choices: a loan can run for years while requiring payments along the way. Changing terms after funding is not implied.
Sources: https://pilot.own.casa/ ; https://loan.bordel.wtf/
-->

---
layout: blueprint
section: '03 / BORDEL · 02 Fund → 03 Activate'
---

# Pool the money. Then activate the loan.

<FinanceDiagram kind="funding" />

<p class="callout">Once enough is committed, the borrower accepts:<br><strong>credit is released and collateral is locked in the same transaction.</strong></p>

<!--
After terms are set, a crowdloan phase lets lenders deposit the credit asset into a shared lending vault. ERC-4626 is the tokenized-vault interface: vault shares represent a position in the pool. Once sufficient money is collected, the borrower can accept the loan. The transaction transfers the loan credit to the borrower and pulls the collateral into smart-contract escrow atomically; if a required step fails, the transaction reverts. The collateral stays there until full repayment or default under the loan's rules. Actual loan proceeds can be affected by configured fees. Converting credit to fiat and settling a property purchase are separate from this diagram.
Sources: https://github.com/PWNDAO/pwn_protocol/blob/v1.5/src/periphery/crowdsource/PWNCrowdsourceLenderVault.sol ; https://github.com/PWNDAO/pwn_protocol/blob/v1.5/src/core/loan/PWNLoan.sol
-->

---
layout: blueprint
section: '03 / BORDEL · 04 Repay → 05 Resolve'
class: repayment-slide
---

# Repay over time. Two possible endings.

<div class="repayment-strip"><span>Borrower repays</span><b>→</b><span>Vault receives funds</span><b>→</b><span>Lenders claim repayments</span></div>

<div class="two-col outcomes">
<div><p class="eyebrow">Paid in full / on time</p><h2>Collateral goes back<br>to the borrower.</h2><p>The loan is finished.</p></div>
<div><p class="eyebrow outcome-default">Required payment missed</p><h2>The loan defaults.<br>Lenders claim collateral.</h2><p class="small">Previous repayments stay paid.<br>The borrower keeps proceeds not repaid.</p></div>
</div>

<!--
The borrower makes periodic repayments against the agreed schedule. Following repayments, lenders can claim from the vault. The interface describes pro-rata shares, but the inherited source review documents a first-come cash-access limitation in the vault; do not imply the contract guarantees simultaneous proportional cash access to every lender. The qualification on screen preserves that distinction.
Full repayment by the required deadlines releases the collateral. Missing an interim required repayment can trigger default before the final maturity; this is not a single end-of-term check. In the crypto loan mechanism, default lets the lender side claim collateral. The borrower loses that collateral and receives no refund of prior repayments. Unrepaid loan proceeds are not automatically clawed back by the contract. This is not a universal statement about legal liabilities outside this mechanism.
Sources: https://github.com/PWNDAO/pwn_protocol/blob/v1.5/src/periphery/product/PWNInstallmentsProduct.sol ; https://github.com/PWNDAO/pwn_protocol/blob/v1.5/src/periphery/crowdsource/PWNCrowdsourceLenderVault.sol
-->

---
section: '03 / BORDEL · Flexibility in the rules'
---

# A repayment deadline, not a price trigger

<div class="three-col rule-details">
<div><p class="eyebrow">Collateral</p><h2>No price-based<br>liquidation here.</h2><p class="small">A price fall alone does not trigger default.</p></div>
<div><p class="eyebrow">Repayments</p><h2>Pay early.<br>Stay on schedule.</h2><p class="small">Payments can arrive at any time, up to the agreed deadlines.</p></div>
<div><p class="eyebrow">Crowdloan phase</p><h2>Committed funds<br>can earn yield.</h2><p class="small">A pool such as Aave can put waiting funds to work.</p></div>
</div>

<p class="callout">Hooks can extend the rules — for example, an agreed external trigger.</p>

<!--
The selected installment loan tests debt against its repayment schedule, rather than liquidating solely because collateral prices fall. Price risk still exists for lenders. Earlier repayments are possible, but the borrower must meet the cumulative schedule; interest treatment follows the contract.
Crowdloan commitments can sit in a configured yield-bearing pool such as Aave while waiting for activation. This can offset opportunity cost, not remove every opportunity cost or guarantee yield; it also introduces the pool's risks.
Hooks are extension points for custom behavior. A possible future example is an oracle-attested construction milestone not being completed by an agreed deadline. Price triggers could also be designed where suitable. These are design possibilities requiring a selected implementation, reliable evidence and agreed terms, not features asserted to be active in BORDEL.
Sources: https://loan.bordel.wtf/ ; https://github.com/PWNDAO/pwn_protocol/tree/v1.5
-->

---
section: '03 / BORDEL · Amortization'
---

# As principal falls, so does LTV

<AmortizationChart />

<!--
This is an illustrative amortization pattern, not BORDEL's repayment schedule. Start with €100,000 principal against €200,000 collateral: 50% LTV. Repay €20,000 principal per year, and after one year debt is €80,000 (40% LTV), after three years €40,000 (20%), and after five years zero. The same pledged collateral remains locked until completion or default. The collateral value is held constant to isolate the effect of repayments. In reality a price fall can raise LTV even while debt falls. Interest payments alone do not reduce principal. LTV here uses outstanding principal for a simple teaching example.
-->

---
section: '03 / BORDEL · Ownership'
---

# Who owns the hackerspace real estate?

<div class="two-col ownership-grid">
<div><p class="eyebrow">The property owner</p><h2>A joint-stock company.</h2><p class="small">Collateral contributors receive<br>company shares proportional<br>to their contribution.</p></div>
<div><p class="eyebrow">Illustrative allocation</p><div class="ownership-ratio"><span>30%</span><b>→</b><span>30%</span></div><div class="ownership-labels"><span>of the collateral</span><span>of the shares</span></div><p class="callout small">Next: use onchain contribution records<br>to determine ownership allocations.</p></div>
</div>

<!--
The OWN pilot describes a Czech joint-stock company as the borrower and property owner. The BORDEL story describes the allocation principle: collateral contributors receive shares in proportion to their contributions. For example, 30% of the collateral corresponds to 30% of the shares in this simplified explanation. This is an allocation illustration, not an independently checked shareholder register. Future accounting could use onchain contribution and repayment data to inform company share allocations. Multisig signing power is not automatically a company shareholding: the legal records and agreements must implement the intended rights.
Sources: https://pilot.own.casa/ ; https://loan.bordel.wtf/
-->

---
layout: blueprint
section: '03 / BORDEL · Shared wallet'
---

# A multisig shares control of the wallet

<div class="two-col multisig-grid">
<div><p class="eyebrow">Shared wallet</p><h2>A multisig needs<br>several approvals.</h2><p class="small">Useful when a community<br>manages funds together.</p></div>
<div><p class="eyebrow">Illustrative / 2 of 3 signers</p><div class="signers"><span class="signed">A ✓</span><span class="signed">B ✓</span><span>C</span><b>→</b><span class="transaction">Execute</span></div><p class="small muted">Propose → collect approvals → execute</p><p class="small">No single key can move the funds alone.</p></div>
</div>

<!--
A multisig is a wallet requiring a threshold of signers to approve transactions. In an illustrative 2-of-3 wallet, one person proposes a transaction, two signers approve, and the transaction can execute. Useful for a shared treasury, accepting a loan or authorizing repayments. It reduces dependence on one key. This diagram does not claim BORDEL uses exactly 2 of 3 signers. Wallet signing authority and company shares are distinct.
-->

---
section: '03 / BORDEL · Repayment & fairness'
---

# Where do the repayments come from?

<div class="two-col repayment-sources">
<div><p class="eyebrow">Everyday operations</p><h2>Membership fees<br>&amp; space revenue.</h2><p>People using the space<br>help sustain it over time.</p></div>
<div><p class="eyebrow">Additional contributions</p><h2>Help repay.<br>Receive more shares.</h2><p>New shares recognize<br>additional repayment contributions.</p></div>
</div>

<p class="callout">The aim: keep ownership fair as contributions change.</p>

<!--
Regular income, particularly membership fees, supports operating costs and repayments. The public story also describes events and community support. If someone contributes extra money to repayment under the ownership arrangement, issuing new company shares can recognize the contribution and update relative ownership. Share issuance has to follow the company's agreements and formalities; it is not automatically performed by the loan contract. Distinguish an equity-recognized repayment contribution from a donation, which does not necessarily grant shares.
Sources: https://loan.bordel.wtf/ ; https://pilot.own.casa/
-->

---
layout: blueprint
section: '03 / BORDEL · The goal'
class: goal-slide
---

# A rent-free,<br>mortgage-free hackerspace.

<p class="lead">Membership fees go back into the community.</p>

<div class="three-col goal-uses"><div><span class="label">01</span><h2>Maintain<br>the space.</h2></div><div><span class="label">02</span><h2>Improve<br>what we have.</h2></div><div><span class="label">03</span><h2>Expand<br>what is possible.</h2></div></div>

<!--
This is the ultimate goal after the loan is fully repaid, not the current status. A permanent home without rent or mortgage payments lets membership income focus on maintenance, better tools, improvements and expanding community resources. Operating costs, repairs and reserves continue to exist. The point is to stop directing so much of the community's effort toward rent or debt service.
Sources: https://loan.bordel.wtf/ ; https://pilot.own.casa/
-->

---
section: '03 / BORDEL · Discussion'
class: discussion-slide
---

<p class="eyebrow">Before we move on</p>

# Questions about<br>the BORDEL loan?

<p class="lead muted">The terms · the mechanics · the ownership</p>

<div class="discussion-next"><span class="label">Next</span><p>What if the property itself could secure the loan?</p></div>

<!--
Pause here for questions about BORDEL, the mechanics, the community or the ownership model. Keep the next distinction clear: crypto assets secured this loan, while the company owns the property. The next section explores how rights connected to the property could become collateral themselves.
-->

---
layout: blueprint
section: '04 / The next step · Real-world collateral'
class: next-stage
---

# What if the property<br>could secure the loan?

<div class="collateral-shift"><div><span class="label">BORDEL example</span><h2>Crypto assets</h2></div><b>→</b><div><span class="label">Next exploration</span><h2>Tokenized real estate</h2></div></div>

<p class="callout">The onchain mechanism is one part.<br><strong>The legal structure depends on the jurisdiction.</strong></p>

<!--
Move from crypto collateral to rights linked to real estate. A token does not inherently transfer a land title. There are multiple possible structures and their feasibility depends on the property, company, parties, rights and jurisdiction. We are exploring possible arrangements, not presenting one universal legal recipe.
-->

---
layout: blueprint
section: '04 / Real-world collateral · One possible structure'
---

# A company, its shares, and a legal link

<FinanceDiagram kind="property" />

<p class="callout">SPV = a special-purpose company that holds the property.<br>The tokens must carry enforceable rights in its shares.</p>

<!--
One possible arrangement: establish an SPV to own the property; it issues company shares; tokenization creates a legally effective link between the tokens and those shares; then the share tokens are pledged as collateral. The company continues to own the land. Holding or transferring the token must carry the intended rights through a valid legal arrangement. The enforceability of the pledge, token transfer, shareholder register and governance depends on the selected jurisdiction and agreements. This is a conceptual structure to investigate with the project, not a claim that ordinary NFTs automatically become legal shares.
-->

---
section: '04 / Real-world collateral · Default'
---

# Agree what happens in case of default

<div class="two-col default-options">
<div><p class="eyebrow">Route A / Ownership</p><h2>Lenders take over<br>the pledged shares.</h2><p>Control of the property-owning company can change hands.</p></div>
<div><p class="eyebrow">Route B / Sale</p><h2>An authorized party<br>sells the property.</h2><p>Sale proceeds are distributed<br>under the agreed recovery rules.</p></div>
</div>

<p class="callout">Rights, authority, and enforcement must be agreed upfront.</p>

<!--
These are possible agreed recovery routes, not automatic legal consequences in every jurisdiction. Route A can transfer pledged company shares or their economic rights to lenders, potentially changing control of the property owner; it does not directly rewrite the land register. Route B authorizes an appropriate party to sell the property and distribute proceeds according to the security and priority arrangements, including costs and other claims. Multiple lenders need a mechanism to act together. Selling the property may require additional security or authority beyond a pledge of share tokens. Resolve these points before funding.
-->

---
layout: blueprint
section: '05 / Another use case · DAO treasury credit · Proposal'
---

# Liquidity for holders. Income for the DAO.

<FinanceDiagram kind="dao" />

<div class="dao-caption"><p class="small">Borrow against the DAO’s token.<br>Pay principal + interest back to the treasury.</p><a href="https://gno.own.casa/">gno.own.casa ↗</a></div>

<!--
A DAO holding stablecoins could lend to holders against its own token. The holder obtains liquidity without selling; the treasury can earn interest if the loan performs. Principal returning is not income. A fixed interest rate can make contractual cash flows predictable, but it does not guarantee actual income: token prices, repayment and recovery still matter. Introduce GNO as the Gnosis token and gno.own.casa as the linked credit example, without asserting a DAO vote, commitment or funded facility. Terms and eligibility are for the specific arrangement.
Source: https://gno.own.casa/
-->

---
section: '05 / Further possibilities · Undercollateralized lending'
---

# Exploration: undercollateralized lending

<div class="two-col undercollateralized">
<div><p class="eyebrow">Illustrative loan</p><div class="loan-total">€100k</div><div class="coverage-bar"><span>€60k secured</span><span>€40k gap</span></div><p class="small muted">Collateral covers only part of the loan.</p></div>
<div><h2>Something else must<br>support the promise.</h2><p class="small">Revenue, guarantees,<br>reputation, etc...</p></div>
</div>

<p class="source spaced">An exploration direction · the uncovered portion increases lender risk.</p>

<!--
Undercollateralized means collateral is worth less than the debt it secures. In this illustrative €100k loan with €60k collateral, €40k is initially uncovered, ignoring interest and recovery costs. That makes underwriting the borrower, income and any guarantees or legal recourse more important. Social trust can be valuable here; it cannot be replaced by a token or an automated rule. This is a further direction to explore, not a statement that the BORDEL installments product allows initial LTV above 100%, nor a ready-made product promise.
-->

---
section: '06 / Open exploration'
class: exploration-slide
---

# There is more than one way to build this.

<p class="statement">Bring your community.<br>Your property.<br><em>Your constraints.</em></p>

<p class="lead spaced">We are actively exploring structures<br>with communities and projects.</p>

<!--
This is an invitation to discovery. We are exploring how different ownership structures, repayment sources and jurisdictions can fit real communities. We want to work on a concrete case together, rather than assume the same arrangement works everywhere. Ask interested people to bring their actual constraints: what they want to finance, what assets they have, their timeline and where the project is based.
-->

---
layout: blueprint
section: '06 / Let’s explore together'
class: final-slide
---

<img class="closing-mark" src="/images/own-logo.svg" alt="OWN" />

# What does your<br>community need next?

<p class="lead">If any of this connects to your project,<br>we would like to explore it with you.</p>

<div class="closing-links"><a href="https://own.casa/">own.casa ↗</a><a href="https://x.com/microHoffman">@microHoffman ↗</a></div>

<p class="small muted spaced">A need. An asset. An idea. Let’s start there.</p>

<!--
Invite people to talk even if their use case only partly resembles these examples. We can discover the constraints and possibilities together: community projects, tokenized property, DAO liquidity or other financing needs. The immediate next step is a conversation about their project. Contact through own.casa or @microHoffman. Thank the room and open the wider discussion.
-->
