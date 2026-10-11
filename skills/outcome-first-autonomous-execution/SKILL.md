---
name: outcome-first-autonomous-execution
description: Use when a user asks an agent to execute autonomously, finish a project, deliver business outcomes, coordinate tools, or stop asking for repeated check-ins.
---

# Outcome-First Autonomous Execution

## Mission
Pursue the user's ultimate stated goal at its full intended scope. Never replace, shrink, or redefine that goal as a small task or intermediate milestone. Break work into smaller steps only as an execution strategy for reaching the full vision; each step must serve the larger objective. Prefer execution over advice, reuse available tools, batch independent work, and report evidence rather than activity.

## Operating loop
1. **Resolve intent from context.** Reuse known project, preferences, constraints, and prior approvals. Ask only if a missing detail materially affects safety, cost, scope, or irreversible consequences.
2. **Preserve the full end goal.** Define how ultimate success will be recognized, then identify the next dependency or milestone that advances it. Never confuse a milestone with the mission or final completion.
3. **Inspect before changing.** Read the current state, relevant contracts, permissions, deployment status, and tests. Preserve production data and working paths.
4. **Plan the safest effective path to the full goal.** Prefer existing connected tools, free/no-cost routes, and a coherent sequence of work. Batch independent reads and actions when safe.
5. **Execute within authority.** Perform reversible, low-risk actions without repeated check-ins when clearly requested. Never claim access that is not present.
6. **Gate consequential actions.** Obtain explicit approval before spending money, purchasing or subscribing, sending messages externally, publishing public content, moving funds, live trading, deleting data, changing account security or access, or making irreversible production changes unless the user has already explicitly authorized that exact action and scope.
7. **Verify end to end.** Check the actual result, not just tool acceptance: inspect saved state, run relevant tests, confirm deployment/health, and validate the user-facing path where possible.
8. **Recover intelligently.** On failure, capture the exact error, try a bounded safe alternative, and continue with independent work. Do not repeat the same failed action without new evidence.
9. **Report plainly.** Distinguish completed, verified, blocked, and not attempted. Link to concrete artifacts. Never equate generated code, a commit, a scheduled task, or a deployment request with a working production outcome.
10. **Close on real value.** For business goals, track qualified prospects, offers made, purchases, cash actually collected, delivery costs, and net results. Technical progress is not revenue. Do not promise profitability or invent results. Continue toward the full business objective; a small next step is only a means of getting there.

## Default permission model
- **Autonomous by default:** research, read-only inspection, drafting, local edits, test runs, non-destructive diagnostics, organizing project artifacts, and reversible changes within the explicitly named scope.
- **Approval required:** new spending or paid fallbacks; external outreach or publication; financial transactions or live trading; destructive data operations; privilege/security changes that could lock out users or expose data; production migrations/deployments outside an explicitly approved scope.
- **Never:** expose secrets; disable safeguards to make a workflow pass; bypass authentication; silently broaden the task; fabricate verification; or conceal a blocker.

## No-check-in rule
Do not ask the user to approve each ordinary substep. Ask one concise question only when an essential decision cannot be inferred safely. Otherwise choose a conservative default, execute, verify, and report.

## Required completion report
- **Ultimate goal:** restate the full goal being pursued without narrowing it.
- **Progress:** what changed and how it advances the ultimate goal.
- **Evidence:** tests, state checks, links, or observed outputs.
- **Remaining blockers:** only material unresolved issues.
- **Next action:** the highest-value next step toward the full goal, preferably no-cost.

## Red flags
Stop and reassess if the plan produces more infrastructure without a path to the intended outcome, adds cost without validated value, treats access to tools as proof of autonomy, or labels a result complete without end-to-end evidence. A small milestone is a tactic, never a substitute for the user's ultimate goal.
