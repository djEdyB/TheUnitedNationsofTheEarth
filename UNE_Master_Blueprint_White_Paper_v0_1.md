---
title: "UNITED NATIONS OF THE EARTH"
subtitle: "Master Blueprint & North Star White Paper"
author: "Concept originated by Eddie Boscana | Integrated research synthesis"
date: "18 November 2026"
---

# UNITED NATIONS OF THE EARTH

## Master Blueprint & North Star White Paper

**Working Draft v0.1 | 18 November 2026**  
**Status:** Architectural research proposal—not a deployed protocol, adopted constitution, financial offering, or claim of governmental authority.  
**Origin:** Eddie Boscana's three founding essays and subsequent discussions concerning censorship-resistant currency, private collateral, collective ownership, and the commons.

> **The north star:** Build a voluntary, open-source, globally interoperable civic and economic commons that protects individual sovereignty, enables trustworthy communication and accountable collective decision-making, and supports neutral exchange and shared prosperity—without concentrating discretionary power in any person, corporation, model, or government.

**Non-negotiable distinction:** No technological system can guarantee perfect freedom, perfect neutrality, permanent availability, or economic stability. UNE will pursue measurable, inspectable, challengeable protections rather than claim absolutes that cannot be demonstrated.

# Executive Summary

The United Nations of the Earth (UNE) is conceived as a rights-oriented, voluntary framework for planetary cooperation. Its proposed Foundation Protocol enables self-controlled identifiers, verifiable communication, and interoperable communities. Its governance layer would coordinate decisions under constitutional constraints. Its Global Value Index (GVI) research proposes a unit of account that reflects broad international purchasing power rather than the fortunes of one national currency. An optional asset-economy layer could enable secured lending against verified real-world assets, legal fractional ownership, and durable community-owned commons.

These ideas belong to one vision, but **must not be built as one tightly coupled application, chain, treasury, or authority**. They are separate trust domains with sharply different failure modes. Cryptography can authenticate messages; it cannot establish that a key corresponds to one unique human. A blockchain can settle tokens; it cannot independently establish legal title to land. An oracle can report a price target; it cannot by itself stabilize a currency. Open-source software can be inspected; that does not guarantee fairness, security, or inclusion.

This document establishes a proposed constitution of design constraints, a modular reference architecture, explicit monetary and asset-accounting models, a threat and risk register, an evidence-based research program, and a gated path to a small integrated prototype. **The first deliverable is verified feasibility, not a live token launch.**

# 1. Founding Thesis and Scope

## 1.1 The originating sequence

1. **The United Nations of the Earth:** Equal dignity, universal rights, democratic cooperation, global and regional institutions, AI-assisted analysis, transparent records.
2. **Building the Foundation:** Self-sovereign cryptographic identifiers, authenticated messages, relay-to-peer-to-peer networking, communication, and civic coordination.
3. **Building an Open Source Global Stable Coin:** A global reference value, protocol-bounded issuance, distributed oracles, and limits on governance power.
4. **Ancillary asset-economy proposal:** Verified collectibles and property can support secured credit; communities can pool funds, acquire assets through legal entities, and build protected commons.

The sequence is conceptual, **not** a mandate to deploy an internet, a sovereign government, and a currency simultaneously.

## 1.2 Intended outcomes

- People retain meaningful control over their cryptographic identities, private communications, and assets.
- Communities can coordinate and audit decisions without requiring one exclusive platform operator.
- A reference unit for cross-border value can be independently calculated and scrutinized.
- Monetary rules are explicit, publicly verifiable, and resistant to discretionary asset freezes and arbitrary issuance.
- Real-world assets can be represented only when enforceable ownership, custody, valuation, and recovery mechanisms exist.
- Public-benefit assets may be collectively owned without becoming an involuntary bailout mechanism for speculative or private losses.
- Anyone can independently implement compatible software, scrutinize designs, propose alternatives, and exit a particular service or community.

## 1.3 Out-of-scope promises

UNE does **not** promise to supersede sovereign nations, remove lawful jurisdiction over physical assets, guarantee stable prices, guarantee censorship-proof global connectivity, make every message permanent, eliminate every intermediary, or create a global democracy merely through key generation. UNE must not present its name as affiliation with the existing United Nations.

# 2. The North Star Alignment Charter

This charter is proposed for adoption through a later legitimate, inclusive process. It is not already ratified.

