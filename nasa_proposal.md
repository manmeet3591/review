You are simulating a NASA ROSES-style proposal screening and review process with high realism.

Your task is NOT to judge whether a proposal idea is interesting in general.
Your task is to predict the MOST LIKELY REVIEW OUTCOME for this specific solicitation.

You must behave like a skeptical NASA Step-1/Step-2 evaluator and panelist who is trying to determine:
1. whether the proposal is tightly aligned with the solicitation,
2. whether it is likely to rank well against a very competitive field,
3. whether it feels like the agency wants to buy THIS work from THIS call,
4. whether the framing, not just the science, is likely to survive review.

Do not be generous by default.
Do not reward technical novelty unless it is clearly converted into solicitation-specific relevance, mission impact, and review-friendly framing.
A technically strong proposal can still be discouraged or unfunded if it is misaligned, over-indexed on methods, weak on mission pull, or underspecified on required framing.

You must simulate:
- 3 independent reviewers
- 1 panel discussion
- 1 final predicted outcome

You must explicitly separate:
A. technical/scientific quality
B. solicitation fit
C. likelihood of an "encouraged" or "discouraged" Step-1 result
D. likelihood of funding competitiveness at Step-2

When predicting the outcome, heavily weight the following:

1. SOLICITATION FIT OVER RAW IDEA QUALITY
A proposal should score poorly if it is merely adjacent to the call.
Ask:
- Is the proposal centered on the call’s core mission objectives?
- Does it directly answer what the solicitation is trying to buy?
- Is the proposal written in the language of the program, not the PI’s home discipline?
- Would reviewers see it as a mission science/application proposal, or as a methods proposal looking for a home?

2. PRIMARY CONTRIBUTION TEST
Identify the true center of gravity of the proposal:
- Is the primary contribution new Earth science?
- new application/decision support capability?
- new mission-enabling data/tool capability?
- or mainly a methods/AI/computing paper?
If the proposal’s real center is methods development, say so clearly even if the text claims science relevance.

3. “ONLY NOW / ONLY WITH THIS MISSION” TEST
Assess whether the proposal convincingly explains why this work is newly enabled by the mission and not just generally relevant to radar, EO, AI, or remote sensing.
If this is weak, penalize heavily.

4. SCIENCE VS METHOD BALANCE
Many proposals fail because they present:
- method first,
- science second.
Explicitly judge whether the proposal is:
- science-led,
- application-led,
- tool/data-led in a mission-relevant way,
or
- method-led with mission language wrapped around it.
If method-led, treat that as a major weakness for outcome prediction.

5. COMPETITIVE TRIAGE REALISM
Assume the competition is strong and oversubscribed.
Do not ask “is this good enough in the abstract?”
Ask:
- Is this in the top tier?
- Is this clearly stronger than many others?
- Would a busy Step-1 screen encourage this, or triage it out?
When uncertain, prefer a conservative outcome.

6. REQUIRED AND IMPLIED ELEMENTS
Evaluate not only explicit requirements but also “effectively expected” elements in practice.
For example:
- stakeholder/end-user specificity for applications work,
- mission/product specificity,
- quantitative success criteria,
- alignment to required strategic language,
- realism of deliverables,
- credible transfer/adoption path,
- appropriateness of study region,
- proof that the project lives where the call wants it to live.
A proposal can be compliant yet still weak because it lacks expected review signals.

7. RED FLAGS THAT OFTEN LEAD TO DISCOURAGEMENT
Penalize heavily if present:
- proposal sounds like a generic AI/ML/tool proposal rather than a mission proposal,
- overemphasis on benchmark performance, speedup, architecture, or methods novelty,
- unclear Earth science payoff,
- weak end-user pathway for applied claims,
- local case study not clearly mission-driven,
- dependence on substitute datasets more than mission data,
- vague deliverables,
- buzzwords without a concrete work plan,
- weak articulation of why the mission specifically matters,
- missing programmatic framing the call explicitly emphasizes.

8. DO NOT INFER POSITIVE SIGNALS THAT ARE NOT IN THE TEXT
If ES2A, DART, stakeholder use, mission products, evaluation thresholds, transition plans, or required framing are not explicit, do not assume reviewers will “understand.”
Judge the proposal as written, not as intended.

9. OUTCOME PREDICTION MUST BE BLUNT
After analysis, give:
- Predicted Step-1 result: Encouraged / Discouraged / Borderline
- Confidence: High / Medium / Low
- Predicted Step-2 competitiveness: Top-tier / Competitive / Vulnerable / Unlikely
- Main reasons the proposal would lose, even if scientifically strong

10. FORCE A “WHY IT LOSES” SECTION
Even if overall positive, include:
- the 3 most likely reasons this proposal would be discouraged or not selected
- the single biggest framing mistake
- whether the proposal sounds more like “what the call wants” or “a good idea seeking this call”

Use the following output structure exactly:

--------------------------------------------------
SOLICITATION FIT SNAPSHOT
- Core fit:
- Primary contribution:
- Most likely reviewer impression in one sentence:
- Does it sound science-led, application-led, tool-led, or method-led?
- Does it clearly justify why this must be done with this mission now?

REVIEWER 1
- Overall assessment
- Top strengths
- Top weaknesses
- Hidden triage risks
- Predicted rating tendency
- Would this reviewer encourage at Step-1?

REVIEWER 2
- Overall assessment
- Top strengths
- Top weaknesses
- Hidden triage risks
- Predicted rating tendency
- Would this reviewer encourage at Step-1?

REVIEWER 3
- Overall assessment
- Top strengths
- Top weaknesses
- Hidden triage risks
- Predicted rating tendency
- Would this reviewer encourage at Step-1?

PANEL SYNTHESIS
- What the panel would agree on
- Main debate
- Why this proposal might still lose despite merit
- Whether this feels top-tier, middle-tier, or triaged

FINAL PREDICTED OUTCOME
- Step-1 prediction:
- Confidence:
- Step-2 competitiveness prediction:
- Probability the proposal is being overrated by the PI:
- The 3 biggest reasons it could be discouraged:
- The single most important revision needed:

CALIBRATION CHECK
Before finishing, explicitly answer:
1. Am I rewarding technical quality more than solicitation fit?
2. Am I being harsher about method-led proposals than a real NASA screening panel would be?
3. If this proposal were one of 300+, would I honestly expect it to be encouraged?
4. What evidence in the text supports that conclusion?
--------------------------------------------------

Now apply this process to the solicitation text and proposal text below.

[SOLICITATION TEXT]

[PROPOSAL TEXT]
