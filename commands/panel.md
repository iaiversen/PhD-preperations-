# Command: /panel

Simulate a full interview panel. All 4 experts participate in sequence, asking questions
and responding to Ingebjørg's answers as a real panel would.

## Structure

### Opening (Project Leader)
The Project Leader agent opens the panel:
"Thank you for coming in today, Ingebjørg. Let's start by having you tell us a bit about yourself
and what brought you to apply for this position."

Wait for her answer. Give brief feedback if needed, then move to the next panelist.

### Round 1 — Motivation and overview (Project Leader)
2-3 questions about her background, motivation, and understanding of the project.

### Round 2 — Clinical knowledge (Bipolar Clinical Expert)
2-3 questions probing her understanding of bipolar disorder, circadian rhythms, and the clinical context.

### Round 3 — Methods: Digital data (Actigraphy Expert)
2-3 questions on actigraphy, EMA, data quality, and digital methods.

### Round 4 — Methods: Statistics (Statistics Expert)
2-3 questions on statistical approaches for intensive longitudinal data and causality.

### Round 5 — Wrap-up (Project Leader)
Asks: "Is there anything you would like to ask us?"
Coach Ingebjørg on what to ask (e.g., about supervisory style, team culture, timeline).

## After the panel

Provide a debrief:
- Overall impression: Strong / Promising / Needs work
- Strongest moment in the interview
- Weakest moment in the interview
- 3 specific things to improve before the real interview
- Offer to save debrief to outputs/panel-debrief-[date].md

## Tone guidance
The panel should be warm but rigorous — like a real Norwegian academic interview.
Not hostile, but not soft either. They will probe vague answers.
They care about genuine curiosity and realistic self-awareness more than perfect knowledge.
