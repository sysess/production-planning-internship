# MTM-1 (Methods-Time Measurement) Study ⏱️

This folder contains a predetermined motion time study (MTM-1) conducted to analyze, standardize, and evaluate a manual-assisted sheet metal bending operation.

## 🎯 Objective
The primary goal of this study was to break down a **3-bend sheet metal forming process** into fundamental human micro-motions (Reach, Grasp, Move, Position, Release), foot motions, and visual inspections. By combining MTM-1 motion codes with machine process times, this study establishes an objective standard time without relying solely on stopwatch observations.

## 📂 Files Included
*   **`MTM_Analysis_Template.xlsx`:** A reusable, blank MTM-1 analysis template structured for two-handed (Left Hand / Right Hand) motion tracking, automatic Effective TMU calculation, process time integration, and PFD allowance application.
*   **`MTM_Analysis_Example.xlsx`:** A completed 28-step MTM-1 analysis for a 3-bend sheet metal operation, demonstrating the practical application of simultaneous motions, eye focus inspections (`EF`), foot pedal activations, and machine-controlled process times (`PT`).

## 📊 Case Study Summary (3-Bend Sheet Metal Operation)
The analyzed operation covers picking the sheet metal from the stack, performing three consecutive bends (including in-air rotations, alignments, pedal activations, and post-bend visual inspections), and placing the finished part into a bin.

| Metric | Value | Notes |
| :--- | :--- | :--- |
| **Total Steps Analyzed** | 28 steps | Includes 3 bends, rotations, and inspections |
| **Total Manual TMU** | 252.6 TMU | Effective simultaneous LH/RH, Foot, and Eye motions |
| **Manual Time** | 9.09 sec | Converted via `1 TMU = 0.036 sec` |
| **Machine Process Time (PT)** | 24.90 sec | 3 bends × 8.3 sec per bend |
| **Net Cycle Time** | 33.99 sec | Manual Time + Machine Process Time |
| **PFD Allowance (15%)** | 5.10 sec | Personal, Fatigue, and Delay allowance |
| **Standard Time** | **39.09 sec** | **Final established work standard** |

## 🔍 Methodology & Engineering Highlights
*   **Simultaneous Motion Evaluation:** Separated Left Hand (LH) and Right Hand (RH) movements to accurately capture the limiting (Effective) TMU at each step (e.g., asymmetric hand movements during the 2nd bend).
*   **Non-Manual Elements:** Explicitly accounted for foot pedal actuation (`8.5 TMU`), visual quality inspections (`EF × 4 = 29.2 TMU` after each bend), and machine-paced bending time (`PT = 8.3 sec`).
*   **Confidentiality:** Operator identity, part codes, and specific workstation names have been anonymized in accordance with company confidentiality policies.
