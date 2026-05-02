# APAN5205 Group 10 — AI Skill Profiling via K-Means Clustering

This repository contains two clustering analyses investigating AI-related skill demand
in the U.S. labor market — one from the **employer perspective** (job postings) and one
from the **developer perspective** (survey responses).

---

## Repository Structure

```
├── Working_Cluster_survey_data.ipynb              # Working Codes for Analysis 1: Developer Survey Skill Profiling
├── Working_Cluster_job_posting.ipynb              # Working Codes for Analysis 2: AI Job Posting Skill Profiling
├── Final_Clustering_Analysis.ipynb                # Final Codes for two analyses
│
├── data/
│   ├── prepared_job_posting_ai.csv    # Input data for Analysis 1
│   └── prepared_survey_data.csv       # Input data for Analysis 2
│   ├── adzuna_ai_all_available.csv    # Original raw data for Analysis 1
│   ├── jobpost_cluster_k_search.csv   # Summary data for Analysis 1
│   ├── final_cluster_summary.csv      # Summary data for Analysis 2
|
├── fig0_skill_prevalence.png                 # Overall skill prevalence bar chart
├── fig1_seniority_level_overview.png         # Seniority distribution and salary overview
├── fig2_elbow_silhouette.png                 # Optimal K selection: Elbow + Silhouette
├── fig3_centroid_heatmap.png                 # Cluster × Skill centroid heatmap
├── fig4_top_skills_per_cluster.png           # Top skills per cluster (bar grid)
├── fig5_cluster_exp_level_bar.png            # Experience level composition per cluster
├── fig5_cluster_seniority_level_bar.png      # Seniority level composition per cluster
├── fig6_cluster_seniority_level_heatmap.png  # Cluster × Seniority heatmap
├── fig7_salary_cluster_seniority_level.png   # Mean salary by cluster × seniority
├── fig8_salary_violin.png                    # Salary violin plot by cluster
├── fig9_pca_scatter.png                      # PCA 2-D projection coloured by cluster
├── fig10_cooccurrence_bubble.png             # Skill co-occurrence bubble chart
│
├── elbow_plot_survey.png                     # Elbow plot for developer survey clustering
├── sil_plot_survey.png                       # Silhouette plot for developer survey clustering
├── skill_prevalence_heatmap.png              # Skill prevalence heatmap across clusters (survey)
├── skill_correlation_fingerprints.png        # Global skill co-occurrence matrix (survey)
├── job_title_misalignment.png                # Job title composition per cluster (survey)
├── specialist_vs_polyglot_radar.png          # Radar chart: Specialist vs. Generalist (survey)
│
└── README.md

```
