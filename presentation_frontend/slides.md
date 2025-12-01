---
# Global deck settings
theme: default
title: Agentic AI — Slides 1–7
info: |
  Seven-slide deck highlighting Agentic AI strategy, workflows, risk-native agents, capability stack, and roadmap.
class: text-left
mdc: true
transition: slide-left
fonts:
  sans: Inter, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial
  mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace
css: |
  @import "./style.css";
---

<!-- SLIDE 1 -->
<h1 class="brand-header">Beyond Automation: Agentic AI as Autonomous Decision-Making</h1>

<div class="card-grid two mt-1" role="group" aria-label="Positioning and comparison">
  <div class="card" aria-labelledby="positioning-title">
    <div id="positioning-title" class="eyebrow">Positioning</div>
    <ul class="points-clean" role="list">
      <li>Shift from process execution to outcome orchestration.</li>
      <li>Agents as autonomous collaborators across systems and data.</li>
      <li>Predictive compliance, not reactive remediation.</li>
      <li>Scalable expertise that compounds over time.</li>
    </ul>
  </div>

  <div class="card" aria-labelledby="benefits-title">
    <div id="benefits-title" class="eyebrow">Benefits</div>
    <ul class="points-clean" role="list">
      <li><span class="benefit">Higher accuracy</span> with real-time, context-aware decisions.</li>
      <li><span class="benefit">Faster cycle times</span> and reduced exception handling.</li>
      <li><span class="benefit">Embedded governance</span> with explainability out-of-the-box.</li>
      <li><span class="benefit">Scalable orchestration</span> across functions and data sources.</li>
    </ul>
  </div>
</div>

<div class="comparison" role="table" aria-label="RPA vs Agentic AI comparison">
  <div class="col" role="rowgroup" aria-label="RPA">
    <h3 aria-label="RPA">RPA (Rules-Based)</h3>
    <ul class="points-clean" role="list">
      <li>Orientation: follows scripts; non-autonomous</li>
      <li>Decisioning: if–then, deterministic</li>
      <li>Data: structured forms; limited variance handling</li>
      <li>Error handling: brittle; manual exceptions</li>
      <li>Governance: after-the-fact checks; logs</li>
      <li>Scaling: task-by-task; costly maintenance</li>
    </ul>
  </div>
  <div class="col" role="rowgroup" aria-label="Agentic AI">
    <h3 aria-label="Agentic AI">Agentic AI (Goal-Driven)</h3>
    <div class="badge benefit" aria-label="benefit badge">Outcome-Oriented</div>
    <ul class="points-clean" role="list">
      <li>Orientation: goal-driven; dynamic planning</li>
      <li>Decisioning: learned policy + tool-use</li>
      <li>Data: multi-source, unstructured, real-time</li>
      <li>Error handling: self-healing; adaptive retries</li>
      <li>Governance: explainable; embedded controls</li>
      <li>Scaling: end-to-end orchestration across systems</li>
    </ul>
  </div>
</div>

<div class="evolution-strip" aria-label="Evolution from RPA to Agentic AI">
  <div class="panel rpa" aria-label="RPA motif">
    <div aria-hidden="true" style="font-size: 20px">⚙️🧰</div>
    <div class="muted small">Mechanical, scripted execution</div>
  </div>
  <div class="arrow" aria-hidden="true">
    <div class="chevron">➜</div>
  </div>
  <div class="panel agentic" aria-label="Agentic AI motif">
    <div aria-hidden="true" style="font-size: 20px">🤖✨</div>
    <div class="muted small">Autonomous, context-aware decisioning</div>
  </div>
</div>

---

<!-- SLIDE 2 -->
<h1 class="brand-header">The Agentic AI Wave: Industry Transformation &amp; GenPact's Position</h1>

