# FUTURE IDEAS — POST-ACCEPTANCE PARKING REGISTRY

Status: `COMPLETION_LOCK RELEASED / ALL IDEAS STILL PARKED`

`DEC-SAD-018` satisfied functional acceptance and released the old completion lock. That removes the completion prerequisite but **does not activate any idea**.

Rules:

1. Append ideas; do not silently delete them.
2. A parked idea becomes active only after an explicit human roadmap decision (or an already-authorized roadmap that unambiguously includes it) plus its stated evidence/authority conditions.
3. Each idea retains an evidence-based reactivation condition.
4. Existing `Why not now` text records the original parking rationale; functional acceptance alone does not imply the remaining reactivation conditions are satisfied.

## IDEA-SAD-001 — General multi-agent / swarm runtime — PARKED
Potential value: parallel specialization and context isolation.
Why not now: not required for first functional path; can hide missing core contracts.
Reactivate when: representative evals show a single capable agent/model+tools cannot meet a defined task class within acceptable quality/cost/latency, and the human explicitly activates the direction.

## IDEA-SAD-002 — Company Loop runtime — PARKED
Potential value: structured decision deliberation.
Why not now: decision process should not precede proof that base Saddle works.
Reactivate when: A/B evidence shows materially better human decisions than simpler decision-support, and the human explicitly activates the direction.

## IDEA-SAD-003 — Full Ginseng graph/runtime/UI — PARKED
Potential value: decision lineage and impact analysis at scale.
Why not now: semantics are valuable; full runtime/UI has no first-product proof.
Reactivate when: minimal lineage/impact records produce repeated value, file-based representation becomes a measured blocker, and the human explicitly activates the direction.

## IDEA-SAD-004 — Vector database / generalized RAG — PARKED
Potential value: large-scale semantic retrieval.
Why not now: targeted file/symbol/context retrieval was enough for the completion path.
Reactivate when: retrieval evals show repeated recall failures that cannot be fixed by simpler retrieval, and the human explicitly activates the direction.

## IDEA-SAD-005 — Browser/computer-use automation — PARKED
Potential value: operate WebAI or real apps.
Why not now: no measured browser bottleneck in the accepted completion path.
Reactivate when: a real workflow shows manual browser transfer is a dominant, repeated cost, and the human explicitly activates the direction with appropriate effect controls.

## IDEA-SAD-006 — Broad MCP marketplace / write-enabled MCP — PARKED
Potential value: plug-in interoperability.
Why not now: expands trust surface beyond the accepted bounded effect path.
Reactivate when: at least two required external integrations benefit from a common MCP adapter, permissions can remain narrowly scoped, and the human explicitly activates the direction.

## IDEA-SAD-007 — Dynamic multi-provider model routing — PARKED
Potential value: workload-specific quality/cost optimization.
Why not now: the first accepted worker path needed one selected model, not routing infrastructure.
Reactivate when: multiple stable workloads show different model winners, routing has measurable value over one default + manual override, and the human explicitly activates the direction.

## IDEA-SAD-008 — Persistent autonomous agent memory service — PARKED
Potential value: long-running continuity.
Why not now: canonical Git memory is the intentional first solution; hidden agent memory conflicts with resumability/auditability.
Reactivate when: two documented continuity failures remain after repository-state discipline and targeted retrieval, and the human explicitly activates a bounded memory design.

## IDEA-SAD-009 — Full observability platform / Langfuse-class stack — PARKED
Potential value: rich tracing/evals/analytics.
Why not now: JSON/JSONL evidence was sufficient for the accepted path.
Reactivate when: volume makes plain trace/eval artifacts materially hard to operate, and the human explicitly activates the direction.

