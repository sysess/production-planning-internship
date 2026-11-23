# MTM-1 Study: Sheet Metal Bending Operation

Predetermined motion time study (MTM-1) for a 3-bend manual-assisted sheet metal forming process. This directory contains a reusable two-handed analysis template and a completed 28-step case study used to establish the operation's standard time.

## Contents

| File | Description |
| :--- | :--- |
| `MTM_Analysis_Template.xlsx` | Blank two-handed (LH/RH) MTM-1 worksheet with built-in formulas for Effective TMU, cycle time, and PFD allowance. |
| `MTM_Analysis_Example.xlsx` | Completed 28-step MTM-1 breakdown for a 3-bend sheet metal part (operator, part code, and workstation fields anonymized). |

## Process Scope

The case study tracks a single operator through the full cycle of a three-bend forming sequence:
1. Reaching for and grasping the sheet metal from the stack (`R40B`, `G1B`) and positioning it at the die (`M40C`, `P1SE`).
2. Executing three consecutive bends, each consisting of foot pedal actuation (`8.5 TMU`), machine-paced bending (`PT = 8.3 s`), part withdrawal, in-air rotation/re-positioning, and visual quality inspection (`EF × 4`).
3. Transferring and releasing the finished part into the output bin (`M50B`, `RL1`).

## Calculation & Results

Standard time is calculated using the MTM-1 conversion factor (`1 TMU = 0.036 s`) and a 15% Personal, Fatigue, and Delay (PFD) allowance:

- **Manual Time** = `Total Effective TMU × 0.036`
- **Net Cycle Time** = `Manual Time + Machine Process Time`
- **Standard Time** = `Net Cycle Time × (1 + PFD Allowance)`

| Parameter | Value | Details |
| :--- | :--- | :--- |
| Total Steps | 28 | Full cycle including 3 bends and inspections |
| Total Manual TMU | 252.6 TMU | Limiting (Effective) LH/RH, foot, and eye motions |
| Manual Time | 9.09 s | `252.6 × 0.036 s` |
| Machine Process Time (PT) | 24.90 s | `3 bends × 8.3 s` |
| Net Cycle Time | 33.99 s | Manual + machine-controlled time |
| PFD Allowance (15%) | 5.10 s | Standard allowance applied to net cycle time |
| **Standard Time** | **39.09 s** | **Established work standard** |

## Using the Template

1. Open `MTM_Analysis_Template.xlsx` and fill in the header metadata (date, workstation, part reference).
2. Break the task into sequential steps and log Left Hand (LH) and Right Hand (RH) descriptions along with their MTM-1 codes and TMU values.
3. For simultaneous motions, record the limiting value under **Effective TMU** (e.g., asymmetric hand movements during the 2nd bend).
4. Enter machine-controlled process times (`PT`) separately so they are added to the manual time without duplicating operator TMU.

## Notes
- Motion descriptions in the example sheet are written in Turkish; column headers and summary metrics are in English.
- All company-specific identifiers (operator name, part code, and machine model) have been removed for confidentiality.