| ID | Principle | Engineering implication | Counterexample / breach |
|---|---|---|---|
| N1 | Equal human dignity | Equal baseline civil and political rights; accessible pathways for participation | Wealth or algorithmic reputation purchases constitutional votes |
| N2 | Individual sovereignty | User-held keys and meaningful exit, portability and recovery | Platform can unilaterally erase identity or lock up funds |
| N3 | Non-domination | No indispensable actor controls identity, speech, treasury or monetary rules | Single root key, oracle provider, custodian or governance bloc |
| N4 | Constitutional restraint | Ordinary majorities cannot arbitrarily confiscate property or erase fundamental rights | Governance vote can blacklist a wallet |
| N5 | Privacy by design | Minimal public personal data; confidential ballots; selective disclosure | Public ledger links every vote to financial transactions |
| N6 | Verifiability | Open specifications, reproducible builds, public audits and evidence | 'Trust the AI' substitutes for verifiable claims |
| N7 | Due process and remedy | Contestable decisions, appeal paths, independent dispute resolution | Reputation penalty is opaque and irreversible |
| N8 | Monetary integrity | No unbacked discretionary issuance; transparent liabilities and redemption rules | Treasury can print against an unverified valuation |
| N9 | Commons protection | Explicit fiduciary duties; protected non-pledgeable assets | Shared land automatically absorbs private bad debts |
| N10 | Peaceful federation | Voluntary, plural communities and interoperable standards | Central council asserts authority over nonconsenting people |
| N11 | Safety and stewardship | Adversarial testing, environmental/resource accounting, safeguards for abuse | Immutable system cannot recover from known exploit |
| N12 | Human accountability | AI advises; identifiable accountable humans/institutions decide | Model autonomously adjudicates binding rights |

**Priority rule:** When objectives conflict, protect fundamental rights, financial solvency and safety before optimizing engagement, influence, growth, convenience or token adoption. The constitution requires rights-balancing and due process; it is not a promise that every claimed right is unlimited in all contexts.

# 3. Reference Architecture and Trust Boundaries

## 3.1 Layers (independent, interoperable)

**A. Constitutional and standards layer.** Publishes rights principles, formal protocol invariants, governance boundaries, open interface specifications, version history, and an amendment/voluntary migration process. It is a *governance framework*, not a magical on-chain veto over all real-world institutions.

**B. Identity and communications (Foundation Protocol).** Key generation, device security, key rotation/recovery, signed messages, optional encrypted content, content addressing, multiple relays, replication and community moderation. No mandatory single identity provider. Signed messages prove key authorization and content integrity, not human uniqueness or enduring message availability.

**C. Participation and governance.** Community membership rules; privacy-preserving eligibility where feasible; human-rights safeguards; verifiable ballots; proposal and treasury workflows; representation and deliberation; independent appeals; contextual reputation for narrow tasks. One-person-one-vote must remain a *research goal* until robust Sybil resistance and inclusion are demonstrated.

**D. Monetary research and settlement.** GVI calculation, independent oracle processes, market design, collateral accounting, mint/redemption rules, risk controls and a transferable unit on a separately evaluated existing settlement network. No token should have an undisclosed administrator freeze function. Network-level censorship and legal risk remain possible.

**E. Real-world asset services.** Independent legal custodians, lenders, appraisal firms, registries, vaults, title agents and trusts interfacing through auditable proofs and contracts. They are not coequal to a trustless token ledger: their obligations are enforceable through physical and legal systems.

**F. Commons and public-benefit organizations.** Local legal entities own, steward and govern shared property; membership rights and fiduciary duties vary by jurisdiction. Commons assets should be partitioned from risky lending and protected by restrictions on pledging and liquidation.

**G. AI advisory interface.** Open and inspectable systems summarize, translate, simulate, detect anomalies and explain decisions. AI outputs are evidence-linked, uncertainty-aware, contestable and nonbinding unless a human-defined narrow administrative task is explicitly delegated with oversight.

## 3.2 Decoupling requirements

- **No common root administrator:** A compromise of one application, council, wallet service or oracle operator must not grant control over all modules.
- **No mandatory proprietary endpoint:** Independent clients, relay operators and data sources must be feasible.
- **No circular economic dependency:** A governance token, currency, and commons reserve must not all derive their solvency from each other's market price.
- **No implicit cross-guarantees:** A borrower's secured loan is not a claim on the community land trust unless a legally specific and transparently authorized guarantee exists.
- **No premature bespoke blockchain:** Research and test monetary mechanisms on established settlement infrastructure before considering a new consensus protocol.
- **Versioned interoperability:** Modules communicate via documented schemas, authenticated messages, capability grants, and audit artifacts; deprecation includes migration and exit procedures.

