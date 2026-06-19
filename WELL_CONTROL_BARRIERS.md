[WELL_CONTROL_BARRIERS_enhanced.md](https://github.com/user-attachments/files/29135948/WELL_CONTROL_BARRIERS_enhanced.md)
# Well Control Barrier Verification

**Document:** `WELL_CONTROL_BARRIERS.md`  
**Standard:** API RP 16D | ISO 16530-1 | NORSOK D-010  
**Revision:** 3.1 — June 2026

---

## 1. Policy Statement

During all completion and intervention operations, **two independent, tested well barriers must be in place at all times**. Neither barrier shall be sacrificed without the other being fully verified and logged. Any single-barrier situation constitutes a **well control incident** and must be reported to the Operator Well Control Authority immediately.

> **Definition (ISO 16530-1):** A *well barrier* is an envelope of one or more well barrier elements that together prevent uncontrolled flow of formation fluids to the external environment.

---

## 2. Dual Barrier Matrix

The table below defines the accepted barrier elements during each phase of a standard subsea completion. All elements must be individually pressure-tested to the values in Section 4.

### Phase A — Open Hole / Pre-Packer

| Barrier | Element | Type | Note |
|---------|---------|------|------|
| **Primary** | BOP Annular / Pipe Rams | Mechanical | Pressure tested per MAWHP |
| **Primary** | Wellbore fluid column | Hydrostatic | Verified density at wellhead |
| **Secondary** | Blind/Shear Ram (BSR) | Mechanical | Function tested each tour |
| **Secondary** | Casing / Formation integrity | Structural | LOT result on record |

### Phase B — Post-Packer Set (Running Tubing)

| Barrier | Element | Type | Note |
|---------|---------|------|------|
| **Primary** | Tubing string + packer | Mechanical | Packer set confirmed by weight indicator |
| **Primary** | Completion fluid hydrostatic | Hydrostatic | Overbalance ≥ 200 psi against reservoir |
| **Secondary** | Production casing | Structural | Pressure tested |
| **Secondary** | BOP (pipe rams + annular) | Mechanical | In service above tubing hanger |

### Phase C — Well Handed Over to Tree

| Barrier | Element | Type | Note |
|---------|---------|------|------|
| **Primary** | Tubing + SCSSV + Tubing Hanger Plug | Mechanical | All tested per Sect. 4 |
| **Primary** | XMT PMV / PWV | Mechanical | Function and pressure tested |
| **Secondary** | Production casing | Structural | |
| **Secondary** | XMT Annulus Master Valve + Crown Valve | Mechanical | |

---

## 3. Maximum Allowable Wellhead Operating Pressure (MAWOP)

MAWOP governs all pressure tests and defines the operational envelope.

```
MAWOP = min(
    Casing burst at shoe × safety factor (0.8),
    Wellhead equipment pressure rating,
    Tubing burst rating × 0.875 (API de-rating)
)
```

**This well:** MAWOP = **690 bar** (based on 9-5/8" P110 casing at shoe depth).

All pressure tests must not exceed MAWOP without written Operator engineering approval.

---

## 4. Pressure Test Requirements

### 4.1 Low-Pressure Test

- Target: **70 bar ± 5 bar**
- Hold: **5 minutes** — no more than 0.7 bar / min decline permitted
- Purpose: Confirms no gross leak in connections or seals

### 4.2 High-Pressure Test

- Target: **80% MAWOP** — i.e. **552 bar** for this well
- Hold: **10 minutes** — no more than 3.5 bar / min decline permitted
- Purpose: Confirms mechanical integrity against well pressure

### 4.3 Acceptance Criteria

A pressure test **PASSES** if:

- No observed decline throughout the hold period, **or**
- Observed decline ≤ permitted rate AND can be fully attributed to temperature equalization (must be documented with temperature log)

A pressure test **FAILS** if decline exceeds the permitted rate. Remediation required before operations continue. Re-test after remediation with full documentation.

---

## 5. Pressure Test Log Template

Complete one row per test. Original copy must be signed and retained in the well file.

| Test # | Date | Component | Low Test (bar) | High Test (bar) | Hold (min) | Initial P | Final P | ΔP | Pass/Fail | Witnessed by | Notes |
|--------|------|-----------|----------------|-----------------|------------|-----------|---------|-----|-----------|-------------|-------|
| 01 | | Tubing string — full | 70 | 552 | 10 | | | | | | |
| 02 | | Packer — annulus side | 70 | 300 | 10 | | | | | | |
| 03 | | SCSSV — open | 70 | 552 | 5 | | | | | | |
| 04 | | SCSSV — closed (BPV test) | 70 | 552 | 5 | | | | | | |
| 05 | | Tubing Hanger Plug | 70 | 552 | 10 | | | | | | |
| 06 | | XMT PMV | 70 | 552 | 10 | | | | | | |
| 07 | | XMT PWV | 70 | 552 | 10 | | | | | | |
| 08 | | XMT AMV (annulus) | 70 | 300 | 10 | | | | | | |
| 09 | | Landing string SSIV | 70 | 552 | 5 | | | | | | |
| 10 | | Landing string BIV | 70 | 552 | 5 | | | | | | |

---

## 6. SCSSV Requirements (API 14A / ISO 10432)

The Surface-Controlled Subsea Safety Valve is the primary barrier element in the production tubing string. The following minimum requirements apply:

- **Type:** Flapper or ball, fail-safe-closed (spring-return)
- **Setting depth:** Minimum 100m below mudline (deepwater regulation) or as specified by Operator Well Programme
- **Pressure rating:** Minimum equal to MAWOP — i.e. **690 bar**
- **Control line:** Hydraulic, 1/4" or 3/8" SS tube, pressure-tested to 1.5× SCSSV MAWOP
- **Function test frequency:** Every 12 months per API 14A, or after any well intervention
- **Fail-safe test:** Close on loss of control line pressure; confirm full closure with applied test pressure before re-opening

### SCSSV Function Test Procedure

1. Confirm production is shut in at the wellhead.
2. Bleed off hydraulic control line pressure gradually to zero.
3. Apply tubing test pressure (552 bar) above the closed SCSSV.
4. Hold 5 minutes — record pressure readings every 30 seconds.
5. Re-pressurize control line to restore open position. Confirm by flow test.
6. Document results and sign test record.

---

## 7. Emergency Response — Loss of Barrier

If either barrier is identified as compromised:

1. **Stop all work** — no pipe movement, no pressure applications.
2. **Notify** the OIM and Operator Company Representative immediately.
3. **Assess:** Can the compromised element be isolated while the second barrier is maintained?
4. **If single-barrier situation exists:** initiate emergency barrier restoration procedure per Well Programme, Section 8.
5. **Do not resume operations** until dual-barrier status is confirmed and signed off by both Operator and Contractor Well Control Authority.

---

*Prepared by: Engineer Mohamed | Rev 3.1 | June 2026*  
*Next review: December 2026*
