# UIDAI Aadhaar Data Analysis: National Hackathon Submission

This repository contains a comprehensive data analysis of Aadhaar enrolment and update datasets (March - December 2025). The goal is to provide actionable insights for UIDAI's operational efficiency and policy planning.

## Project Structure
- `comprehensive_uidai_analysis.ipynb`: The primary analytical pipeline (Cleaning, EDA, Clustering, Stress Index).
- `UIDAI_Hackathon_Report_Draft.md`: Final strategic report for jury submission.
- `visuals/`: Directory containing high-fidelity charts and figures.
- `requirements.txt`: Python dependencies.
- `venv/`: Virtual environment setup.

## Key Insights
- **Adult Saturation**: 97% of enrolments are for minors; recommending a shift to neonatal integration.
- **Service Stress Index (SSI)**: A predictive metric for identifying infrastructure bottlenecks.
- **Operational Archetypes**: Clustering states into distinct profiles for targeted resource allocation.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd <repo-name>
   ```
2. Set up the environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   jupyter notebook comprehensive_uidai_analysis.ipynb
   ```

## Note on Data
The analysis assumes the presence of UIDAI's aggregated enrolment and update datasets in the root directory.
