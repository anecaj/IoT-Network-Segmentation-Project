# Network Segmentation for IoT Security in Residential Buildings

Research project investigating the effectiveness of network segmentation in reducing lateral movement attacks within residential high-rise IoT systems.

## Overview

This project evaluates whether segmenting Internet of Things (IoT) devices into separate logical networks can reduce the success of lateral movement attacks in building automation environments. Using simulated network architectures, the research compares flat versus segmented network designs across multiple security metrics.

## Key Findings

- **67% reduction** in lateral movement success rate
- **180% improvement** in anomaly detection rates
- **5x increase** in time-to-compromise (3 minutes → 15 minutes)
- **58% reduction** in vulnerability density exposure

## Methodology

- **Simulation Tool:** GNS3 with Python automation scripts
- **Test Environment:** 40 virtualized IoT devices across 4 subsystems
  - HVAC systems
  - Access control
  - Surveillance cameras
  - Environmental controls
- **Attack Scenarios:** 20 simulated lateral movement attempts per architecture
- **Architecture Types:** Flat network vs. VLAN-based segmentation with ACLs

## Metrics Analyzed

1. **Rate of Lateral Movement Success** - Percentage of successful pivot attempts
2. **Average Time to Compromise** - Duration from reconnaissance to compromise
3. **Detection Rate** - Percentage of attempts generating identifiable anomalies
4. **Vulnerability Density** - Total exploitable vulnerabilities accessible from compromised device

## Implementation

Segmentation was implemented using:
- VLAN isolation by device function
- Access Control Lists (ACLs) restricting inter-VLAN routing
- Zero Trust principles with least-privilege communication policies

## Academic Context

This research was conducted as part of the **Introduction to Operating Systems** course at NYU Tandon School of Engineering (Fall 2025). The project addresses the growing security challenges in building automation systems where cyber and physical infrastructure converge.

## Repository Contents

- Full academic paper with detailed methodology and findings
- Academic presentation summarizing key results

## Technologies Used

- GNS3 (Network Simulation)
- Python (Automation & Scripting)
- VLAN Configuration
- Access Control Lists
- Zero Trust Architecture Principles

## Applications

This research provides evidence-based recommendations for:
- Residential high-rise building management
- Smart building infrastructure design
- IoT security architecture planning
- Building automation system deployments
