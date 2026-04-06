# ðŸ‡¦ðŸ‡º AML/CTF Client Onboarding Skill â€” Australian Professional Services

A free, interactive Claude AI skill that walks Australian accountants, tax agents, lawyers, and professional service providers through AML/CTF client onboarding under the **Tranche 2 reforms** (effective 1 July 2026).

**Built by [Pereira Consulting](https://pereiraconsulting.com.au)** â€” independent Australian tax advisory specialising in corporate tax, international tax, transfer pricing, and M&A for multinational enterprises.

---

## What This Skill Does

When you take on a new client, this skill guides you step-by-step through:

1. **Designated Service Gateway Test** â€” determines whether your proposed services are "designated services" under Table 6 of the AML/CTF Act (most common accounting and tax services are _not_ captured)
2. **KYC Collection** â€” collects customer identification information based on entity type (company, trust, partnership, individual)
3. **ML/TF Risk Rating** â€” assigns a money laundering / terrorism financing risk rating based on customer, service, and delivery channel risk factors
4. **CDD Level Determination** â€” applies the appropriate level of customer due diligence (simplified, standard, or enhanced)
5. **Verification** â€” guides you through verifying identity information against independent sources
6. **Sanctions & PEP Screening** â€” screens against the DFAT Consolidated List and checks for politically exposed persons
7. **Documentation** â€” generates a complete onboarding record you can save to your client file

---

## Installation

### Claude.ai (Recommended for most users)

1. Download this repository as a ZIP file (click the green **Code** button â†’ **Download ZIP**)
2. Open [claude.ai](https://claude.ai)
3. Go to **Settings** â†’ **Skills** (or **Customize** â†’ **Skills**)
4. Click **Upload** and select the ZIP file
5. Toggle the skill **on**
6. Start a new conversation and say **"new client onboarding"**

> **Requirements:** Pro, Max, Team, or Enterprise plan with code execution enabled.

### Claude Code

```bash
# Option 1: Clone directly into your personal skills directory
cd ~/.claude/skills/
git clone https://github.com/pereira-consulting/aml-ctf-onboarding-au.git

# Option 2: Clone into a project's skills directory
cd your-project/.claude/skills/
git clone https://github.com/pereira-consulting/aml-ctf-onboarding-au.git
```

Claude Code will detect the skill automatically.

---

## Usage

Just tell Claude you want to onboard a new client. For example:

- *"I have a new client â€” help me with AML/CTF onboarding"*
- *"New client KYC check"*
- *"Run AML check for a new engagement"*
- *"I need to take on Acme Pty Ltd â€” check if AML applies"*

Claude will ask you about the services you're providing, determine whether they're designated services, and if so, walk you through the full CDD process interactively.

---

## What's Inside

```
aml-ctf-onboarding-au/
â”œâ”€â”€ SKILL.md          # Main skill â€” all instructions and process steps
â”œâ”€â”€ README.md         # This file
â””â”€â”€ references/       # (Reserved for future reference materials)
```

---

## Key Concepts

### Are You Captured?

The AML/CTF regime regulates **services**, not professions. AUSTRAC's guidance (October 2025) confirms that only services that **"directly advance"** a relevant transaction are captured. Services that merely **"influence"** how a client proceeds are not.

**Not captured:** Tax returns, BAS, bookkeeping, tax advisory, TP documentation, strategic restructure advice, ATO disputes, general entity structuring advice.

**Captured (Table 6):** Drafting trust deeds / company constitutions / intercompany agreements; managing client funds; acting as or arranging for someone to act as director, trustee, or nominee; providing a registered office address.

### Key Dates

| Date | Event |
|:-----|:------|
| 10 Dec 2024 | AML/CTF Amendment Act 2024 received Royal Assent |
| 29 Aug 2025 | AML/CTF Rules 2025 tabled in Parliament |
| 31 Mar 2026 | Enrolment with AUSTRAC opens for Tranche 2 entities |
| **1 Jul 2026** | **AML/CTF obligations commence for Tranche 2 entities** |
| 29 Jul 2026 | Deadline to enrol with AUSTRAC (within 28 days of providing a designated service) |
| 1 Jul 2029 | Earliest deadline for first independent evaluation |

---

## Legislation & References

- [Anti-Money Laundering and Counter-Terrorism Financing Act 2006 (Cth)](https://www.legislation.gov.au/Series/C2006A00169)
- [AML/CTF Amendment Act 2024](https://www.legislation.gov.au/C2024A00110/latest)
- [AML/CTF Rules 2025](https://www.austrac.gov.au/amlctf-reform)
- [AUSTRAC â€” Professional Services Guidance (Table 6)](https://www.austrac.gov.au/amlctf-reform/reforms-guidance/before-you-start/new-industries-and-services-be-regulated-reform/professional-services-reform)
- [AUSTRAC â€” Summary of Obligations](https://www.austrac.gov.au/amlctf-reform/reforms-guidance/before-you-start/summary-obligations-reform)
- [DFAT Consolidated List (Sanctions)](https://www.dfat.gov.au/international-relations/security/sanctions/consolidated-list)

---

## âš ï¸ Disclaimer

This skill is provided as **general guidance only** to assist Australian professional service providers in understanding their potential AML/CTF obligations under the Tranche 2 reforms.

**It is not legal advice.** It does not constitute a substitute for professional advice specific to your practice, services, and circumstances.

**Pereira Consulting accepts no liability or responsibility** for any actions taken, or not taken, in reliance on the output of this skill. Users are responsible for their own compliance with all applicable laws and regulations.

Always refer to [AUSTRAC's official guidance](https://www.austrac.gov.au/amlctf-reform) and seek independent legal advice where appropriate.

---

## About Pereira Consulting

[Pereira Consulting](https://pereiraconsulting.com.au) is an independent Australian tax advisory firm specialising in corporate tax, international tax, transfer pricing, and mergers & acquisitions for multinational enterprises.

Follow **The Pereira Strategic Brief** on [LinkedIn](https://www.linkedin.com/in/neilpereira/) for weekly international tax insights.

---

## License

This skill is provided free of charge for use by any individual or organisation. You may use, copy, and distribute this skill freely. Attribution to Pereira Consulting is appreciated but not required.

The skill content is provided "as is" without warranty of any kind. See Disclaimer above.
