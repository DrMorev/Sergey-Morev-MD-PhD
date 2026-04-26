## Sergey Morev - MD/PhD researcher working on clinical AI safety through personal, open-source projects.

**Current role:** Transportation & Logistics (New Brunswick, Canada)  
**Medical background:** MD/PhD + 6+ years in pharmacovigilance & drug safety  
**Scope:** Personal, non-commercial open-source research only.

### Focus
Deterministic boundaries for probabilistic models before they touch real-world workflows. I frame clinical AI monitoring as **AI Vigilance** — applying pharmacovigilance logic to runtime model behavior.

---

## Research areas (personal open-source)

### 1) Runtime verification & deterministic safety gates
- Enforcement patterns separating probabilistic generation from workflow action
- Deterministic PASS / BLOCK / ABSTAIN gates for state-changing steps
- Translating clinical cost-of-failure into explicit engineering constraints
- Evidence model: traces + constraints + audit artifacts (natural-language claims alone aren't evidence)

### 2) Qualification under pressure & behavior stability
- Reproducible crash-tests for role drift
- Stress evaluation beyond benchmark accuracy (auditable FAIL artifacts)
- Post-claim qualification: claims ≠ clearance

### 3) Architecture selection under hard constraints
- Decision protocols for LLM-only vs world-model vs hybrid approaches
- Hard tradeoffs: latency budgets, verification independence, cost-of-error
- Reasoning orchestration patterns (Plan → Execute → Verify) for lightweight/edge settings


## Selected projects

- **CASEF** Clinical AI Safety Evaluation Framework for reproducible, artifact-based qualification of LLM behavior under explicit constraints.

- **EBAC-T4**  deterministic trace-bound authorization gate for high-risk EHR writes.

- **Clinical Verifiable Gates**  medical verifier kernel using extractor contracts, UNKNOWN-by-default fields, and deterministic PASS / BLOCK / ABSTAIN adjudication.

- **LLM / World Model / Hybrid Decision Frame** — architecture decision protocol for choosing system design under risk, latency, and verification constraints.
---

## How I do my research (independent & verifiable)
- Method sanity checks: framing, assumptions, failure modes; independent cross-checking
- Engineering discipline: prototypes → documented, testable artifacts; stable interfaces; minimal reproducible examples
- Adversarial QA: stress tests for unsafe behavior, hallucinated actions, and format brittleness; definition-of-done gates

---

## Availability (non-commercial only)

Open to open-source collaboration, research discussion, peer review, and unpaid writing/speaking where appropriate.

Commercial or paid engagements are not available at this time.

srgmorev@gmail.com

**Tags:** clinical ai deployment safety · runtime verification · deterministic verification · auditable constraints · pharmacovigilance · behavior stability · adversarial testing · deployment constraints
