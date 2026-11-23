# REFA Standard Time Study: Multi-Part Industrial Shipping Crate

REFA-based time study covering the sheet metal fabrication, surface treatment, and final assembly of a multi-part industrial shipping crate. The workbook breaks down 10 sheet-metal sub-components and the final assembly stage into elemental flow slices to calculate unit standard times ($t_e$).

## Contents

| File | Description |
| :--- | :--- |
| `REFA_Standard_Time_Example.xlsx` | 11-sheet REFA standard time workbook covering sub-component fabrication (laser cutting, bending, finishing, coating) and final crate assembly. |

*(If you also upload the blank version, add `REFA_Standard_Time_Template.xlsx` to this table.)*

## Methodology & REFA Formulation

Each worksheet divides the component's production route into sequential flow slices, recording the elemental time ($t_i$) and performance rating ($F$) to derive the standard unit time ($t_e$):

- **Main Time ($t_g$):** $\sum \left(t_i \times \frac{F}{100}\right)$
- **Resting Time Allowance ($t_{er}$):** $11\%$ of $t_g$
- **Lost / Distribution Time Allowance ($t_v$):** $10\%$ of $t_g$
- **Unit Standard Time ($t_e$):** $t_g + t_{er} + t_v = t_g \times 1.21$

## Summary of Results

| Component (Sheet) | Flow Slices | Main Time ($t_g$) [s] | Unit Time ($t_e$) [s] | Unit Time ($t_e$) [min] |
| :--- | :---: | :---: | :---: | :---: |
| Main Body (`Gövde`) | 4 | 330.0 | 399.30 | 6.66 |
| Body Side Panel (`Gövde Yan Kapak`) | 4 | 333.0 | 402.93 | 6.72 |
| Body-Lid Internal Support (`Gövde-Kapak İç Destek`) | 6 | 240.0 | 290.40 | 4.84 |
| Body-Lid Foam Support (`Gövde-Kapak Sünger Destek`) | 4 | 60.0 | 72.60 | 1.21 |
| Body Handle Hinge (`Gövde Kulp Menteşe`) | 6 | 170.0 | 205.70 | 3.43 |
| Body Lock (`Gövde Kilit`) | 6 | 280.0 | 338.80 | 5.65 |
| Body Handle (`Gövde Kulp`) | 11 | 620.0 | 750.20 | 12.50 |
| Lid Tensioner (`Kapak Gerdirme`) | 12 | 530.0 | 641.30 | 10.69 |
| Crate Lid (`Sandık Kapağı`) | 4 | 600.0 | 726.00 | 12.10 |
| Lid Lock (`Kapak Kilit`) | 6 | 195.0 | 235.95 | 3.93 |
| **Sub-Components Subtotal** | **63** | **3,358.0** | **4,063.18** | **67.72** |
| Final Assembly & Shipping Unit (`Sevk Bütünü Kutusu`) | 8 | 3,930.0 | 4,755.30 | 79.26 |
| **Grand Total (All 11 Sheets)** | **71** | **7,288.0** | **8,818.48** | **146.97** |

## Process Highlights
- **Fabrication Operations:** Sub-components primarily move through laser cutting, inter-station transfer, bending (press brake and eccentric press), and surface finishing/deburring.
- **Outsourced Operations:** Processes marked with `*` in the workbook (such as coating/painting on the Body Handle and sandblasting on the Lid Tensioner) are performed off-site.
- **Primary Bottleneck:** Final assembly accounts for **53.9%** of the total unit time, driven mainly by welding (`2,100 s`) and coating/painting (`840 s`).

## Notes
- Flow slice descriptions and sheet names are in Turkish; table headers and REFA parameters are in English.
- Product identifiers and customer-specific details have been anonymized for confidentiality.