<div class="card-grid two mt-1" role="group" aria-label="Market and opportunity">
  <div class="feature-card" aria-labelledby="market-reality">
    <div id="market-reality" class="eyebrow">Market Reality</div>
    <ul class="points-clean" role="list">
      <li>Finance &amp; Accounting — <span class="accent-orange">65%</span> tasks ripe for agentic handoff</li>
      <li>Audit — <span class="accent-orange">55%</span> automation-ready with embedded controls</li>
      <li>Compliance — <span class="accent-orange">60%</span> continuous monitoring potential</li>
      <li>Procurement — <span class="accent-orange">45%</span> manual triage → agentic workflows</li>
    </ul>
    <div class="section-divider"></div>
    <div class="muted"><strong class="accent-green">Agents</strong>: <span class="accent-green">10 → 300+</span> over 12–24 months</div>
  </div>

  <div class="feature-card" aria-labelledby="genpact-opportunity">
    <div id="genpact-opportunity" class="eyebrow">GenPact's Opportunity</div>
    <ul class="points-clean" role="list">
      <li>Domain-led orchestration: finance, audit, compliance, procurement</li>
      <li>Agentization of legacy processes via API and workflow wrappers</li>
      <li>Outcome SLAs: cycle time, accuracy, cost-to-serve</li>
      <li>Progressive deployment patterns across functions</li>
    </ul>
    <div class="section-divider"></div>
    <div class="muted small">
      <strong>Key Stats</strong> • SOX cost ↓ <span class="accent-orange">30–50%</span> • Audit cycle ↓ <span class="accent-orange">35–60%</span>
    </div>
  </div>
</div>

<div class="card mt-1" aria-label="Waterfall of manual effort decline">
  <div class="eyebrow">Manual Effort Decline — Waterfall</div>
  <div class="waterfall" role="img" aria-label="Declining manual effort across functions">
    <div class="bar" aria-label="Finance 90%">
      <div class="bar-inner" style="height: 90%"></div>
      <label>Finance</label>
    </div>
    <div class="bar" aria-label="Audit 70%">
      <div class="bar-inner" style="height: 70%"></div>
      <label>Audit</label>
    </div>
    <div class="bar" aria-label="Compliance 55%">
      <div class="bar-inner" style="height: 55%"></div>
      <label>Compliance</label>
    </div>
    <div class="bar" aria-label="Procurement 40%">
      <div class="bar-inner" style="height: 40%"></div>
      <label>Procurement</label>
    </div>
  </div>
</div>

<div class="timeline horiz mt-1" aria-label="Mini timeline 2024 to 2026">
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">2024</div>
      <strong>Establish 10–20 agents</strong><br>
      <span class="muted">Foundational pilots</span>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">2025</div>
      <strong>Scale to 100–200</strong><br>
      <span class="muted">Multi-function rollout</span>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">2026+</div>
      <strong>300+</strong><br>
      <span class="muted">Enterprise-wide agent mesh</span>
    </div>
  </div>
</div>

---

<!-- SLIDE 3 -->
<h1 class="brand-header">Agentic Workflows: From KYC to Continuous Compliance</h1>

