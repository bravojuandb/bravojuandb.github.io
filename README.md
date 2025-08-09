## Welcome – I’m Juan

> **"Omnia disce, videbis postea nihil esse superfluum."**  
> *"Learn everything; you will see later that nothing is superfluous."*  
> — *Hugh of Saint Victor, Didascalicon III.4*


# Solo Agile Manifesto (Juan’s One-Pager)

## Purpose
Ship measurable pieces of work after every weekly sprint (see my Projects)

## Principles
1) Value > Activity  
   I measure weeks by delivered outcomes (running code, docs, tests), not hours.

2) Short Feedback Loops  
   Plan → build → test → review → adjust, in one-week cycles.

3) Make Work Visible  
   Every task is an Issue; every Issue has acceptance criteria; the board reflects reality.

4) Limit WIP  
   ≤3 items In Progress. Finish what I start.

5) Blockers Are First-Class  
   If I’m stuck >30 minutes, I open a BLOCKER issue and either solve it or switch tasks.

6) Prefer Small, Done Increments  
   A simple running pipeline beats a half-built “perfect” pipeline.

7) Definition of Done (DoD)
   • Code runs from a clean clone  
   • Logged & parameterized (argparse)  
   • README “How to run” verified in a fresh environment  
   • Basic tests (or a verifiable check) pass  
   • PR merged to main

8) Ruthless Retrospectives  
   End of week: What shipped? What slipped (why)? What will I change next week?

9) Backlog Discipline  
   New ideas go to Backlog, not into the current sprint—unless they unblock or are critical.

10) Public, Professional Trace  
   Clean commits, clear PRs, issues linked. My GitHub should read like a portfolio of decisions.

## Weekly Cadence
- **Sun/Mon**: Plan sprint; size tasks (S/M/L); lock scope.  
- **Daily**: Move cards; keep WIP small; raise Blockers.  
- **Fri/Sat**: Review + Retrospective; carry over intentionally.

## Quality Guardrails
- Conventional commits (e.g., `feat:`, `fix:`, `docs:`)  
- One feature branch per Issue  
- CI/checks green before merge  
- Squash merge to keep history crisp

> Motto: Plan small, ship weekly, learn always.