## IDEA-SAD-010 — Agent framework as core (LangGraph / Agents SDK / similar) — PARKED
Potential value: managed loops, handoffs, persistence, tool dispatch.
Why not now: Executor/Saddle intentionally own critical state/effect semantics; adding a framework risks duplicate control planes.
Reactivate when: a concrete runtime requirement is repeatedly expensive or unreliable to implement directly, the framework passes security/eval comparison, and the human explicitly activates the direction.

## IDEA-SAD-011 — Self-hosted/open-weight model infrastructure — PARKED
Potential value: locality, privacy, predictable marginal cost.
Why not now: operational cost and no accepted-path requirement.
Reactivate when: data-governance, offline, latency, or measured TCO requirement justifies it, and the human explicitly activates the direction.

## IDEA-SAD-012 — Dashboard/control center — PARKED
Potential value: visibility for multiple concurrent agents/runs.
Why not now: visual layer did not close the functional gate.
Reactivate when: operational run volume creates a repeated decision/visibility failure not solved by generated reports, and the human explicitly activates the direction.

## IDEA-SAD-013 — Auto-merge / auto-deploy — PARKED
Potential value: speed.
Why not now: high-risk authority expansion beyond the accepted bounded effect model.
Reactivate when: lower-risk draft-PR flow is mature, rollback/evidence are proven, and the human explicitly authorizes a narrower automation class.

## IDEA-SAD-014 — Human-controlled value and reinvestment flywheel — PARKED
Potential value: let Saddle-related work finance maintenance, research and bounded experiments by creating measurable value for users, while financial/legal authority remains with humans or human-controlled entities.
Why still parked: functional acceptance is now satisfied, but financial, contractual and legal mechanisms remain a separate consequential-effect surface with no approved governance policy.
Reactivate when: at least one repeatable paid value case is evidenced, and the human explicitly approves a treasury/contract governance policy with appropriate legal/accounting review.
Dependencies: functional acceptance (SATISFIED); evidence/accounting records; explicit spending/contract authority boundary; human-controlled accounts and credentials.

## IDEA-SAD-015 — Bounded self-improvement loop — PARKED
Potential value: systematically observe recurring capability gaps, propose reversible improvements, run isolated experiments and improve task quality over time without creating a self-preservation or resource-acquisition objective.
Why still parked: functional acceptance does not authorize a second autonomous control loop; adoption of self-change still needs explicit external review/authority and measured need.
Reactivate when: repeated capability gaps are recorded, experiments can run in a bounded environment, and adoption of any self-change remains an externally reviewable state transition under unchanged human-owned objectives and permissions, with explicit human roadmap activation.
Dependencies: eval harness (SATISFIED); immutable goal/authority boundary (SATISFIED in accepted scope); sandboxed experiment contract; human or pre-authorized adoption gate; rollback/versioning.

