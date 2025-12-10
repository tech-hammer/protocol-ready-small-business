# Protocol-Ready Small Business Standard (PRSB)
## Version 0.1 — Draft

---

## 1. PRINCIPLE

A protocol-ready small business is one whose:
- identity is sovereign (Nostr keys)
- payments are sovereign (Bitcoin + Lightning)
- discovery is portable and open (catalog schemas)
- fulfillment is transparent and verifiable (signed artifacts)
- operations are observable (SLA, resolution, delivery logs)
- customer engagement includes contribution, not passive consumption
- reputation is a first-class economic primitive

---

## 2. IDENTITY REQUIREMENTS

A business must:
1. Generate a **dedicated business Nostr keypair**
2. Securely back up the private key
3. Use that key for:
   - identity
   - announcements
   - commit signatures
   - release signatures
   - verified provenance of deliverables
4. Publish:
   - business public key
   - support channels (Nostr DMs)
   - Lightning address

Identity **must not** depend on:
- Facebook groups
- platform logins
- closed CRM identity stores

---

## 3. PAYMENT REQUIREMENTS

A protocol-ready business must:
- support Lightning invoices
- support LNURL-pay
- support static Lightning address for inbound microtransactions
- maintain sats treasury allocation
- support V4V (value-for-value) interactions

Payment **must not** depend on:
- Stripe
- PayPal
- platform intermediaries
- chargeback models

Settlement must be:
- instant
- final
- peer-to-peer

---

## 4. DISCOVERY REQUIREMENTS

The business must publish **an open catalog** in machine-readable form:

- JSON catalog file
- publicly accessible endpoint (self-hosted)
- Nostr event mirroring for discovery
- versioning and price transparency

Discovery **must not** require:
- Shopify
- Amazon
- Google Merchant
- proprietary feed formats

Because:
> discovery becomes protocol-driven, not platform-driven.

---

## 5. REPUTATION & TRANSPARENCY

Fulfillment, support, and dispute logs must be:
- timestamped
- signed by the business key
- tied to machine-readable SLA artifacts
- partially or fully visible depending on privacy constraints

Each engagement must generate:
- a signed “work artifact” documenting delivery

Optional:
- transparent SLA metrics
- dispute resolution documents
- satisfaction endorsements as zaps

Reputation must be:
- observable
- cryptographically provable
- portable between interfaces

Reputation **must not** be:
- testimonials controlled by the seller
- ad-optimized reviews
- manipulate-able identities

---

## 6. PARTICIPATION REQUIREMENT

Customers must be able to:
- participate in documentation
- participate in QA
- propose improvements
- report UX friction
- produce localization or templates
- receive micro-payments for contributions

Businesses must:
- reward contributors using sats
- treat community participation as a delivery input

This converts customers into **co-creators**, not passive buyers.

---

## 7. OPERATIONS REQUIREMENTS

Business processes must be:
- versioned
- documented
- reproducible
- minimally dependent on SaaS
- sovereign where possible

Artifacts include:
- onboarding checklists
- custody diagrams
- support protocols
- refund/dispute flows
- security audit steps
- vendor evaluation criteria

Ops transparency is the **brand**, not persuasion.

---

## 8. DISPUTE MODEL

Disputes must:
- produce a visible SLA artifact
- show escalation steps
- record refund path
- be tied to Lightning settlement artifacts
- be publicly or privately visible depending on sensitivity

A dispute resolved successfully **increases reputation**, not risk.

---

## 9. IMPLEMENTATION VALIDATION

Every major clause in this standard must eventually be validated with:

- at least one small business adopter
- one transparency artifact
- one end-to-end Lightning settlement
- one onboarding example
- one QA cycle
- one dispute resolution example
- real metrics

Unvalidated clauses remain experimental.

---

## 10. VERSIONING & CHANGE MANAGEMENT

- All revisions are signed with the business key
- Each version is announced on Nostr
- Each change has:
  - issue discussion
  - implementation notes
  - UX validation status

This ensures the **standard evolves with proof, not theory**.

---

## 11. ECONOMIC OBJECTIVE

The business becomes a **sovereign node**, not a vendor:

- identity anchored by keys
- discovery anchored by open catalog
- competence anchored by transparency
- revenue anchored by V4V micro-services
- reputation anchored by observable artifacts
- community anchored by participation

The business no longer depends on:
- platforms
- ads
- SaaS lock-in
- third-party CRM identity
