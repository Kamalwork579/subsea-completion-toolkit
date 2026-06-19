# Subsea Completion Toolkit

**A structured field reference for deepwater and horizontal well completion operations.**  
Covers pre-job planning through well handover, with integrated well control, hydrate management, and lessons-learned resources — aligned to API 17D / ISO 13628-4.

---

## Contents

| File | Description |
|------|-------------|
| [`CHECKLIST_COMPLETION_OPERATION.md`](./CHECKLIST_COMPLETION_OPERATION.md) | Phase-by-phase completion operation checklist with CRITICAL item flags |
| [`WELL_CONTROL_BARRIERS.md`](./WELL_CONTROL_BARRIERS.md) | Dual-barrier element verification, pressure test log templates, MAWOP guide |
| [`HYDRATE_MANAGEMENT_GUIDE.md`](./HYDRATE_MANAGEMENT_GUIDE.md) | Prevention, MEG injection design, remediation procedure for subsea flowlines |
| [`LESSONS_LEARNED_HORIZONTAL_WELLS.md`](./LESSONS_LEARNED_HORIZONTAL_WELLS.md) | Field-proven lessons covering safety, operations, equipment, and environment |
| [`ENGINEERING_CALCULATORS_PLAN.md`](./ENGINEERING_CALCULATORS_PLAN.md) | Roadmap for embedded engineering calculators (hydrostatic, burst, MEG, annular vol.) |

---

## Scope

This toolkit targets **subsea completion engineers** and **offshore well supervisors** working on:

- Deepwater single and dual-bore subsea tree installations
- Horizontal open-hole completions with sand control (screens, gravel pack, ICDs)
- HPHT completion string design and pressure testing
- Hydrate risk management during well test and shut-in periods

All procedures reference current industry standards. Where operator-specific deviations exist, they must be captured in the project Well Programme.

---

## Applicable Standards

| Domain | Standard |
|--------|----------|
| Subsea equipment design | API 17D / ISO 13628-4 |
| Well control procedures | API RP 16D / IWCF |
| Tubing design & material | API 5CT / ISO 11960 |
| H₂S material requirements | NACE MR0175 / ISO 15156 |
| SCSSV performance | API 14A |
| Downhole safety valves | ISO 10432 |
| Completion fluid handling | API RP 13B-1/13B-2 |
| Erosional velocity | API RP 14E |

---

## How to Use

1. **At program planning stage** — review `LESSONS_LEARNED_HORIZONTAL_WELLS.md` and incorporate applicable actions into the Well Programme and risk register.
2. **During pre-job HAZID** — cross-check `CHECKLIST_COMPLETION_OPERATION.md` Phase 1 items against the MOC and equipment matrix.
3. **On the rig floor** — use the phase checklists sequentially. All `★ CRITICAL` items require dual sign-off (Operator Company Rep + Contractor Supervisor).
4. **Before and during well test** — reference `HYDRATE_MANAGEMENT_GUIDE.md` for MEG injection rates and shutdown/restart procedure.
5. **At job close** — update lessons learned and submit new entries for future revision.

---

## Critical Safety Notes

> **DUAL BARRIER POLICY**: At all times during completion operations, two independent, tested well barriers must be in place. No string movement may occur unless both barriers are confirmed by the Wellsite Supervisor. Refer to `WELL_CONTROL_BARRIERS.md`.

> **HYDRATE RISK**: Subsea completions operating below the hydrate equilibrium temperature must have MEG injection active or a tested depressurization procedure in place before any planned or unplanned shutdown exceeding 4 hours.

---

## Revision History

| Rev | Date | Author | Change Summary |
|-----|------|--------|----------------|
| 3.1 | June 2026 | Engineer Mohamed | Added H-well lessons (7 entries), expanded hydrate remediation, pressure test log template |
| 3.0 | March 2026 | Engineer Mohamed | Barrier verification framework updated to align with ISO 16530-1 |
| 2.0 | Nov 2025 | Engineer Mohamed | Checklist restructured into 4 phases; MEG calculator added |
| 1.0 | Aug 2025 | Engineer Mohamed | Initial release |

---

## Contributing

Issues and pull requests are welcome. Please tag new lessons learned with one of the four categories: `safety`, `operations`, `equipment`, `environment`, and include a specific corrective action.

---

## License

MIT — see [`LICENSE`](./LICENSE). For field use, all content should be validated against your operator's well programme and local regulatory requirements.