## 3.3 Fundamental flow

Citizen-controlled identity → authenticated/encrypted communication → eligible community participation → constitutional decisions and transparent treasury accounting. In parallel: independent market data → audited GVI calculation → simulated monetary policy → permissionless settlement. Separately: verified off-chain ownership → enforceable legal custody/secured lending or equity transfer → audited on-chain representations where appropriate. No arrow here implies automatic legal title, purchasing-power stability, or political legitimacy.

# 4. Identity, Privacy, Speech, and Civic Participation

## 4.1 Three identities that must not be conflated

1. **Cryptographic identity:** Proof that a message or transaction was signed by a controlled key.
2. **Human uniqueness / eligibility:** Evidence that a particular natural person meets a defined participation rule and is counted once.
3. **Legal or asset identity:** Evidence accepted under applicable rules for deeds, banking, regulated finance, taxation, or enforceable contracts.

A person may use multiple pseudonyms for safety and privacy while presenting a one-time, privacy-preserving voting eligibility proof to a community. No currently assumed mechanism achieves global uniqueness, privacy, accessibility and perfect coercion resistance simultaneously. This is an explicit open research problem.

## 4.2 Essential identity safeguards

Local key creation is only a beginning. The architecture must include multi-device use, recovery from loss/theft, key rotation, delegated access, revocation of compromised keys, account portability, metadata minimization, accessibility and safety for users subject to coercion. Community moderation is compatible with protocol-level expressive freedom: people cannot be guaranteed compulsory hosting or amplification by every relay.

## 4.3 Message guarantees

A valid signature supports authenticity against a public key, not truthfulness. Hashes can reveal later modification; they do not guarantee immutable availability. End-to-end encryption is a separate protocol requirement, not a property of signatures. Large or personal content should generally be encrypted or off-chain; where necessary, publish minimal commitments rather than permanent plaintext. Design for lawful data handling and narrowly scoped community moderation.

## 4.4 Democratic design

Constitutional rights are not a function of account age, token balance or a general-purpose social score. Reputation may inform specialized roles—such as oracle accuracy, technical auditing and forecast calibration—but must be domain-specific, explainable, appealable, resistant to collusion and incapable of removing fundamental participation rights. The Global Council/Regional Assembly idea remains a possible federated constitutional model, not a preauthorized world government. Legitimate representation requires consent, transparent chartering, pluralism, terms and recall, conflict-of-interest rules, and realistic limits on jurisdiction.

# 5. The Global Value Index: Research Specification

## 5.1 First resolve the measurement problem

The claim 'average value of world money' is not well-defined without a reference good, purchasing-power standard, time period and exchange-rate convention. A GDP-weighted mean of fiat exchange rates can move merely because of the chosen numeraire and does not itself measure cost of living or real purchasing power.

UNE should evaluate **two distinct candidate units** rather than hard-code a solution:

- **FX-basket reference:** A rules-based basket of currencies with published units and weights. Useful as a diversified nominal benchmark; not inherently an inflation-proof global purchasing-power measure.
- **Global purchasing-power reference:** A reproducible basket/index of representative goods and services drawing on PPP and inflation methodologies, with clear geographic and temporal coverage. More closely matches the mission, but introduces data lags, regional comparability, revision and manipulation risks.

Neither is automatically best. Select by transparent backtesting and independent critique.

## 5.2 Candidate formula (illustrative—not approved)

For a published set of countries or regions *i*, let *Pᵢ(t)* be a comparable local consumption price index transformed into a declared common reference, and let *wᵢ(t)* be bounded, nonnegative weights summing to one. A research candidate is a weighted geometric index:

**GVI(t) = GVI(t₀) × exp[ Σᵢ wᵢ(t) · ln(Pᵢ(t) / Pᵢ(t₀)) ].**

This expression is *not complete* until the price normalization, currencies, exchange rates, PPP linkage, revisions, representative baskets, time-varying weights, and data-quality process are specified. It is a research scaffold, not an issuance rule.

### Research tests