<div class="wf-grid mt-1" role="group" aria-label="Workflow examples by function">
  <!-- Finance -->
  <div class="feature-card" aria-labelledby="finance-kyc">
    <div class="eyebrow">Finance</div>
    <h3 id="finance-kyc">KYC / Onboarding</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip" aria-label="Collect">Collect</span>
      <span class="phase-chip" aria-label="Screen">Screen</span>
      <span class="phase-chip" aria-label="Validate">Validate</span>
    </div>
    <div class="muted">Metric: <span class="benefit">60% faster onboarding</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-medium" aria-label="risk medium">Medium</span></div>
  </div>

  <div class="feature-card" aria-labelledby="finance-fraud">
    <div class="eyebrow">Finance</div>
    <h3 id="finance-fraud">Fraud Detection</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip">Ingest</span>
      <span class="phase-chip">Score</span>
      <span class="phase-chip">Alert</span>
    </div>
    <div class="muted">Metric: <span class="benefit">35% fewer false positives</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-high" aria-label="risk high">High</span></div>
  </div>

  <div class="feature-card" aria-labelledby="finance-recon">
    <div class="eyebrow">Finance</div>
    <h3 id="finance-recon">Reconciliation</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip">Match</span>
      <span class="phase-chip">Exception</span>
      <span class="phase-chip">Post</span>
    </div>
    <div class="muted">Metric: <span class="benefit">80% auto-match rate</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-low" aria-label="risk low">Low</span></div>
  </div>

  <div class="feature-card" aria-labelledby="finance-variance">
    <div class="eyebrow">Finance</div>
    <h3 id="finance-variance">Variance Analysis</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip">Trend</span>
      <span class="phase-chip">Explain</span>
      <span class="phase-chip">Report</span>
    </div>
    <div class="muted">Metric: <span class="benefit">50% faster close</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-low">Low</span></div>
  </div>

  <!-- Audit / Insurance -->
  <div class="feature-card" aria-labelledby="audit-prep">
    <div class="eyebrow">Audit / Insurance</div>
    <h3 id="audit-prep">Audit Prep</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip">Gather</span>
      <span class="phase-chip">Map</span>
      <span class="phase-chip">PBC</span>
    </div>
    <div class="muted">Metric: <span class="benefit">2× faster readiness</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-medium">Medium</span></div>
  </div>

  <div class="feature-card" aria-labelledby="control-testing">
    <div class="eyebrow">Audit / Insurance</div>
    <h3 id="control-testing">Control Testing</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip">Catalogue</span>
      <span class="phase-chip">Execute</span>
      <span class="phase-chip">Evidence</span>
    </div>
    <div class="muted">Metric: <span class="benefit">75% automated testing</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-medium">Medium</span></div>
  </div>

  <div class="feature-card" aria-labelledby="policy-compliance">
    <div class="eyebrow">Audit / Insurance</div>
    <h3 id="policy-compliance">Policy Compliance</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip">Map</span>
      <span class="phase-chip">Monitor</span>
      <span class="phase-chip">Certify</span>
    </div>
    <div class="muted">Metric: <span class="benefit">Continuous adherence</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-low">Low</span></div>
  </div>

  <div class="feature-card" aria-labelledby="claims-processing">
    <div class="eyebrow">Audit / Insurance</div>
    <h3 id="claims-processing">Claims Processing</h3>
    <div aria-label="workflow-steps" style="margin-bottom: 8px">
      <span class="phase-chip">Intake</span>
      <span class="phase-chip">Triage</span>
      <span class="phase-chip">Approve</span>
    </div>
    <div class="muted">Metric: <span class="benefit">30% faster settlement</span></div>
    <div class="muted">Risk: <span class="risk-badge risk-high">High</span></div>
  </div>
</div>

---

<!-- SLIDE 4 -->
<h1 class="brand-header">Risk-Native Agents: Compliance Built Into Automation</h1>

<div class="hub" role="group" aria-label="Risk-native agent hub">
  <div class="node" style="grid-column: 2; grid-row: 1" aria-label="Regulatory Monitoring Agent">
    <strong>Regulatory Monitoring Agent</strong>
    <ul class="points-clean">
      <li>Tracks rule changes; maps to controls</li>
      <li class="benefit">Cuts policy drift by 60%</li>
    </ul>
  </div>
  <div class="node" style="grid-column: 1; grid-row: 2" aria-label="Decision Explainability Agent">
    <strong>Decision Explainability Agent</strong>
    <ul class="points-clean">
      <li>Generates rationale &amp; evidence</li>
      <li class="benefit">Audit-ready narratives</li>
    </ul>
  </div>
  <div class="center" aria-label="Risk-Native Agents">Risk‑Native Agents</div>
  <div class="node" style="grid-column: 3; grid-row: 2" aria-label="Exception & Escalation Agent">
    <strong>Exception &amp; Escalation Agent</strong>
    <ul class="points-clean">
      <li>Routes, investigates, remediates</li>
      <li class="benefit">MTTR ↓ 45%</li>
    </ul>
  </div>
  <div class="node" style="grid-column: 2; grid-row: 3" aria-label="Policy Orchestration Agent">
    <strong>Policy Orchestration Agent</strong>
    <ul class="points-clean">
      <li>Enforces guardrails in workflow</li>
      <li class="benefit">Prevents non-compliant paths</li>
    </ul>
  </div>
</div>

