---
name: aml-ctf-onboarding-au
description: >
  Free AML/CTF client onboarding and KYC skill for Australian accountants, tax agents,
  and professional service providers under the Tranche 2 AML/CTF regime (effective
  1 July 2026). Use this skill when onboarding a new client, preparing an engagement
  letter, conducting KYC checks, assessing whether your services are designated services,
  running a sanctions or PEP screen, or building your AML/CTF compliance documentation.
  Trigger phrases: "new client", "onboard", "KYC", "AML check", "CDD", "due diligence",
  "designated service", "engagement letter", "sanctions check", "PEP screening",
  "AML/CTF program". This skill walks you step by step through the entire process â€”
  from determining whether you are captured, through to completing and documenting CDD.
  Powered by Pereira Consulting (pereiraconsulting.com.au). Use at your own discretion
  â€” this skill provides general guidance only and does not constitute legal advice.
---

# AML/CTF Client Onboarding â€” Australia

A step-by-step onboarding skill for Australian accountants, tax agents, and
professional service providers under the Tranche 2 AML/CTF reforms.

**Effective date:** 1 July 2026
**Regulator:** AUSTRAC
**Legislation:** Anti-Money Laundering and Counter-Terrorism Financing Act 2006 (Cth),
as amended by the AML/CTF Amendment Act 2024; AML/CTF Rules 2025.

