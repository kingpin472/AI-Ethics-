# AI Fairness Audit: COMPAS Dataset Analysis

![Fairness Metrics Comparison](results/plots/fairness_comparison.png)

## 📋 Project Description
This repository contains a fairness audit of the COMPAS recidivism risk assessment tool, implementing bias detection and mitigation techniques using Python and AIF360.

## 🚀 Quick Start
1. **Install dependencies**:
   ```bash
   pip install aif360 pandas numpy matplotlib scikit-learn

Download data:

bash
wget https://raw.githubusercontent.com/propublica/compas-analysis/master/compas-scores-two-years.csv
Run analysis:

bash
python compas_audit.py
📂 File Structure
text
.
├── compas_audit.py            # Main analysis script
├── compas-scores-two-years.csv # Dataset
├── results/
│   ├── plots/                 # Generated visualizations
│   └── reports/               # Analysis summaries

🔍 Key Metrics
Metric	Target Value	Description
Disparate Impact	1.0	Ratio of favorable outcomes between groups
Statistical Parity Difference	0.0	Difference in positive outcome rates
False Positive Rate Difference	0.0	Difference in error rates for non-recidivists

📊 Sample Output
Original Data Fairness:
==========================================
• Disparate Impact: 0.63 
• Statistical Parity Difference: -0.18

After Mitigation:
==========================================
• Disparate Impact: 0.89  
• Statistical Parity Difference: -0.04
📚 Resources
ProPublica's COMPAS Analysis

AI Fairness 360 Documentation

EU AI Ethics Guidelines

⚖️ Ethical Note
This analysis contains sensitive criminal justice data. Please:

Anonymize all results

Contextualize findings appropriately

Consider societal impact when sharing

📝 License
MIT License
### Key Features:
1. **Clean Markdown Formatting** - Ready to paste into your repository
2. **Visual Structure** - With clear sections and emoji icons
3. **Self-Contained** - Includes all essential information
4. **Actionable** - Direct copy-paste commands for setup
5. **Ethical Reminders** - Prompts for responsible handling of sensitive data

Just copy this entire block and save as `README.md` in your project root. The formatting will render perfectly on GitHub/GitLab.