<div class="card-grid two mt-1" role="group" aria-label="Risk framework and status">
  <div class="card" aria-label="Risk framework matrix">
    <div class="eyebrow">Risk Framework</div>
    <div class="risk-matrix" role="img" aria-label="Impact vs Likelihood matrix">
      <div class="axis-y muted small" aria-hidden="true" style="writing-mode: vertical-rl; transform: rotate(180deg);">Impact</div>
      <div class="matrix-cells" aria-hidden="true">
        <div class="cell"><div class="dot" style="background: var(--brand-green)"></div></div>
        <div class="cell"><div class="dot" style="background: var(--brand-orange)"></div></div>
        <div class="cell"><div class="dot" style="background: #FF6B6B"></div></div>
        <div class="cell"><div class="dot" style="background: color-mix(in oklab, var(--brand-green) 65%, #000)"></div></div>
      </div>
      <div></div>
      <div class="axis-x muted small" aria-hidden="true">Likelihood</div>
    </div>
  </div>

  <div class="card" aria-label="Compliance status">
    <div class="eyebrow">Status</div>
    <ul class="points-clean">
      <li><span class="risk-badge risk-low">✓ Compliant</span> — controls embedded</li>
      <li><span class="risk-badge risk-medium">◷ Under Review</span> — explainability configured</li>
      <li><span class="risk-badge risk-low">★ Audit-Ready</span> — evidence auto-collected</li>
    </ul>
  </div>
</div>

---

<!-- SLIDE 5 -->
<h1 class="brand-header">GenPact's Agentic AI Capability: From Vlinder Labs to Enterprise Scale</h1>

<div class="card-grid three mt-1" role="group" aria-label="Capability pillars">
  <div class="feature-card" aria-labelledby="cap-foundation">
    <div id="cap-foundation" class="eyebrow">Foundation</div>
    <h3>Code Gen, Orchestration, Documentation</h3>
    <ul class="points-clean">
      <li>Multi-agent planners &amp; tool-use</li>
      <li>Autogen pipelines; docs-as-code</li>
      <li>Guardrails &amp; eval suites</li>
    </ul>
    <div class="muted"><span class="benefit">Lead time ↓ 40%</span> • <span class="accent-orange">Defects ↓ 25%</span></div>
  </div>

  <div class="feature-card" aria-labelledby="cap-integration">
    <div id="cap-integration" class="eyebrow">Integration</div>
    <h3>API Orchestration, Legacy Connectors, Cloud</h3>
    <ul class="points-clean">
      <li>Wrapper SDKs for SAP, Oracle, mainframes</li>
      <li>Event-first &amp; workflow bridges</li>
      <li>Cloud-native runtimes</li>
    </ul>
    <div class="muted"><span class="benefit">Integration time ↓ 50%</span> • <span class="accent-orange">Coverage +30%</span></div>
  </div>

  <div class="feature-card" aria-labelledby="cap-domain">
    <div id="cap-domain" class="eyebrow">Domain</div>
    <h3>Financial Services, Compliance &amp; Audit, Supply Chain</h3>
    <ul class="points-clean">
      <li>Packaged controls &amp; templates</li>
      <li>Outcome SLAs &amp; reporting</li>
      <li>Playbooks and runbooks</li>
    </ul>
    <div class="muted"><span class="benefit">Time-to-value ↓ 60%</span> • <span class="accent-orange">Accuracy +20–30%</span></div>
  </div>
</div>

<div class="timeline horiz mt-1" aria-label="Proven Track Record timeline">
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">Proven Track Record</div>
      <strong>50+ Codebases</strong>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <strong>7 Agent Types</strong>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <strong>100% IP Transfer</strong>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <strong>Production Ready</strong>
    </div>
  </div>
</div>

---

<!-- SLIDE 6 -->
<h1 class="brand-header">Scaling FinTech &amp; InsurTech with Agentic AI: High-Impact, High-Velocity Deployment</h1>