> **Disclaimer:** This skill provides general guidance to assist practitioners in
> understanding and navigating their AML/CTF obligations. It does not constitute
> legal advice and should not be relied upon as a substitute for professional advice
> tailored to your specific circumstances. Users should consult AUSTRAC's official
> guidance and seek independent legal advice where appropriate. No responsibility
> is accepted for any action taken or not taken based on this skill.
>
> **Powered by** [Pereira Consulting](https://pereiraconsulting.com.au) â€” independent
> Australian tax advisory for multinational enterprises.

---

## How This Skill Works

This skill guides you through a five-step onboarding process for each new client
engagement. Run it whenever you are taking on a new client or a new matter where
the scope of services may have changed.

```
Step 1: Am I Captured?        â†’ Designated service gateway test
Step 2: Who Is My Customer?   â†’ KYC information collection
Step 3: What Is the Risk?     â†’ ML/TF risk rating
Step 4: Verify and Screen     â†’ Identity verification, sanctions, PEP checks
Step 5: Document and File     â†’ Generate compliance records
```

Start at Step 1 for every new engagement. If Step 1 determines no designated
service is involved, no further AML/CTF steps are required.

---

## Step 1: Am I Captured? (Designated Service Gateway Test)

The AML/CTF regime captures specific **services**, not professions. You are only
a reporting entity if you provide one or more "designated services" under the Act.

Ask the user to describe the services they will provide on this engagement. Then
assess each service against the classification below.

### Services NOT captured (advisory / compliance work):

These are NOT designated services â€” no AML/CTF obligations arise:

- Preparing and lodging tax returns, BAS, and other compliance documents
- Providing tax advice and opinions
- Bookkeeping and management accounting
- Preparing financial statements and audit support
- Payroll services
- Tax planning advice (without drafting operative documents)
- Transfer pricing documentation and benchmarking studies
- R&D tax incentive claims
- ATO dispute and objection work
- General business advisory (e.g. "should I use a trust or a company?")
- Reviewing agreements prepared by others (limited to providing advice on them)
- SMSF compliance and administration (unless managing member funds beyond
  administration)

### Services that ARE designated services (Table 6):

If you provide ANY of these, you are captured:

- **Item 1:** Assisting in the planning or execution of a transaction to sell, buy,
  or transfer real estate (beyond providing advice â€” must directly advance the
  transaction)
- **Item 2:** Assisting in a transaction to sell, buy, or transfer a company, trust,
  partnership, or other legal arrangement
- **Item 3:** Receiving, holding, controlling, or managing a client's money, accounts,
  securities, or other assets (other than fees for your own services). This includes
  operating a trust account for client funds in connection with transactions.
- **Item 4:** Assisting with equity or debt financing transactions for a company,
  trust, or other legal arrangement (beyond general advice â€” must directly advance
  the transaction)
- **Item 5:** Providing a shelf company
- **Item 6:** Assisting in the creation or restructuring of a company, trust,
  partnership, or other legal arrangement. This includes drafting trust deeds,
  company constitutions, shareholder agreements, intercompany agreements, or other
  documents that give legal effect to the creation or restructuring.
- **Item 7:** Acting as, or arranging for someone to act as, a director, secretary,
  trustee, partner, or similar position on behalf of a client
- **Item 8:** Acting as, or arranging for someone to act as, a nominee shareholder
- **Item 9:** Providing a registered office address or principal place of business
  address for a company or other legal arrangement

### The Key Test: "Directly Advances" vs "Merely Influences"

AUSTRAC's guidance (October 2025) draws the line at whether your work **directly
advances** the transaction or outcome, or merely **influences** how the client
proceeds. General advice, options analysis, and ancillary services are not captured.
Drafting operative documents, lodging forms, managing funds, or taking steps that
make the transaction happen ARE captured.

**Example:** An accountant advises a client on the tax implications of setting up
a trust â€” NOT captured. The same accountant drafts the trust deed â€” CAPTURED.

**Example:** An accountant advises on the financial impact of pulling out of a
property settlement â€” NOT captured. A conveyancer preparing the contracts for the
same settlement â€” CAPTURED.

### Gateway Output

Present the assessment to the user:

```
DESIGNATED SERVICE ASSESSMENT
Client: [Name]
Date: [Date]

Proposed services:
1. [Service description] â†’ Not a designated service
2. [Service description] â†’ DESIGNATED SERVICE (Table 6, Item [X])

RESULT: [No AML/CTF obligations / CDD required â€” proceed to Step 2]
```

If no designated services are identified, save the assessment and stop. The
engagement can proceed under the firm's standard onboarding process.

If designated services are identified, proceed to Step 2.

---

## Step 2: Who Is My Customer? (KYC Collection)

Initial customer due diligence (CDD) must be completed **before** providing the
designated service. You must establish the following matters on reasonable grounds
(Act s 28):

1. **Identity of the customer**
2. **Identity of any person receiving the service on the customer's behalf**
   (e.g. beneficiaries of a trust)
3. **Identity of any person acting on behalf of the customer** and their authority
4. **Identity of any beneficial owners** (the individuals who ultimately own or
   control the customer)
5. **Whether any of the above are a PEP or subject to targeted financial sanctions**
6. **The nature and purpose of the business relationship**

### What to Collect â€” By Customer Type

**Individual:** Full name, date of birth, residential address, citizenship, tax
residence, occupation.

**Company:** Full legal name, ACN/ABN or foreign equivalent, country and date of
incorporation, registered office, principal place of business, directors, senior
officers, ownership and control structure (shareholdings, classes, distribution),
and beneficial owners (individuals holding 25%+ directly or indirectly, or
otherwise exercising control).

**Trust:** Full name and type of trust, ABN, country and date of establishment,
trust deed, trustees (individual and corporate), settlor, appointor, guardian/
protector, beneficiaries (or classes of beneficiaries), and beneficial owners
(all individuals with control â€” trustees, settlor, appointor, protector, and
controlling beneficiaries).

**Partnership:** Full name, ABN, partners (individual and entity), partnership
agreement, beneficial owners of entity partners.

**Listed company exemption:** If the customer is listed on the ASX or an equivalent
exchange with public disclosure requirements, you are not separately required to
identify beneficial owners. Document the listing status.

**Cannot identify beneficial owners:** If after reasonable steps you cannot identify
them, record the steps taken, the difficulties encountered, and collect the identity
of the CEO or equivalent. You are taken to have complied.

---

## Step 3: What Is the Risk? (ML/TF Risk Rating)

Assign an ML/TF risk rating to the customer based on the KYC information collected.
This determines the depth of CDD required.

### Risk Factors to Assess

**Customer factors:**
- Ownership structure complexity (multi-layered, nominees, opaque)
- Jurisdiction risk (operations in FATF grey/black list countries)
- PEP involvement
- Newly formed entity with no operating history
- Shell company with no substance
- Adverse media (financial crime, fraud, sanctions evasion)
- Source of wealth concerns

**Service/transaction factors:**
- Cross-border transactions or restructures
- Complex or unusual transaction structures
- No clear commercial or economic rationale
- Unusual urgency or pressure

**Delivery channel factors:**
- Non-face-to-face engagement without video verification
- Instructions from third parties rather than the client directly

### Risk Rating

**LOW:** Australian-resident customer, transparent ownership, low-risk jurisdictions,
clear commercial purpose. No red flags. No enhanced CDD triggers.

**MEDIUM:** Some risk factors present with moderate impact (e.g. operations in
medium-risk jurisdictions, moderately complex structure). No red flags or mandatory
enhanced CDD triggers.

**HIGH:** Significant risk indicators (e.g. complex opaque structures, high-risk
jurisdictions, foreign PEP involvement, no clear economic purpose, adverse media).

### CDD Level

| Risk Rating | CDD Level | What It Means |
|-------------|-----------|---------------|
| Low | Simplified CDD | Single-source verification; PEP/sanctions check via internet search and DFAT list; document justification for simplified approach |
| Medium | Standard CDD | Full KYC collection and verification from at least two independent sources |
| High | Enhanced CDD | All standard CDD plus: source of funds/wealth; senior management approval (mandatory for foreign PEPs); documented reasons for transactions; enhanced ongoing monitoring |

---

## Step 4: Verify and Screen

**IMPORTANT â€” Use your web search capability to actively perform the verification
and screening steps below.** Do not just tell the user to do these checks manually.
Run the searches yourself during the conversation and report the results.

### 4A. Entity Verification

For Australian companies, **use web search now** to verify the entity details:

- **Search ABN Lookup** for the customer's ABN or ACN. Search for
  "[ABN number] ABN Lookup" or go to abr.business.gov.au. Confirm the entity name,
  ABN, ACN, GST registration status, and business location match what the customer
  provided.
- **Search ASIC** for the company name or ACN if you need to verify directors and
  shareholding. Search for "[company name] ASIC" or "[ACN] ASIC company search".

For foreign companies, search the relevant foreign company register (e.g.
"[company name] ACRA Singapore" or "[company name] Companies House UK").

For trusts, verify the ABN on ABN Lookup if one was provided, and confirm the
trust type and trustee details match the trust deed information.

Report the verification results to the user, noting any discrepancies between
what the customer provided and what the public records show.

### 4B. Sanctions Screening â€” DFAT Consolidated List

**Use web search now** to screen each identified person and entity against the
DFAT Consolidated List. For each person and entity identified in Steps 2â€“3,
run a search:

- Search for "[person/entity name] DFAT sanctions consolidated list"
- Also search for "[person/entity name] Australian sanctions"

Screen ALL of the following:
- The customer entity itself
- All beneficial owners (individuals)
- All customer representatives
- Any parent entities or controlling entities

**Report the results for each person/entity screened.** State the date of
screening and whether a match was identified.

The DFAT Consolidated List is maintained at:
https://www.dfat.gov.au/international-relations/security/sanctions/consolidated-list

**If a match is found:** STOP. Inform the user immediately. The designated service
must not be provided. The user must not deal with the person's or entity's assets.
Advise the user to seek immediate legal advice and to notify the Australian
Federal Police and the Australian Sanctions Office.

### 4C. PEP Screening

**Use web search now** to check whether any identified individual is a Politically
Exposed Person (PEP). For each individual identified as a beneficial owner,
director, or customer representative:

- Search for "[person name] politician" or "[person name] government"
- Search for "[person name] [country] political" or "[person name] public office"
- Check whether they hold or have recently held a prominent public position in a
  government body or international organisation, or are a family member or close
  associate of such a person

PEP categories:
- **Foreign PEP:** Mandatory enhanced CDD with senior management approval
- **Domestic PEP:** Risk-based assessment
- **International organisation PEP:** Risk-based assessment

### 4D. Adverse Media Check

**Use web search now** to check for adverse media relating to financial crime,
fraud, money laundering, sanctions evasion, or terrorism financing for the
customer entity and all identified beneficial owners:

- Search for "[entity/person name] fraud" or "[entity/person name] money laundering"
- Search for "[entity/person name] sanctions" or "[entity/person name] financial crime"

Report any adverse media findings to the user. If adverse media is found, this
may increase the ML/TF risk rating and trigger enhanced CDD.

### 4E. Identity Verification for Individuals

For individuals (beneficial owners, customer representatives), the user will need
to verify identity using primary photographic ID (passport or driver's licence)
either in person, via video call, or through a digital ID verification provider
(e.g. Scantek, GreenID). This step must be completed by the user â€” it cannot be
done through web search.

**You do NOT need to keep copies of identity documents.** Record: what steps were
taken, what identifying information was presented (e.g. passport number, issuing
authority, expiry, name as shown), the date, and the outcome.

### 4F. Compile Screening Results

After completing all searches, present a summary:

```
VERIFICATION AND SCREENING RESULTS â€” [Client Name]
Date: [Date]

Entity verification:
- [Entity name]: [Confirmed via ABN Lookup / ASIC / foreign register â€” details match / discrepancy noted]

Sanctions screening (DFAT Consolidated List):
- [Entity name]: No match identified
- [Person 1 name]: No match identified
- [Person 2 name]: No match identified

PEP assessment:
- [Person 1 name]: No PEP indicators identified
- [Person 2 name]: No PEP indicators identified

Adverse media:
- [Entity/Person]: No adverse media identified / [Summary of findings]

Individual identity verification:
- [Person 1]: [Pending â€” user to verify via photo ID / Completed â€” passport verified on [date]]
```

---

## Step 5: Document and File

Generate and save the following records for the client file. These records must be
retained for **7 years** after the end of the business relationship.

### Documents to Generate

**1. Service Scoping Assessment** (from Step 1):

```markdown
# Service Scoping Assessment â€” [Client Name]
Date: [Date]
Assessed by: [Name]

## Proposed Services
- [Service 1]: [Not a designated service / Designated service â€” Item X]
- [Service 2]: [Not a designated service / Designated service â€” Item X]

## Gateway Result
[No designated services â€” standard onboarding applies]
OR
[Designated service(s) identified â€” CDD completed on [date]]

## Basis
[Brief reasoning for classification of each service]
```

**2. KYC Record** (from Step 2):

```markdown
# KYC Record â€” [Client/Entity Name]
Customer type: [Company / Trust / Partnership / Individual]
Date: [Date]
Collected by: [Name]

## Customer Identity
[Entity details as collected]

## Ownership and Control
[Structure description]

## Beneficial Owners
[Identified individuals]

## Customer Representative
[Name, role, authority basis]

## Nature and Purpose
[Description of the business relationship and services]
```

**3. Risk Rating Worksheet** (from Step 3):

```markdown
# ML/TF Risk Rating â€” [Client Name]
Date: [Date]

## Risk Factors
| Factor | Present? | Impact |
|--------|----------|--------|
| Complex ownership | Y/N | Low/Med/High |
| High-risk jurisdiction | Y/N | Low/Med/High |
| PEP involvement | Y/N | Low/Med/High |
| Adverse media | Y/N | Low/Med/High |
| Cross-border restructure | Y/N | Low/Med/High |
| Non-face-to-face | Y/N | Low/Med/High |

## Overall Rating: [LOW / MEDIUM / HIGH]
## CDD Level: [Simplified / Standard / Enhanced]
## Basis: [Narrative]
```

**4. CDD Completion Checklist** (from Step 4):

```markdown
# CDD Completion â€” [Client Name]
Date: [Date]

- [ ] Customer identity established
- [ ] Beneficial owners identified (or exemption/reasonable steps documented)
- [ ] Customer representative identified and authority confirmed
- [ ] ML/TF risk rating assigned: [LOW / MEDIUM / HIGH]
- [ ] CDD level: [Simplified / Standard / Enhanced]
- [ ] Identity verification completed â€” method: [describe]
- [ ] DFAT Consolidated List screened â€” date: [date] â€” result: [Clear / Match]
- [ ] PEP assessment completed â€” date: [date] â€” result: [Not PEP / PEP type]
- [ ] Enhanced CDD applied: [Yes â€” measures / No â€” not required]
- [ ] Senior management approval: [Yes â€” date / Not required]

## Clearance
- [ ] CDD COMPLETE â€” designated service may be provided
- [ ] CDD INCOMPLETE â€” designated service must not be provided until resolved
```

Save all documents in the client's file. If using a digital filing system, create
an `AML-CTF/` subdirectory for these records.

---

## Ongoing Obligations (After Onboarding)

Once CDD is complete, you have ongoing obligations throughout the business
relationship:

- **Monitor** for unusual transactions or behaviour that may require a suspicious
  matter report (SMR)
- **Review and update** KYC information periodically or when doubts arise about
  its accuracy
- **Re-screen** sanctions and PEP status at appropriate intervals
- **Re-assess risk** if there is a significant change in the nature or purpose
  of the business relationship

If you form a suspicion that a client is not who they claim to be, or that
providing a designated service may facilitate money laundering or terrorism
financing, you **must** submit an SMR to AUSTRAC. Do **not** tip off the client.

---

## Key References

- AUSTRAC AML/CTF Reform guidance: https://www.austrac.gov.au/amlctf-reform
- AUSTRAC professional services guidance:
  https://www.austrac.gov.au/amlctf-reform/reforms-guidance/before-you-start/new-industries-and-services-be-regulated-reform/professional-services-reform
- DFAT Consolidated List:
  https://www.dfat.gov.au/international-relations/security/sanctions/consolidated-list
- AUSTRAC Accounting Program Starter Kit: available from AUSTRAC website
- AML/CTF Act 2006 (as amended): https://www.legislation.gov.au

---

> This skill is provided free of charge by
> [Pereira Consulting](https://pereiraconsulting.com.au) as a resource for the
> Australian professional services community. For specialist international tax,
> transfer pricing, and M&A advisory, visit pereiraconsulting.com.au.
