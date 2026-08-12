# Nubra TradeGuard — Product Case Study

## Product Problem

Trade execution can become difficult to understand when orders have multiple legs and unexpected execution states.

This case study explores a product hypothesis:

> Intermediate options traders may experience ambiguity around order state, rejection reasons, and per-leg execution status during high-pressure trading moments.

The project focuses on improving execution clarity without changing the underlying trading engine or providing financial advice.

---

## Product Goal

Help traders:

**Understand → Diagnose → Act**

when an unexpected execution state occurs.

---

## Proposed Solution — TradeGuard

TradeGuard is a proposed execution clarity and recovery layer around the existing trading experience.

### Core experience

1. Pre-Trade Review
2. Execution Status
3. Unexpected State Explanation
4. Recovery Options

For multi-leg strategies, the experience provides visibility into the execution state of each individual leg.

---

## Product Scope

### MVP

- Pre-trade summary
- Clear order status
- Per-leg execution visibility
- Failure/rejection explanation
- Operational recovery options
- Margin visibility
- Execution timestamps

### Out of Scope

- Trading recommendations
- Price prediction
- Automated trading decisions
- Portfolio optimization
- AI-generated financial advice

---

## Product Analytics

### North Star Metric

**Unexpected-State Resolution Rate**

Measures whether users successfully understand and resolve unexpected execution states.

### Supporting Metrics

- Order-State Comprehension Rate
- Recovery Completion Rate
- Time to Understand
- Time to Resolution
- Unexpected-State Abandonment Rate
- Support Contact Rate

### Guardrails

- Normal Trade Completion Time
- Normal Trade Abandonment Rate
- Duplicate Order Attempts
- Incorrect Recovery Actions
- Incorrect or Stale Order Status

---

## Experiment Plan

### Stage 1 — Usability Testing

Test the proposed experience with 5–8 relevant active/intermediate F&O traders.

Evaluate whether users can:

- Understand the order state
- Identify the affected leg
- Understand the failure reason
- Identify an appropriate operational next step

### Stage 2 — A/B Test

Compare:

**Control:** Existing execution experience

**Variant:** TradeGuard clarity experience

Primary metric:

**Unexpected-State Resolution Rate**

The experiment should improve exception handling without materially increasing friction during normal successful trading.

---

## Prototype

The interactive prototype covers:

**Pre-Trade Review → Execution Status → Unexpected State → Recovery**

### Figma Prototype

Paste the Figma prototype link here.

---

## Case Study Structure

The complete case study covers:

- Product Context
- Problem Hypothesis
- User & Journey
- Opportunity
- Proposed Solution
- MVP Prioritization
- Product Flow
- Product Principles
- PRD
- Metrics & Experimentation
- Interactive Prototype