<div class="split-two mt-1" role="group" aria-label="FinTech and InsurTech split">
  <div class="card" aria-labelledby="fintech-title">
    <div id="fintech-title" class="eyebrow">FinTech</div>
    <h3 class="brand-blue">Lending, Payments &amp; Settlement, CDP</h3>
    <ul class="points-clean">
      <li>
        Lending: <span class="phase-chip">Underwrite</span> <span class="phase-chip">Price</span> <span class="phase-chip">Fund</span>
        <div class="muted small">Volume: 50k+/mo • <span class="accent-orange">Revenue +4–7%</span></div>
      </li>
      <li>
        Payments &amp; Settlement: <span class="phase-chip">Match</span> <span class="phase-chip">Clear</span> <span class="phase-chip">Post</span>
        <div class="muted small">STP: <span class="benefit">85%</span> • Exceptions ↓ 40%</div>
      </li>
      <li>
        CDP: <span class="phase-chip">Ingest</span> <span class="phase-chip">Segment</span> <span class="phase-chip">Activate</span>
        <div class="muted small">Uplift: <span class="accent-orange">+10–15%</span></div>
      </li>
    </ul>
    <div class="muted"><span class="risk-badge risk-low">Compliant ✓</span> with embedded controls</div>
  </div>

  <div class="card" aria-labelledby="insurtech-title">
    <div id="insurtech-title" class="eyebrow">InsurTech</div>
    <h3 class="brand-green">Dynamic Pricing, Claims Fast‑Track, Fraud Prevention</h3>
    <ul class="points-clean">
      <li>
        Dynamic Pricing: <span class="phase-chip">Quote</span> <span class="phase-chip">Rate</span> <span class="phase-chip">Bind</span>
        <div class="muted small">Win-rate: <span class="accent-orange">+5–8%</span></div>
      </li>
      <li>
        Claims Fast‑Track: <span class="phase-chip">Intake</span> <span class="phase-chip">Triage</span> <span class="phase-chip">Approve</span>
        <div class="muted small">Cycle: <span class="benefit">48h → 8h</span></div>
      </li>
      <li>
        Fraud Prevention: <span class="phase-chip">Ingest</span> <span class="phase-chip">Score</span> <span class="phase-chip">Explain</span>
        <div class="muted small">Leakage ↓ <span class="accent-orange">25–35%</span></div>
      </li>
    </ul>
    <div class="muted"><span class="risk-badge risk-medium">Audit‑Ready ◷</span> evidence captured</div>
  </div>
</div>

<div class="overlay-timeline" role="group" aria-label="Deployment timeline">
  <div class="card">
    <div class="eyebrow">Deployment Timeline</div>
    <div class="timeline horiz">
      <div class="time-node">
        <div class="time-card">
          <strong>Week 1–2</strong><br><span class="muted small">Foundation &amp; testing</span>
        </div>
      </div>
      <div class="time-node">
        <div class="time-card">
          <strong>Week 3–4</strong><br><span class="muted small">Production</span>
        </div>
      </div>
      <div class="time-node">
        <div class="time-card">
          <strong>Month 2–3</strong><br><span class="muted small">Scale</span>
        </div>
      </div>
    </div>
  </div>
</div>

---

<!-- SLIDE 7 -->
<h1 class="brand-header">GenPact Agentic AI Roadmap: 200, 300, 400 Agents — Build &amp; Deploy Timeline</h1>