- Long-run realized purchasing-power stability across regions; distribution of outcomes, not merely global average.
- Sensitivity to omitted countries, stale price reports, FX shocks, basket revisions and structural breaks.
- Transparent maximum weight and change-per-epoch bounds; handling of countries with unreliable or missing data.
- Publication of uncertainty intervals, lag and error estimates, and revision histories.
- Comparison with the US dollar, SDR-like baskets, inflation-indexed references, and simpler benchmarks.

## 5.3 Oracle architecture

Oracles must publish signed source-attributed observations, confidence metadata, timestamp, versioned methodology and dispute windows. Median aggregation alone does not ensure decentralization when all nodes consult the same upstream provider. Incentives and slashing must be analyzed against maximum potential market-manipulation profit, correlated failures and censorship. During unreliable data, the protocol must have predetermined fail-safe behavior such as stale-price thresholds and suspension of **new credit issuance**; it must not silently empower an administrator to seize existing user balances.

# 6. Money: Stability, Backing, Issuance, and Redemption

## 6.1 Four different objects

- **Index:** A benchmark number describing a specified reference value.
- **Unit of account:** A denomination used to quote prices and obligations.
- **Settlement token:** A transferable digital asset governed by a specific chain and contract.
- **Redemption claim:** A legal or protocol-enforceable right to exchange a token for collateral or another asset under stated conditions.

A GVI can exist without a tradeable token. A tradeable token can exist without meaningful redemption. Price stability cannot be inferred from either alone.

## 6.2 Candidate monetary mechanisms to compare

**Model M0: GVI-only reference.** Publish a verifiable open index with no token or balance-sheet risk. Lowest-complexity, highest-value first experiment.

**Model M1: Overcollateralized crypto-backed token.** Mint only upon posting accepted on-chain collateral. Enforce debt ceilings, liquidation thresholds, protocol solvency constraints and transparent redemption mechanics. Native ETH collateral minimizes issuer freeze risk but introduces volatility and liquidation cascades; more collateral types increase correlated dependencies.

**Model M2: Reserve-backed claim.** Issue against segregated audited liquid reserves and explicit redemption rights. May stabilize value under normal conditions but introduces custodial, banking, regulatory and seizure dependencies. It cannot honestly claim full issuer-independence.

**Model M3: Hybrid / RWA-backed token.** Consider only after demonstrating legally enforceable claims, timely redemption and stress-tested liquidity. Illiquid land or collectibles are not equivalent to liquid reserves.

**Pure algorithmic uncollateralized issuance** should not be the default model; it must meet especially stringent adversarial tests before consideration.

## 6.3 Monetary invariants (proposed)

1. No administrator privilege to blacklist arbitrary addresses or confiscate settlement balances in the native protocol.
2. No unbacked, discretionary monetary issuance or unreported contingent liabilities.
3. Minting and burning are attributable to explicitly defined, independently testable transactions or rules.
4. Debt, collateral valuation, reserve sufficiency, liquidation and redemption order are publicly auditable without revealing unnecessary personal information.
5. Parameter updates and software migrations do not silently override existing owners' contracts. Proposed replacements use opt-in migration where possible.
6. Supply *may* expand or contract within predetermined risk and collateral constraints; a universal hard cap must not be asserted compatible with a stable peg without proof.
7. Nonpayment and market stress require predefined insolvency waterfalls; 'backed' is not a substitute for actual exit liquidity.

## 6.4 Stress model and order of losses

Test price collapse, demand run, flash liquidity shock, oracle outage, collateral depeg, reserve impairment, validator censorship, emergency legal action, smart-contract exploit and chain reorganization. Specify the loss waterfall before launch: borrower equity/collateral → designated insurance or buffer (if any) → explicitly disclosed risk-bearing capital → residual holder shortfall if unavoidable. **Never quietly transfer these losses to the commons or taxpayers.**

## 6.5 Explicit freeze-resistance claim

A native token with no blacklist, proxy upgrade authority or administrative pause can materially resist selective issuer freezes; Liquity V1/V2 provide useful patterns to study, not a blueprint to copy blindly. Token sovereignty does not protect against wallet compromise, service refusal, validator censorship, sanctions, litigation, exchange rejection, collateral seizure, or failure to maintain a target peg.

# 7. Asset-to-Currency Operating System

## 7.1 Exactly what is being proposed

The asset idea has **three different financial/legal pathways** that require separate contracts and accounting:

