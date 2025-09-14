# HR Attrition Analysis: ML + LLM Integration

## Overview
This project demonstrates the integration of traditional Machine Learning with Large Language Models to create human-readable insights from employee attrition predictions.

## Technical Stack
- **ML Models**: Random Forest, Logistic Regression
- **LLM Integration**: OpenAI GPT-4 API
- **Data**: IBM HR Employee Attrition Dataset (1,470 employees)
- **Languages**: Python, SQL

## Key Features
- Strategic sampling methodology maintaining demographic distributions
- Individual employee risk assessments with AI-generated explanations
- Portfolio-wide organizational analysis
- Cost-effective LLM integration (~$5 for 249 employee analyses)

## Results
- **Model Performance**: 84% Random Forest accuracy, 80% Logistic Regression
- **Sample Validation**: Multi-variable stratified sampling preserves department and attrition patterns
- **Business Insights**: Department-specific attrition drivers and targeted recommendations

## Setup
1. Install dependencies: `pip install pandas scikit-learn openai mysql-connector-python`
2. Configure database credentials and OpenAI API key
3. Run the Jupyter notebook

## Key Learning
Demonstrates the importance of proper sampling methodology when scaling from full datasets to cost-effective LLM analysis. Human validation remains essential for AI-assisted analytics.

## Files
- `HRattrition_LLM.ipynb` - Main analysis notebook
- `README.md` - This file