## IDEA-SAD-016 — GUIDED CREATIVE + SESSION HARVEST + ATTACK THE FRAME — FUTURE IDEA / GOLD — PARKED
Potential value: preserve human agency and creative exploration while keeping a conversation operationally focused, preserving valuable peripheral material, and periodically challenging the frame before a promising line of thought hardens into self-confirming narrative.
Core pattern: three complementary modules form one interaction discipline. `GUIDED CREATIVE` defines how we collaborate; `SESSION HARVEST` defines what we do not allow to disappear; `ATTACK THE FRAME` defines how we defend against self-congratulation, wishful thinking, premature convergence, and an attractive but weak framing of the problem.
Session Harvest structure: `MAIN THREAD` holds the active task; `GOLD` preserves ideas, principles, analogies or formulations worth retaining beyond the current task; `SIDE TRAILS` parks interesting directions that should not interrupt the active thread; `OPEN LOOPS` records started but unresolved questions or problems.
Behavioral principle: when something potentially valuable appears outside the main thread, the AI should park it in the appropriate harvest bucket rather than immediately expanding it. The intended effect is one conversational track with peripheral awareness and explicit preservation of useful side material.
Guided Creative principle: provide enough context and tools for the human to make the next move; surface consequential errors early; avoid correcting every minor detail; expose genuine forks; separate `AI SUGGESTS` from `HUMAN DECIDES`; expand technical depth only when it is needed for the next decision.
Attack the Frame principle: after roughly three successive rounds of deepening the same subject, followed by a natural stopping point, treat the current framing as a candidate for deliberate challenge. Ask what assumptions are being protected, what evidence would falsify the direction, what simpler or opposing explanation fits the same observations, whether the problem has been framed around the preferred solution, and whether accumulated agreement reflects evidence or merely conversational momentum. `3× deepening + natural stopping point = candidate for ATTACK THE FRAME`, not an automatic interruption rule.
Why GOLD: the combined pattern may generalize beyond one conversation or prompt into a reusable interaction, knowledge-capture, and epistemic-control capability for creative, research, design and implementation workflows.
Why not now: it is currently a strong interaction hypothesis, not yet a validated Saddle capability. Premature implementation could turn useful conversational disciplines into another control layer or ritual without evidence that they improve outcomes.
Reactivate when: repeated real sessions show measurable value from all three parts of the pattern — better human decision ownership/focus from Guided Creative, materially lower loss or derailment of valuable side material from Session Harvest, and better detection of weak assumptions or premature convergence from Attack the Frame — and the human explicitly activates the direction.
Evidence to seek: representative session comparisons, examples of recovered GOLD/SIDE TRAILS/OPEN LOOPS that were later useful, evidence of reduced topic derailment, evidence that human decisions remain genuinely human-owned rather than AI-defaulted, and concrete cases where Attack the Frame changed, weakened, rejected or strengthened a working hypothesis for evidence-based reasons.

## IDEA-SAD-017 — ACTIONABLE DECISION AFTER ANALYSIS — FUTURE IDEA / GOLD — PARKED
Potential value: prevent analysis from ending as an information dump when it actually supports a decision, while avoiding the opposite failure mode of manufacturing artificial decisions where information, uncertainty reduction or further measurement is the correct output.
Core principle: do not `always propose a decision`; always check whether the analysis genuinely implies a decision. If it does, surface the single best recommended next decision or action. If it does not, end with the information, uncertainty, or measurement still required rather than forcing a recommendation.
Default decision format when a real decision exists: `ANALYSIS → RECOMMENDED DECISION → WHY → BEST NEXT STEP → ALTERNATIVE (only if a meaningful fork exists) → USER DECIDES`.
Decision ownership principle: `AI RECOMMENDS ≠ HUMAN DECIDES`. The AI may compress evidence into a recommendation and explain why it prefers one path, but the recommendation must remain visibly distinct from human authority.
Selection principle: prefer one best recommendation rather than five co-equal options. Surface alternatives only when there is a genuine, decision-relevant fork; otherwise extra options create noise and transfer the synthesis burden back to the human.
No-forced-decision guardrail: valid terminal outputs include `INFORMATION ONLY`, `MEASURE NEXT`, `UNCERTAINTY REMAINS`, or `NO DECISION YET` when the evidence does not support an actionable choice.
Why GOLD: the pattern directly addresses a common gap between analysis quality and operational usefulness: the AI should not stop at `INSIGHT` when a defensible action follows, but it also should not confuse decisiveness with inventing a decision.
Why not now: this is a strong interaction-policy hypothesis rather than a validated Saddle capability. Making it mandatory without testing could bias the system toward premature closure or overconfident recommendations.
Reactivate when: representative sessions show that the pattern increases useful follow-through and reduces analysis-without-action without increasing premature or artificial decisions, while users can still clearly distinguish recommendations from their own authority.
Evidence to seek: examples where a recommended next step improved follow-through; counterexamples where `NO DECISION YET` was the correct result; comparison of one-best-recommendation outputs against multi-option outputs; and evidence that `AI RECOMMENDS ≠ HUMAN DECIDES` remains legible in practice.
