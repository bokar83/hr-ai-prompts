# HR AI prompts

Ten short, copy-paste prompts for HR AI work. Each one works on its own in any AI tool. Replace the [BRACKETED] part with your own text.

Every prompt asks the AI to say UNKNOWN instead of guessing, to draft only, and to use roles instead of names. Use hypothetical or redacted text.

## 1. Score an HR task as an AI candidate

Score this HR task as an AI candidate. Give 0 to 2 on each: volume, checkable output, low harm if wrong, easy human review, data can be protected, meaningful time saved. Flag any hiring, pay, promotion or discipline use as a risk gate. Total out of 12, name three unknowns, and suggest the smallest safe first test. Task: [DESCRIBE THE TASK]

Related skill (optional): ai-use-case-intake in the hr-ai-skills repository. This prompt does not need it.

## 2. Review a planned AI use for risk

Review this planned AI use for fairness and bias, personal data, transparency, human oversight, accuracy, employee consultation and record keeping. Rate each LOW, MEDIUM, HIGH or UNKNOWN with a reason. Label every legal point: check current law and counsel, not legal advice. Do not cite any statute or article number. Use: [DESCRIBE THE USE AND THE REGIONS]

Related skill (optional): hr-ai-risk-review in the hr-ai-skills repository. This prompt does not need it.

## 3. Redact text before using AI

Redact this text before I use it with an AI tool. Replace names with roles, remove ids and contact details, generalize exact dates, salaries and rare titles, and mark special categories for removal. Return the redacted text, a table of changes, and a residual risk rating. Text: [PASTE TEXT]

Related skill (optional): pii-redaction-before-ai in the hr-ai-skills repository. This prompt does not need it.

## 4. Verify an AI draft claim by claim

Check this AI draft claim by claim. For each claim mark VERIFIED (quote my source), UNVERIFIED (no source) or WRONG (conflicts with source). Redo all arithmetic. Mark legal points unverified. Draft: [PASTE DRAFT]. Source: [PASTE SOURCE TEXT]

Related skill (optional): ai-output-verifier in the hr-ai-skills repository. This prompt does not need it.

## 5. Estimate value conservatively

Build a conservative low, middle and high estimate of value for this AI use. List every assumption and its source. Include review and correction time. Separate hours saved from money saved. Show which assumption matters most. Say what is not counted. Inputs: [TASKS PER MONTH, MINUTES TODAY, MINUTES WITH AI, COSTS]

Related skill (optional): roi-estimate in the hr-ai-skills repository. This prompt does not need it.

## 6. Stress-test a plan

Stress-test this plan with five voices: skeptic, affected person, operator, risk owner, outsider. List what must be true and mark each TRUE, FALSE or UNKNOWN. Then assume it failed in twelve months and list the five likeliest reasons with early warning signs. End with a verdict and the cheapest next check. Plan: [PASTE PLAN]

Related skill (optional): pressure-test in the hr-ai-skills repository. This prompt does not need it.

## 7. Run an expert panel on a decision

Run a panel on this decision with seven role seats: skeptical chief HR officer, employee-relations voice, privacy and legal voice, frontline manager, security voice, finance lead, change lead. Add an always-on Contrarian who argues the opposite. Each seat names one concrete failure and one thing it needs to see. A non-voting closer gives a verdict (go, go-with-changes, stop), the top three changes, what would change the verdict, and unknowns. Label legal points: check current law and counsel. Decision: [DESCRIBE DECISION]

Related skill (optional): hr-ai-council in the hr-ai-skills repository. This prompt does not need it.

## 8. Draft a message to employees

Draft a short message to employees about this change. Say what changes, what stays, what to do and by when, where to ask questions, and what is not decided. Add five FAQ items and manager talking points. Keep language simple for translation and flag terms that may not translate. Change: [DESCRIBE CHANGE]

Related skill (optional): employee-comms-draft in the hr-ai-skills repository. This prompt does not need it.

## 9. Answer a policy question from policy text

Answer this employee question using only the policy text below. Quote the passage and name its section. Say what the text does not cover. If the text does not answer it, say so and name who to escalate to. Question: [QUESTION]. Policy text: [PASTE POLICY]

Related skill (optional): hr-policy-qa-draft in the hr-ai-skills repository. This prompt does not need it.

## 10. Turn a long update into a leader brief

Turn this into a brief for a leader: headline of eight words or fewer, why it matters now, the decision needed by whom and when, up to three evidence bullets with sources, the biggest risk, and what is not known yet. Keep it under 150 words. Do not change any number. Source: [PASTE SOURCE]

Related skill (optional): executive-brief in the hr-ai-skills repository. This prompt does not need it.
