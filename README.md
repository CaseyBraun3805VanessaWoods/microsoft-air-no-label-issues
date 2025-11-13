# Microsoft Air Repositories - No Label Issues Analysis

This repository contains an analysis of Microsoft's Air-related repositories for open issues that lack proper labeling.

## Report Summary

The analysis identified **11 repositories** under the Microsoft organization that contain "Air" in their name. The report tracks the number of open issues without any labels assigned.

### Key Findings

**Total Open Issues Without Labels: 229**

#### Repositories Analyzed:

1. **AirSim** - 172 unlabeled open issues
   - Most popular repository (17,677 stars)
   - Open source simulator for autonomous vehicles
   - Clearly needs the most attention for issue management

2. **AirSim-NeurIPS2019-Drone-Racing** - 27 unlabeled open issues
   - Drone racing competition repository
   - Second highest count of unlabeled issues

3. **AirSim-Drone-Racing-Lab** - 14 unlabeled open issues
   - Framework for drone racing research

4. **AIReferenceArchitectures** - 5 unlabeled open issues
   - Azure AI reference architectures (archived)

5. **apache-airflow-microsoft-fabric-plugin** - 4 unlabeled open issues
   - Apache Airflow plugin for Microsoft Fabric

6. **AirSim-Drone-Racing-VAE-Imitation** - 3 unlabeled open issues
   - Research project for aerial navigation

7. **woodgrove-airline** - 2 unlabeled open issues
   - Experimental demo project

8. **AirSim-Drone-Racing-Lab-Source** - 1 unlabeled open issue
   - Source code for AirSim Drone Racing Lab

9. **AirbandData** - 1 unlabeled open issue
   - Data repository

10. **ContosoAir** - 0 unlabeled open issues
    - Demo application (archived)

11. **airflow-providers-microsoft-fabric** - 0 unlabeled open issues
    - Microsoft Fabric provider for Airflow

## Report File

- **microsoft_air_no_label_report.json** - JSON format report with repository names and unlabeled issue counts

## Purpose

This analysis helps identify repositories that may need better issue management practices, particularly:
- Issue triage and labeling workflows
- Community management resources
- Documentation for contributors on proper issue categorization

## Recommendations

1. **AirSim** requires immediate attention with 172 unlabeled issues
2. Implement automated labeling bots for high-traffic repositories
3. Establish clear labeling guidelines for contributors
4. Consider closing or archiving stale issues without labels

## Data Collection Date

November 13, 2025

## Methodology

- Searched for all repositories under 'microsoft' organization with 'Air' in the name
- For each repository, counted open issues with no labels using GitHub's search API
- Generated JSON report with repository names as keys and unlabeled issue counts as values
