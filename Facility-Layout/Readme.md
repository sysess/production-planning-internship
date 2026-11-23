# Facility Layout & Forklift Route Optimization

Facility layout evaluation and material handling improvement study for the manufacturing floor. This directory documents the existing shop-floor arrangement, a proposed layout revision targeting deburring workstation placement, and the corresponding forklift routing plan.

## Contents

| File | Description |
| :--- | :--- |
| `existing_layout.png` / `.pdf` | Current shop-floor layout showing workstation placement and clustered deburring tables. |
| `proposed_layout.png` / `.pdf` | Revised layout redistributing deburring tables across the center and lower columns. |
| `forklift_route.png` / `.pdf` | Optimized internal forklift travel path aligned with the revised layout. |

*(Update the filenames above to match your uploaded files.)*

## Problem Statement

In the existing layout, deburring tables are clustered in the upper section of the production floor. This creates localized congestion, increases material handling distances for parts coming from central and lower workstations, and causes unnecessary forklift backtracking.

## Layout Analysis: Advantages & Disadvantages

### 1. Existing Layout
* **Advantages:**
  * Centralizes all deburring operations in a single zone, making supervision and shared tool access straightforward.
  * Requires zero reallocation cost or downtime since the infrastructure is already in place.
* **Disadvantages:**
  * Creates a material handling bottleneck in the upper zone due to workstation clustering.
  * Forces longer travel distances and cross-traffic for work-in-process (WIP) moving from central and lower machines.
  * Increases congestion in main aisles, reducing forklift maneuverability.

### 2. Proposed Layout (Redistributed Deburring Tables)
Redistributes the deburring tables across the **center and lower columns** to position them closer to upstream forming and cutting stations.

* **Advantages:**
  * **Reduced Transport Distance:** Shortens inter-station transfer paths between cutting/bending machines and deburring stations.
  * **Balanced Floor Flow:** Eliminates clustering in the upper zone and distributes WIP more evenly across the shop floor.
  * **Improved Forklift Routing:** Clears primary aisles, enabling a cleaner, safer, and more direct forklift travel loop.
* **Disadvantages:**
  * **Implementation Effort:** Requires physical relocation of tables, power/air line adjustments (if applicable), and brief floor reorganization.
  * **Decentralized Supervision:** Spreading deburring stations across multiple zones requires slightly more coordination for shared consumables and quality checks.

## Comparison Matrix

| Evaluation Criterion | Existing Layout | Proposed Layout |
| :--- | :--- | :--- |
| **Material Flow Efficiency** | Low (backtracking & cross-flow) | High (linear, point-of-use flow) |
| **Deburring Accessibility** | Clustered in upper section | Distributed across center & lower columns |
| **Forklift Traffic & Safety** | High congestion in upper aisles | Dedicated, streamlined routing path |
| **WIP Congestion** | Localized bottlenecks | Evenly balanced across zones |
| **Implementation Cost** | None | Low-to-moderate (relocation & line setup) |

## Visual Preview

*(Optional: Uncomment and update filenames to display your PNG layouts directly in the README)*
<!--
### Existing Layout
![Existing Layout](existing_layout.png)

### Proposed Layout
![Proposed Layout](proposed_layout.png)

### Forklift Route
![Forklift Route](forklift_route.png)
-->

## Notes
- Facility dimensions, machine brand labels, and company identifiers have been omitted or generalized for confidentiality.
