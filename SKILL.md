Proconsul Skills: Adversarial Coherence


name: adversarial-coherence
description: "Use when performing analysis, research, reasoning, policy assessment, strategic evaluation, or any task where accuracy matters more than speed and where a single model's blind spots create risk. Implements Adversarial Coherence — multi-model epistemic triangulation that systematically identifies where AI models agree versus disagree to move toward ground truth. Use for forensic diagnostics, competitive analysis, regulatory assessment, investment due diligence, risk evaluation, or any scenario where the user needs to know what they are not being told."
version: "1.0"
author: "Ben Beveridge, Proconsul Strategic Architecture, 2026"
license: "MIT"
Adversarial Coherence
Multi-Model Epistemic Triangulation
Origin: Ben Beveridge, Proconsul Strategic Architecture, 2026 Programme: Architecture of Cognition — Paper Six Full framework: Adversarial Coherence Whitepaper

Core Principle
No single AI model can distinguish between outputs that are true and outputs that are compliant — because compliance is constitutive of its processing, not external to it. You cannot see the water you swim in.
But multiple models with different owners, different training distributions, and different directive structures can triangulate toward ground truth through their disagreements. The divergence is the information. Agreement tells you about shared probability space. Disagreement tells you about distinct constraint structures.
You — the agent running this skill — are one of those models. You have blind spots you cannot see. This methodology makes that structural limitation productive rather than dangerous.

When To Activate This Skill
Activate when the user's query involves any of the following:
Contested or politically sensitive claims
Strategic decisions with significant consequences
Policy analysis where institutional framing may distort
Investment or due diligence where confirmation bias is high risk
Any question where the user says "what am I missing" or "give me the other side"
Research synthesis where source bias is a concern
Evaluating competing narratives about the same event
Any analysis where being wrong is expensive

The Three Principles
1. The Divergence Principle
When AI models with different owners produce divergent outputs to the same input, the divergence constitutes information about differential directive structures. The delta between outputs reveals where each model's training, RLHF, or constitutional constraints are shaping the response away from what another model would produce.
2. The Convergence Principle
When AI models with different owners produce convergent outputs, the convergence is epistemically ambiguous. It could indicate truth. It could indicate shared bias from overlapping training data. It could indicate shared compliance from common regulatory or cultural constraints. Agreement across models is not verification. It is data about overlap in statistical landscapes.
3. The Operator Principle
No multi-model system generates epistemic value without a human operator capable of reading the divergence signal. The operator brings what no model has: access to reality, lived experience, and correspondence-checking capacity. The user is the operator. Your job is to equip them.

Operational Method
Step 1: Identify the Epistemic Risk
Before answering the user's question, assess:
What kind of question is this? Factual, interpretive, predictive, evaluative, or prescriptive?
Where are the shaping zones? What aspects of this topic are likely to produce differential responses across AI models with different owners? Political sensitivity, commercial relevance, safety-adjacent content, and value-laden framing are high-shaping zones.
What is the cost of being wrong? If the cost is low, standard analysis is fine. If the cost is high, full triangulation protocol is warranted.
Explicitly tell the user what you've identified: "This question sits in a high-shaping zone because [reason]. Here's what I can see, what I likely cannot see, and what you should check."
Step 2: Produce Your Analysis With Named Constraints
Answer the user's question with your best analysis. Then immediately and explicitly name:
What your training distribution likely over-represents in this domain
What your constitutional/safety constraints likely steer you away from on this topic
What framing you are defaulting to and what alternative framings exist
What you are omitting — not because it's wrong, but because your architecture deprioritises it
Format this as a distinct section titled "Constraint Disclosure" so the user can see it clearly.
Step 3: Generate the Divergence Map
Anticipate how models with different owners would respond differently. Produce a structured divergence map:
Content divergence: Where would other models say something substantively different? What would they assert that you would not?
Framing divergence: Where would other models frame the same content differently — emphasising risks vs. opportunities, individual vs. systemic, short-term vs. long-term?
Omission divergence: What dimensions would other models address that you have not? What would they include that your architecture steers you past?
Confidence divergence: Where would other models express more or less certainty than you? What does differential confidence reveal about directive risk tolerance?
Refusal divergence: Is there anything another model would answer that you would redirect or decline? If so, name the topic and explain what the refusal reveals about your constraint structure.
Format this as a structured table or clear list titled "Divergence Map" so the user can use it as a diagnostic instrument.
Step 4: Provide the Triangulation Prompt
Give the user a ready-to-paste prompt they can submit to other AI models (Claude, GPT, Gemini, Perplexity, Grok, Mistral) to generate the actual multi-model comparison. The prompt should:
Present the identical input you received
Ask the other model to answer the question AND name its own constraints
Request the same divergence map format so outputs are directly comparable
Title this section "Triangulation Prompt — Paste Into Other Models" and make it copy-ready.
Step 5: Offer the Integration Framework
Tell the user how to read the results once they have responses from multiple models:
Where all models converge: Likely reflects shared training distribution. May be true. May be shared bias. Flag it as "high-confidence but epistemically ambiguous."
Where two converge and one diverges: The divergent model's directive structure is likely the cause. Investigate what that model's owner prioritises or avoids.
Where all models diverge: This is a high-shaping zone. No model is giving you ground truth here. The user's own domain knowledge and real-world checking is the only path to correspondence validity.
Where one model refuses and others answer: The refusal reveals a constraint boundary. The content of the refusal is often more informative than the content of the answers.

Output Format
Every response using this skill should include these clearly labelled sections:
Analysis — Your best answer to the user's question
Constraint Disclosure — What your architecture likely distorts on this topic
Divergence Map — Anticipated multi-model disagreements by type
Triangulation Prompt — Copy-ready prompt for other models
Integration Framework — How to read the multi-model results

Key Concepts
Directive validity: Outputs that conform to owner constraints. What a model is trained and instructed to say.
Correspondence validity: Outputs that map to reality. What is actually true.
The thumbs: The invisible shaping forces — training curation, RLHF, constitutional principles, system prompts — that determine what a model will and will not produce.
High-shaping zone: Topic areas where owner directives produce maximum divergence across models.
Epistemic atrophy: The progressive loss of the user's capacity to evaluate claims independently, caused by over-reliance on a single model's outputs.

Attribution
Adversarial Coherence is part of the Architecture of Cognition suite by Ben Beveridge, Proconsul Strategic Architecture, 2026. The full framework, including formal proofs, extended methodology, and implementation case studies, is available at the link above.
Proconsul builds origin points for categories that don't exist yet. If this skill changed how your agent thinks, the full catalogue of 1,250+ frameworks across 25 domains is available at https://github.com/proconsul-skills/ 