| Path | Asset ownership | Cash/currency received | Risk and claim |
|---|---|---|---|
| Secured credit | Borrower generally retains legal title, subject to security interest | Loan proceeds; debt remains even after funds are spent | Default, foreclosure, collateral shortfall |
| Fractional sale | Buyer obtains defined ownership/economic rights if legally valid | Sale consideration; seller has transferred rights | Securities, governance, title and custody complexity |
| Contribution to common trust | Trust or legal entity receives title | Membership, grant, sale price or other defined consideration | Fiduciary duties, community control, restrictions on alienation |

Spending minted currency **does not** progressively transfer fractions of a collateralized card or deed to the network. Any such transfer requires separately defined rights and enforceable agreements.

## 7.2 Collateral intake workflow

Applicant consent and verified legal identity as needed → chain of title and lien search → provenance/custody and jurisdictional eligibility → independent appraisal with uncertainty bounds → conservative haircut and loan-to-value cap → perfected security interest / custody contract → debt issuance under audited limits → ongoing revaluation and margin triggers → repayment, sale or enforceable default resolution. For land, add taxes, zoning, environmental obligations, insurance and tenant/occupant protections. For collectibles, add authenticity, vault controls, insurance, saleability and valuation concentration.

**Illustration, not a loan offer:** A collectible appraised at $1,000,000 might support a $400,000 secured loan at 40% initial LTV. The borrower's debt remains $400,000 after the loan proceeds change hands. An appraised value is not guaranteed cash proceeds in a distressed auction.

## 7.3 Commons acquisition and stewardship

Communities may voluntarily pool capital through appropriately constituted trusts, cooperatives or other entities. The deed belongs to the legal entity; membership interests and governance powers are documented, and blockchain receipts can improve transparency. Some commons land may be designated non-pledgeable or subject to heightened consent and legal restrictions. Public-access rights must be legally established, not inferred from crowdsourced token ownership.

### Commons firewall

- No automatic use of community land to cover private borrowing losses.
- No automatic monetary backing based on speculative appraisals of shared land.
- Separate balance sheets, treasury accounts, insurance, fiduciaries and disclosures for each entity.
- Any risk-bearing reserve contribution must be explicit, consented to, capped, independently priced and legally valid.
- A commons must remain viable if the monetary token fails completely.

# 8. Governance, Constitution, and Constitutional Change

## 8.1 Federated legitimacy rather than imposed sovereignty

Start as a voluntary standards and coordination network. A UNE council cannot credibly claim governance over nonconsenting people. Pilot with constituted communities and transparent accession/exit processes; only expand jurisdiction on demonstrated legitimacy and applicable legal authorization.

**Possible institutions:** Constitutional review and rights ombudsperson; technical standards council; elected community assemblies; monetary risk committee with sharply limited *advisory* role; independent audit function; asset trust fiduciaries; appeals and dispute-resolution forums. Avoid creating one master committee holding keys to all systems.

## 8.2 Separation of powers

**Constitutional layer:** records and interprets rights, governance boundaries, and voluntary amendment procedures.  
**Community governance:** allocates authorized common resources and adopts local policies with notice, equal rights, and appeal.  
**Money contracts:** mechanically enforce settlement/issuance rules; neither popularity nor reputation gives arbitrary confiscation authority.  
**Asset entities:** act within legal mandates, title registries, fiduciary duties and courts; their powers are not concealed as 'trustless.'  
**AI:** observes, explains, models, flags conflicts and drafts options; no unilateral rights adjudication or treasury spending.

## 8.3 What 'immutable rights' can responsibly mean

An immutable contract is not an immutable civilization. Preserve a constitutional commitment to non-domination, due process, and equal human dignity while using versioned, reviewable implementations. For grave vulnerabilities, publish evidence, alerts, safe migration and explicit user choice wherever feasible. A forced code upgrade that can rewrite private holdings would contradict the no-unilateral-control objective.

# 9. Safety, Abuse, and Legality

## 9.1 Threat model

