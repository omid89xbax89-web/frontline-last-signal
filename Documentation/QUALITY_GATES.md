# Project Quality Gates

A gate is passed only when its evidence is recorded. `NOT_TESTED` is never equivalent to `PASS`.

| Gate | Requirement | Evidence |
|---|---|---|
| G1 — Requirements | Scope, target platforms, and acceptance criteria are written | Approved brief |
| G2 — Graybox | Scale, silhouette, geometry, and collision reviewed | Screenshots and review decision |
| G3 — Visual integration | Materials, textures, and lighting work in the chosen engine | In-engine captures |
| G4 — Performance | Target devices tested and frame-time issues recorded | Device/build/test report |
| G5 — Gameplay | Controls, objectives, round flow, and restart tested | Test cases and results |
| G6 — Release | Build, known issues, and platform package verified | Release checklist |

## Test report template

- Build / commit:
- Date:
- Platform and device:
- Test case:
- Steps:
- Expected result:
- Actual result:
- Status: `PASS` / `FAIL` / `NOT_TESTED`
- Evidence:
- Known issue:

## Approval policy

The project owner approves major scope and visual decisions. A tool-generated file, successful upload, or successful deployment does not by itself pass a quality gate.
