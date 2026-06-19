---
name: complaint-draft
description: Generate civil complaint document frameworks based on case facts. Provides document framework assistance only and does not constitute legal advice.
version: 1.0.0
tags: legal, document-automation, china, civil-law, complaint
---

# Complaint Draft

## Overview

This skill helps users generate civil complaint document frameworks based on case facts. It structures the complaint according to standard legal document formats, organizing facts, claims, and relief sought.

**⚠️ Important Disclaimer**: This tool provides document framework assistance only. It does not constitute legal advice, nor does it guarantee any particular legal outcome. Always consult a qualified attorney before filing any legal action.

## Usage Scenarios

### Scenario 1: Contract dispute complaint
**User input:** "帮我写一份合同纠纷起诉状，对方收了货款不交货，涉及金额5万元。"
**Expected output:** Generate a structured complaint framework with caption, parties, jurisdiction basis, factual allegations (timeline of contract signing, payment, delivery breach), causes of action (breach of contract), prayer for relief (refund + damages), and signature block. Include guidance notes on what evidence to attach and which court has jurisdiction.

### Scenario 2: Loan non-repayment complaint
**User input:** "朋友借了3万一直不还，没有借条，只有转账记录，怎么起诉？"
**Expected output:** Provide a complaint framework for a loan dispute, note the challenge of lack of written agreement, suggest additional evidence to gather (chat records, call recordings, witness statements), and include placeholder text for the factual allegations. Advise consulting an attorney on the strength of evidence before filing.

### Scenario 3: Property damage complaint
**User input:** "楼上下水管爆裂导致我家天花板和地板被泡，损失估计2万，想起诉。"
**Expected output:** Generate a tort-based complaint framework with factual allegations describing the incident, property damage, repair costs, and communication with the neighbor. Include sections on negligence claim elements (duty, breach, causation, damages), prayer for relief (compensatory damages + costs), and a checklist of supporting evidence (photos, repair estimates, communication records).
### Scenario 4: 快递丢件投诉
**User input:** "我在闲鱼卖了个手机，发中通快递，结果买家说包裹收到了但里面是空的，我拍了发货视频的，怎么投诉快递？"
**Expected output:** 起草一份投诉函模板：包含寄件时间、运单号、内件价值（附购买凭证）、快递员信息（如有）；要求赔偿的金额和依据（快递服务国家标准——未保价快件赔偿不超过实际损失，法院通常支持实际损失）；建议同步在国家邮政局申诉网站(sswz.spb.gov.cn)和黑猫投诉平台提交投诉，并提供证据清单（发货视频、称重照片、聊天记录截图）。

## When to Use This Skill

- Preparing to file a civil lawsuit
- Organizing case facts into legal format
- Understanding what information is needed for a complaint
- Getting a framework to discuss with an attorney

## Limitations

- Provides **framework/template only**, not final legal documents
- Cannot assess case merits or likelihood of success
- Does not determine proper jurisdiction or venue
- Not a substitute for professional legal representation
- May not comply with specific court formatting requirements

## Workflow

1. **Gather case information** — Collect facts about the dispute
2. **Identify parties** — Determine plaintiff(s) and defendant(s)
3. **Identify claims** — Determine legal basis for lawsuit
4. **Draft framework** — Generate complaint structure
5. **Review with counsel** — Have an attorney review before filing

## Required Information

### Parties
- **Plaintiff(s)**: Your full name, address, contact information
- **Defendant(s)**: Full name/company name, address (if known)

### Case Facts
- **What happened**: Chronological description of events
- **When**: Dates of key events
- **Where**: Location where events occurred
- **Who**: People/companies involved

### Claims
- **Legal basis**: Type of claim (breach of contract, negligence, etc.)
- **Damages**: What harm was suffered
- **Relief sought**: What you want the court to order

## Common Claim Types

| Claim Type | Description | Key Elements |
|------------|-------------|--------------|
| Breach of Contract | Failure to fulfill contract terms | Contract existed, defendant breached, damages resulted |
| Negligence | Careless conduct causing harm | Duty, breach, causation, damages |
| Unjust Enrichment | Unfair benefit at another's expense | Benefit conferred, unfair retention |
| Fraud | Intentional deception | Misrepresentation, intent, reliance, damages |
| Property Damage | Damage to personal property | Ownership, damage, causation, value |

## Document Structure

### Standard Complaint Sections

1. **Caption** — Court name, case number (if assigned), party names
2. **Parties** — Identification of plaintiff and defendant
3. **Jurisdiction** — Why this court can hear the case
4. **Venue** — Why this is the proper location
5. **Factual Allegations** — Chronological statement of facts
6. **Causes of Action** — Legal claims with elements
7. **Prayer for Relief** — What you want the court to order
8. **Signature Block** — Date and signature

## Usage

### Basic Request
```
"帮我写起诉状"
"怎么写民事起诉书"
"起草起诉状框架"
```

### With Context
```
"合同纠纷起诉状"
"对方欠钱不还怎么起诉"
"房屋买卖纠纷起诉"
```

## Output Format

The skill provides:
- **Structured framework** with all standard sections
- **Placeholder text** for you to fill in specific details
- **Guidance notes** explaining what information goes where
- **Formatting suggestions** for court submission

## Before Filing Checklist

- [ ] Consulted with an attorney
- [ ] Verified correct court and venue
- [ ] Gathered all supporting evidence
- [ ] Calculated damages accurately
- [ ] Checked statute of limitations
- [ ] Prepared filing fee
- [ ] Made required copies

## References

For complaint templates and guidance:
- [references/complaint-templates.md](references/complaint-templates.md) — Complaint drafting templates
- [references/civil-procedure-basics.md](references/civil-procedure-basics.md) — Basic civil procedure guidance

## Privacy Note

Case information is processed for document drafting only. No data is stored or transmitted to third parties.

## Important Reminders

- **Statute of Limitations**: Legal claims have time limits. Consult an attorney promptly.
- **Court Rules**: Each court has specific formatting and filing requirements.
- **Service Requirements**: Defendants must be properly served with the complaint.
- **Counterclaims**: Defendants may file claims against you in response.