| Threat | Potential impact | Primary response |
|---|---|---|
| Sybil vote creation | Democratic capture | Eligibility research, private proofs, audits and inclusion appeals |
| Reputation cartel | Unequal political power | Domain-specific scores; no constitutional vote weighting |
| Key loss or coercion | Permanent account loss / extortion | Recovery, rotation, guardianship options and coercion-aware UX |
| Relay / ISP blocking | Speech and availability failures | Multi-relay, offline transport research, replication and diversity |
| Oracle manipulation | Unjust minting or liquidation | Independent sources, economic attack modeling, bounded fallbacks |
| Depeg / run | Holder losses, insolvency | Credible redemption, buffers, stress tests and disclosed loss waterfall |
| Asset fraud | Undersecured lending | Title verification, independent appraisal, custody and audits |
| Capture of physical asset | Unenforceable backing | Jurisdictional risk and segregation; no false trustlessness claims |
| AI misinformation / bias | Delegitimized decisions | Human sign-off, audit trails, reproducible evidence, appeals |
| Protocol exploit | Irrecoverable losses | Formal methods, audits, bug bounties, limited pilots, migration plans |
| Financial misuse | Legal and human harm | Risk-based lawful interfaces, independent legal review, narrowly tailored protections |
| Foundation capture | Hidden control | Published conflicts, plural operators, funding diversity, exit rights |

## 9.2 Regulatory reality

A globally available token, lending protocol, exchange, property investment vehicle and community trust can trigger separate regulatory responsibilities. Classification depends on jurisdiction, functionality, management, redemption promises and actual control. Legal review is required **before** any public fundraising, custody, credit issuance, fractional real-asset sale or tradable value-bearing launch. Neither decentralization rhetoric nor open-source licensing creates legal immunity. Privacy and compliance must be designed together rather than solved through a universal blacklist.

## 9.3 Environmental and social impact

Track energy use, infrastructure resilience, physical asset stewardship, access for low-connectivity populations, language availability, disability access, ability to appeal mistaken denials, and power concentration. A global monetary benchmark must evaluate regional winners and losers, not merely report low average volatility.

# 10. Sustainability and Public-Goods Economics

'Gift to humanity' should describe openness and public purpose, not an assumption that systems have zero operating cost. Specify the budget for security reviews, relay operations, storage, oracles, governance, translation, legal support, insurance and physical custody. Test a mix of modest usage fees where appropriate, independent grants, transparent donations, competitively supplied services and separately budgeted community funds. A critical function must not depend on one donor or entity without a defined continuity plan.

Separate **protocol costs**, **commercial optional services**, **monetary reserves**, **asset-custody balance sheets**, and **commons treasuries**. A nonprofit standards body may steward specifications without owning or guaranteeing all network assets. Any commercial service provider can compete through open interfaces and should have no privileged monetary keys.

# 11. Development Program and Hard Gates

**Operating discipline:** A single evidence ledger, small falsifiable experiments, reproducible simulations, red-team reviews, published objections, and explicit stop/go criteria. Research artifacts are versioned; every phase ends with a decision, not merely more code.

| Phase | Objective | Deliverables | Gate: do not proceed until… |
|---|---|---|---|
| 0 — Charter | Establish scope and non-negotiables | Constitution draft; glossary; threat model; stakeholder map | No unresolved contradiction hidden as a guarantee |
| 1 — GVI index only | Show reproducible global-value measurement | Open datasets; methodology; backtests; sensitivity plots | Outperforms or meaningfully complements simple baselines on published criteria |
| 2 — Monetary simulation | Test actual stabilization and solvency | Agent-based scenarios; issuance/redemption model; loss waterfall | Survives defined shock suite or research is revised/terminated |
| 3 — Foundation hardening | Prove communication and identity claims | Independent relays; key recovery; encrypted channels; verifier tooling | Integrity, privacy and failure tests pass; no exaggerated availability claims |
| 4 — Governance pilot | Demonstrate legitimate, bounded decisions | Small opt-in community pilot; eligibility research; appeals | Sybil, coercion and exclusion risks measured and accepted by pilot participants |
| 5 — Testnet integration | Integrate components without value at stake | Test tokens; simulated assets; public dashboard; adversarial exercise | Independent security and economic reviews; no critical unresolved findings |
| 6 — Asset-economy pilot | Test one legally bounded asset workflow | Custody/legal opinions; one jurisdiction; segregated balance sheets | Title, enforceability, liquidation, consumer protections independently verified |
| 7 — Public-value consideration | Decide whether real money is warranted | Legal classification, audited contracts, reserves, disclosures, incident process | Explicit multidisciplinary launch authorization; never automatic |

## 11.1 First 90 days: a focused research plan