<div class="card-grid two mt-1" role="group" aria-label="Capacity and visualization">
  <div class="card" aria-label="Capacity & velocity">
    <div class="eyebrow">Capacity &amp; Velocity</div>
    <div class="capacity-grid">
      <div class="cap-card">
        <strong>Monthly</strong>
        <div class="muted small">Agents: <span class="accent-green">10–25</span></div>
        <div class="muted small">Deployments: 2–4</div>
      </div>
      <div class="cap-card">
        <strong>Quarterly</strong>
        <div class="muted small">Agents: <span class="accent-green">60–120</span></div>
        <div class="muted small">Domains: 2–3</div>
      </div>
      <div class="cap-card">
        <strong>Annual</strong>
        <div class="muted small">Agents: <span class="accent-green">200–400</span></div>
        <div class="muted small">Coverage: Enterprise</div>
      </div>
    </div>

    <div class="section-divider"></div>

    <div class="eyebrow">Stacked Agent Counts by Domain</div>
    <div class="stacked-bars" role="img" aria-label="Agent counts by domain over time">
      <div>
        <div class="bar" aria-label="Month 3 totals">
          <div class="segment seg-finance" style="width: 35%"></div>
          <div class="segment seg-audit" style="width: 25%"></div>
          <div class="segment seg-fintech" style="width: 20%"></div>
          <div class="segment seg-insurtech" style="width: 10%"></div>
          <div class="segment seg-supply" style="width: 10%"></div>
        </div>
        <div class="label">Month 3</div>
      </div>
      <div>
        <div class="bar" aria-label="Month 6 totals">
          <div class="segment seg-finance" style="width: 30%"></div>
          <div class="segment seg-audit" style="width: 30%"></div>
          <div class="segment seg-fintech" style="width: 20%"></div>
          <div class="segment seg-insurtech" style="width: 10%"></div>
          <div class="segment seg-supply" style="width: 10%"></div>
        </div>
        <div class="label">Month 6</div>
      </div>
      <div>
        <div class="bar" aria-label="Month 12 totals">
          <div class="segment seg-finance" style="width: 25%"></div>
          <div class="segment seg-audit" style="width: 30%"></div>
          <div class="segment seg-fintech" style="width: 20%"></div>
          <div class="segment seg-insurtech" style="width: 15%"></div>
          <div class="segment seg-supply" style="width: 10%"></div>
        </div>
        <div class="label">Month 12</div>
      </div>
    </div>

    <div class="legend" aria-label="Domain legend">
      <div class="item"><span class="dot" style="background: var(--brand-blue)"></span><span class="muted small">Finance</span></div>
      <div class="item"><span class="dot" style="background: var(--brand-green)"></span><span class="muted small">Audit</span></div>
      <div class="item"><span class="dot" style="background: var(--brand-orange)"></span><span class="muted small">FinTech</span></div>
      <div class="item"><span class="dot" style="background: #8B5CF6"></span><span class="muted small">InsurTech</span></div>
      <div class="item"><span class="dot" style="background: #14B8A6"></span><span class="muted small">Supply Chain</span></div>
    </div>
  </div>

  <div class="card" aria-label="Phases and outcomes">
    <div class="eyebrow">Phases 1–4</div>
    <ul class="points-clean">
      <li><strong>Phase 1:</strong> Foundation — platform, controls, pilots</li>
      <li><strong>Phase 2:</strong> Expansion — multi-function rollout</li>
      <li><strong>Phase 3:</strong> Scale — automation mesh, cross-domain</li>
      <li><strong>Phase 4:</strong> Optimize — self-healing, continuous controls</li>
    </ul>

    <div class="section-divider"></div>

    <div class="card-grid two">
      <div class="feature-card">
        <div class="eyebrow">Team Growth</div>
        <ul class="points-clean">
          <li>Core → PODs → Guilds</li>
          <li>Engineers + SMEs + Risk</li>
        </ul>
      </div>
      <div class="feature-card">
        <div class="eyebrow">ROI &amp; Confidence</div>
        <ul class="points-clean">
          <li>ROI: <span class="accent-green">3× → 12×</span></li>
          <li>Confidence: <span class="risk-badge risk-low">85% → 95% → 98%</span></li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="timeline horiz mt-1" aria-label="Roadmap timeline">
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">Month 1</div>
      <strong>Launch 10–20</strong>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">Month 3</div>
      <strong>Stabilize 50–80</strong>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">Month 6</div>
      <strong>Cross‑domain 150+</strong>
    </div>
  </div>
  <div class="time-node">
    <div class="time-card">
      <div class="eyebrow">Month 12–24</div>
      <strong>Enterprise 300–400</strong>
    </div>
  </div>
</div>

<div class="card mt-1" aria-label="References annotation">
  <div class="eyebrow">References</div>
  <div class="muted small">
    Benchmarks and ranges illustrative; tune with client baselines. Colors: headers <span style="color:#050E9B">#050E9B</span>, benefits <span style="color:#10B981">#10B981</span>, milestones/metrics <span style="color:#F59E0B">#F59E0B</span>.
  </div>
</div>
