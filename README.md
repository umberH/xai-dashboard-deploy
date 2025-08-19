# XAI Benchmarking Dashboard

Interactive Streamlit dashboard for analyzing XAI (Explainable AI) benchmarking results.

## 🚀 Features
- **Experiment Overview**: Summary statistics and metrics
- **Model Performance**: Compare models across datasets  
- **Explanation Methods**: Analyze different XAI techniques
- **Performance Analysis**: Time complexity and efficiency metrics
- **Individual Instance Analysis**: Detailed explanation exploration
- **Feature Importance**: Deep dive into feature contributions

## 📊 Data Structure
The dashboard analyzes experiment data from:
- `results/experiment_*/benchmark_results.json` - Main experimental results
- `results/experiment_*/detailed_explanations/` - Individual explanations
- `results/experiment_*/comprehensive_report.md` - Summary reports

## 🎯 Usage
1. Select an experiment from the sidebar
2. Use filters to focus on specific datasets/models/methods
3. Explore different analysis tabs
4. Drill down into individual instances for detailed explanations

## 🔧 Local Development
```bash
pip install -r requirements.txt
streamlit run streamlit_dashboard.py
```

## 📈 Supported Analysis
- SHAP visualizations (waterfall plots, summary plots)
- LIME local explanations  
- Feature attribution analysis
- Counterfactual explanations
- Prototype analysis
- Performance benchmarking