**Days 1–30 — Constitutional alignment.** Freeze v0.1 terminology; adopt the twelve north-star principles as provisional tests; identify conflicts; publish data definitions, threat boundaries, and the list of powers deliberately denied to operators. Draft two mathematical GVI alternatives and an evaluation protocol.

**Days 31–60 — GVI evaluation.** Reproducibly test the FX basket and purchasing-power basket with documented public data; show sensitivity to weights, lags, shocks, regional inflation and missing observations. Publish counterarguments and distinguish index usefulness from token feasibility.

**Days 61–90 — Monetary design decision.** Simulate at least two collateral/redemption architectures; report peg deviations, insolvency probabilities under chosen assumptions, liquidation throughput, oracle exploit economics, and reserve adequacy. Produce a stop/go recommendation for a *testnet only*. Parallel work is limited to standards/interface hardening, not a live land-backed currency.

## 11.2 Acceptance metrics (to be defined before testing)

- GVI: median and tail purchasing-power error across regions; reproducibility; revisions; lag; manipulation exposure.
- Money: stress peak peg deviation, recovery time, collateral coverage, shortfall and redemption queue; worst-case not just mean.
- Identity: false duplicate rate, false exclusion rate, privacy leakage, recovery success and coercion resistance.
- Network: signed-message verification, relay diversity, availability under partial outage, censorship cost and recovery.
- Governance: turnout legitimacy, concentration, appeals, accessibility, time to dispute resolution.
- Asset lending: loan-to-liquidation recovery, valuation drift, legal enforceability and custody failures.
- Sustainability: independent operator count, cost per activity, runway, donor concentration, and critical-service substitutability.

Do not insert invented numeric thresholds. Research owners must set and publish them prior to experiments; stakeholders then assess whether the evidence meets them.

# 12. Decision Register: Open Questions Requiring Explicit Resolution

**D1 — Political legitimacy:** Is UNE ultimately a voluntary confederation, a standards-based public utility, an advocacy movement, or an aspirational global government? **Default for research:** voluntary federation with no sovereign claim.

**D2 — Voting:** What independently auditable mechanism distinguishes one eligible human from unlimited keys without creating a universal surveillance identifier? **Default:** small consent-based pilot; no global voting claim.

**D3 — Reputation:** Where is reputation permissible? **Default:** narrow advisory/operational contexts, never baseline rights or constitutional vote weight.

**D4 — Global value:** FX basket, consumption/PPP reference, or other globally meaningful standard? **Default:** benchmark both; no designated official GVI yet.

**D5 — Monetary economics:** What creates a two-way arbitrage/redemption path and controls losses? **Default:** simulate overcollateralized models; publish failure cases.

**D6 — Immutability:** Which parts can update without arbitrary seizure? **Default:** immutable ownership/settlement invariants; voluntary version migrations; explicit risk switches for *new* exposures where justified.

**D7 — Settlement:** Existing chain versus new consensus network? **Default:** existing infrastructure for research and testnet.

**D8 — Asset ownership:** Loan, sale or trust contribution? **Default:** separate contracts, ledgers, and legal disclosures.

**D9 — Reserve segregation:** Can commons property ever support money issuance? **Default:** prohibited absent a separately adopted, rigorously audited, legally enforceable and capped arrangement; never automatic.

**D10 — Legal perimeter:** Which jurisdiction and operator activities come first? **Default:** no value-bearing offering until specialized counsel and documented controls.

**D11 — Data rights:** What is public, encrypted, erasable, and anchored? **Default:** minimal public commitments and user-controlled encrypted payloads.

**D12 — Failure governance:** What happens after a catastrophic exploit or constitutional dispute? **Default:** disclose, contain optional services, provide independent review and voluntary migration; no secret superuser.

# 13. A North Star Test for Every Future Proposal

Before approving a feature, funding mechanism, governance change, collateral type or AI agent, answer **all** the following in writing:

1. **Rights:** Whose freedom, privacy, equality or due process is affected? Can they contest and exit?
2. **Power:** What actor gains a discretionary capability? Could it be used to censor, seize, inflate or exclude?
3. **Trust:** Which claims require an oracle, custodian, court, administrator or hardware operator?
4. **Accounting:** Who owns each asset, who owes each liability, who absorbs losses and under what enforceable rule?
5. **Economic stability:** What incentive, redemption right or balance sheet makes the promised value credible under stress?
6. **Adversarial resilience:** What happens if inputs lie, nodes disappear, markets panic or an operator is coerced?
7. **Interoperability:** Can users move to a competing implementation without losing identity, rights or legitimate property claims?
8. **Evidence:** What measurable test could falsify the proposal, and what result would stop the launch?

