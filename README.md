# TUOS KNIME Coursework

A comprehensive collection of KNIME workflows developed during the University of Sheffield coursework, covering essential data analytics and machine learning concepts using KNIME Analytics Platform.

## Overview

This repository contains weekly KNIME projects demonstrating practical skills in data manipulation, visualization, statistical analysis, machine learning, and time series forecasting. Each week focuses on different aspects of the data science workflow.

## Project Structure

```
TUOS-KNIME-coursework/
├── Data/                          # Shared datasets used across workflows
├── Week 1/                        # Data exploration and visualization basics
├── Week 2/                        # Data integration and transformation
├── Week 3/                        # Advanced data preprocessing
├── Week 4/                        # Machine learning models
├── Week 5/                        # Model evaluation and optimization
├── W6 TSA & Forecasting/         # Time series analysis and forecasting
└── README.md                      # This file
```

## Weekly Breakdown

### Week 1: Data Exploration & Visualization
**Focus:** Introduction to KNIME, data loading, and basic visualization

- **Key Nodes:** File Reader, Statistics, Scatter Plot, Color Manager, GroupBy
- **Outputs:** 
  - `Output CSV.csv` - Filtered/processed data
  - `Output 2.csv` - Statistical summaries
  - `Output 3.csv` - Aggregated results
- **Skills Covered:**
  - CSV file reading
  - Statistical analysis
  - Data filtering and grouping
  - Scatter plot visualization
  - Color-coded visualization

### Week 2: Data Integration & Transformation
**Focus:** Working with multiple data sources and data transformation techniques

- **Key Nodes:** Concatenate, Date/Time operations, Column operations, CSV Writer, Table Reader
- **Capabilities:**
  - Combining multiple datasets
  - Date and time manipulation
  - Column filtering and transformation
  - Data export and storage
- **Skills Covered:**
  - Data concatenation
  - Temporal data handling
  - Complex transformations

### Week 3: Advanced Data Preprocessing
**Focus:** Handling missing values, outliers, and data quality issues

- **Key Techniques:**
  - Missing value treatment
  - Outlier detection and handling
  - Data normalization and scaling
  - Feature engineering
- **Skills Covered:**
  - Data cleaning best practices
  - Quality assurance
  - Advanced preprocessing pipelines

### Week 4: Machine Learning Models
**Focus:** Building and implementing predictive models

- **Key Algorithms:**
  - Classification models
  - Regression models
  - Decision trees and ensemble methods
- **Skills Covered:**
  - Model selection
  - Training and validation
  - Hyperparameter tuning
  - Prediction workflows

### Week 5: Model Evaluation & Optimization
**Focus:** Assessing model performance and improving accuracy

- **Evaluation Metrics:**
  - Confusion matrices
  - ROC curves
  - Cross-validation
  - Performance metrics (accuracy, precision, recall, F1-score)
- **Skills Covered:**
  - Performance analysis
  - Model comparison
  - Optimization techniques

### W6: Time Series Analysis & Forecasting
**Focus:** Advanced temporal data analysis and predictive forecasting

- **Key Nodes:** 
  - ARIMA Learner & Predictor
  - Lag Column
  - Moving Aggregator
  - Time Series analysis tools
  - Linear Regression Learner
  - String to Date/Time conversion
- **Techniques:**
  - ARIMA modeling
  - Lag feature creation
  - Moving averages
  - Autocorrelation analysis (ACF)
  - Time-based data visualization
  - Linear correlation analysis
- **Outputs:**
  - Time series forecasts
  - Trend visualizations
  - ACF plots and analysis
- **Skills Covered:**
  - Time series decomposition
  - Stationarity testing
  - ARIMA parameter extraction and optimization
  - Forecasting accuracy assessment

## Dataset Overview

The `Data/` folder contains various datasets used throughout the coursework:

| Dataset | Type | Use Case |
|---------|------|----------|
| `iris_data.csv` | Tabular | Classification examples |
| `Glucose_Level_dataset.csv` | Tabular | Regression examples |
| `weather-*.table` | Temporal | Time series analysis |
| `Real estate.csv` | Tabular | Regression modeling |
| `sales2008-2011.csv` | Temporal | Time series forecasting |
| `credit-card-small.csv` | Tabular | Classification tasks |
| `caco-*.table` | Temporal | Advanced analysis |
| `vehicle.table` | Tabular | Multiclass classification |
| `wines.csv` | Tabular | Clustering & classification |
| `Calls.csv` | Temporal | Call center analytics |
| `ContractData.csv` | Tabular | Business analytics |

## Getting Started

### Prerequisites
- KNIME Analytics Platform (v5.5.3 or higher recommended)
- Java Runtime Environment (JRE)
- Basic knowledge of data analysis concepts

### Opening Workflows
1. Launch KNIME Analytics Platform
2. Navigate to the desired week folder
3. Open the `workflow.knime` file
4. Review the nodes and connections in the workflow
5. Execute the workflow (Ctrl+F6 or right-click → Execute)

### Using the Workflows
- **View Results:** Right-click on output nodes (CSV Writer, visualization nodes) and select "View"
- **Modify Parameters:** Double-click nodes to adjust settings
- **Explore Data:** Use Table Viewer nodes to inspect intermediate results
- **Regenerate Outputs:** Re-execute the workflow with modified parameters

## Key KNIME Concepts Used

| Concept | Description |
|---------|-------------|
| **Nodes** | Individual processing units performing specific operations |
| **Ports** | Connection points for data flow between nodes |
| **Workflows** | Directed acyclic graphs of connected nodes |
| **Data Types** | String, Number, Date/Time, Collection types |
| **Metanodes** | Grouped nodes for organization and reusability |
| **Configuration** | Node-specific settings for customization |

## Learning Outcomes

Upon completing these workflows, you will understand:
- Data loading and preprocessing strategies
- Statistical and exploratory data analysis
- Data visualization and interpretation
- Machine learning model development and evaluation
- Time series analysis and forecasting techniques
- KNIME platform best practices
- Workflow design and optimization

## File Organization

Each week folder contains:
- **workflow.knime** - Main workflow file (open in KNIME)
- **workflow-metadata.xml** - Workflow metadata
- **workflowset.meta** - Workflow set configuration
- **Node Folders** - Individual node configurations and settings
- **CSV Files** - Output files from various workflows
- **Data/** - Local data folder (Week 2+)

## Version Information

- **KNIME Version:** 5.5.3
- **Created By:** khalilalakbarzade
- **Last Updated:** March 2026
- **Course:** University of Sheffield Data Analytics

## Notes

- Always ensure KNIME is properly installed before executing workflows
- Some workflows may require additional extensions or plugins
- CSV output files are automatically generated in their respective week folders
- Workflows are designed to be modular and can be executed independently
- Data flows are indicated by arrows connecting nodes

## Tips for Best Results

✓ Execute workflows sequentially to understand data flow  
✓ Examine intermediate results using Table Viewer nodes  
✓ Modify node parameters to experiment with different approaches  
✓ Check the KNIME console for error messages and debugging information  
✓ Save modified workflows with descriptive names for version control  

## Support & Resources

- KNIME Official Documentation: https://www.knime.com/knime-documentation
- KNIME Community Forum: https://forum.knime.com/
- Local KNIME Hub within the Analytics Platform
- Workflow comments and annotations for context

---

**Author:** Khalil Alakbarzade  
**Institution:** University of Sheffield  
**Last Modified:** March 18, 2026