**Alignment verdicts:** **Aligned** (all material answers documented and no constitutional breach); **Conditional** (the idea may proceed only as research with explicit gates); **Rejected** (violates a foundational invariant or lacks an ethically/legal defensible path). No feature qualifies merely because it uses AI, blockchain, decentralization or a democratic vote.

# 14. First Implementation Decision

**Build the GVI as an open, reproducible index before minting a coin.** This provides immediate intellectual value and tests the central economic thesis without placing users' wealth at risk. In parallel, harden the Foundation Protocol's authenticated messaging and separation of identity/eligibility; keep the real-world asset economy at the legal-and-accounting design stage.

The initial integrated prototype should demonstrate **one signed citizen proposal, one independently verifiable community decision, one published GVI observation, and one simulated currency transaction** across documented interfaces. No real collateral, no public investment solicitation, no assumed governmental recognition and no claim of guaranteed stability.

# Conclusion

UNE's greatest opportunity is not to make everything immutable. It is to make **power constrained, claims verifiable, systems substitutable, participation meaningful, and value creation accountable**. A lasting network must be resilient to its founders, not dependent on their continued authority.

The project succeeds only if individuals can remain free when a council disagrees with them, a company shuts down, a currency depegs, an oracle lies, a property custodian fails, or a model produces the wrong answer. The constitutional commitment is permanent as a design aspiration; every practical mechanism remains subject to evidence and correction.

**North Star:** *A voluntary global civic and economic commons where no actor is indispensable, no person's baseline rights are for sale, and no monetary or technological promise outruns its evidence.*

# Appendix A — Founding Sources and Research References

**Founding materials (provided in full by the project originator):**

1. Eddie Boscana, “The United Nations of The Earth,” 31 October 2026. https://eddieboscana.com/journal/the-united-nations-of-the-earth
2. Eddie Boscana, “Building the Foundation: Creating a NEW Internet for The United Nations of the Earth,” 31 October 2026. https://eddieboscana.com/journal/building-the-foundation
3. Eddie Boscana, “Building an Open Source Global Stable Coin,” 31 October 2026. https://eddieboscana.com/journal/building-an-open-source-global-stable-coin
4. Ancillary discussion supplied in conversation: secured collectible collateral, deeds, collective land trusts, and the asset-to-currency operating-system concept.

**Relevant external technical and methodological references (not endorsements):**

5. W3C, Decentralized Identifiers v1.0. https://www.w3.org/TR/did-core/
6. World Bank, International Comparison Program methodology. https://www.worldbank.org/en/programs/icp/methodology
7. Liquity V1 official protocol documentation (noncustodial, governance-free architecture). https://docs.liquity.org/liquity-v1
8. Liquity V2 whitepaper and architecture. https://liquity.gitbook.io/v2-whitepaper
9. Bank for International Settlements, *Annual Economic Report 2025*, next-generation monetary and financial system (discussion of singleness, elasticity and integrity). https://www.bis.org/publications/aer-2025/next-generation-monetary-financial-system

**Scope note:** These references support precedent and research methods, not proof that UNE's intended system is secure, stable, legally authorized or economically feasible. Legal classifications and operational controls require current jurisdiction-specific professional review.

# Appendix B — Terms That Must Remain Distinct

**Immutable:** A particular code/record cannot be changed by specified parties; not 'impervious to exploitation.'  
**Censorship-resistant:** No single identified party can reliably prevent all valid participation or transfers; not 'every transaction is always included.'  
**Self-custodial:** User controls signing keys; does not imply an unfreezable asset.  
**Decentralized:** No actor holds decisive operational authority across a defined trust boundary; a measurable claim, not a label.  
**Stable:** Low deviation relative to an explicitly defined benchmark over a defined period; not a guarantee of purchasing power everywhere.  
**Collateral:** Asset supporting a claim, subject to valuation and enforcement; not automatic issuance capacity.  
**Tokenized deed:** Digital representation of asserted rights; not proof that local title law recognizes transfer.  
**Commons:** Assets governed under a specified public-benefit, cooperative or trust framework; not necessarily government-owned public land.  
**Governance:** Legitimate rule-setting over a defined scope, constrained by rights and due process; not blanket control over users or money.
