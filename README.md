# Business Analytics and Computational Statistics (BACS) Course

This repository contains homework assignments and projects for a Business Analytics and Computational Statistics course. The assignments cover fundamental and advanced topics in statistical analysis, data manipulation, and machine learning using R.

## Table of Contents

- [Repository Structure](#repository-structure)
- [Course Overview](#course-overview)
- [Homework Assignments](#homework-assignments)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Key Technologies](#key-technologies)
- [Topics Covered](#topics-covered)
- [Usage Instructions](#usage-instructions)

## Repository Structure

The repository is organized into homework folders (hw1-hw15), each containing:
- R Markdown files (.Rmd) with analysis and code
- Compiled output files (PDF, HTML, DOCX)
- Associated data files (CSV, TXT)
- Supporting materials and visualizations

```
bacs/
├── hw1/          # Basic R Operations and Data Manipulation
├── hw2/          # [Additional R Programming Concepts]
├── hw3/          # Bootstrap Sampling and Time Series Analysis
├── hw4/          # Statistical Testing and Bootstrap Methods
├── hw5/          # Data Reshaping with tidyr
├── hw6/          # Media Type Analysis and Comparison
├── hw7/          # Recommendation Systems (PicCollage Case Study)
├── hw8/          # Linear Regression Analysis
├── hw9/          # Advanced Regression and Log Transformations
├── hw10/         # [Additional Statistical Methods]
├── hw11/         # [Security Questions Analysis]
├── hw12/         # Principal Component Analysis (PCA)
├── hw13/         # Structural Equation Modeling (SEM)
├── hw14/         # Model Comparison and Validation
└── hw15/         # Decision Trees and Bagging
```

## Course Overview

This course covers essential concepts in business analytics and computational statistics, progressing from basic data manipulation to advanced machine learning techniques. Students learn to apply statistical methods to real-world business problems using R programming.

## Homework Assignments

### HW1: Basic R Operations
- Reading and manipulating data
- Vector operations and indexing
- Basic statistical functions (mean, sorting, subsetting)
- Working with customer data

### HW3: Bootstrap Sampling and Time Series
- Time series data manipulation
- Bootstrap resampling techniques
- Standardization of variables
- Analysis of booking patterns

### HW4: Statistical Testing and Bootstrap Methods
- Bootstrap confidence intervals
- T-statistics and hypothesis testing
- Interactive statistical tools
- Visualization of bootstrap distributions

### HW5: Data Reshaping and Visualization
- Data transformation with tidyr package
- Wide-to-long format conversion
- Density plots and comparative visualization
- Analysis of Verizon response times (ILEC vs CLEC)

### HW6: Media Type Analysis
- Comparative analysis of different media types
- Statistical comparison of viewer intentions
- Data exploration with multiple datasets
- Analysis of animated audio, picture audio, picture text, and text-only media

### HW7: Recommendation Systems
- Building automated recommendation systems
- Cosine similarity calculations
- Matrix operations for similarity analysis
- PicCollage mobile app case study
- Geometric models for content recommendation

### HW8: Linear Regression Analysis
- Simple and multiple linear regression
- Residual analysis and diagnostics
- Sum of squares decomposition (SSR, SSE, SST)
- Model evaluation and interpretation

### HW9: Advanced Regression Techniques
- Log transformations and model improvement
- Residual visualization and validation
- Multi-group regression analysis
- Variable importance assessment

### HW12: Principal Component Analysis
- Dimensionality reduction techniques
- Parallel analysis for component selection
- Factor rotation and interpretation
- Security questionnaire analysis

### HW13: Structural Equation Modeling
- PLS-SEM (Partial Least Squares) modeling
- CB-SEM (Covariance-based) modeling
- Path analysis and model estimation
- Bootstrap validation of structural models

### HW14: Model Comparison and Cross-Validation
- Cross-validation techniques
- Model performance comparison
- Polynomial regression
- Decision tree modeling

### HW15: Decision Trees and Ensemble Methods
- Decision tree construction with rpart
- Bagging and ensemble methods
- Model depth optimization
- RMSE evaluation and hyperparameter tuning

## Prerequisites

- **R Programming**: Basic to intermediate knowledge of R
- **Statistics**: Understanding of descriptive and inferential statistics
- **Mathematics**: Basic linear algebra and calculus
- **Software**: R (version 3.6+) and RStudio recommended

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/chousheep/bacs.git
   cd bacs
   ```

2. **Install required R packages**:
   ```r
   # Core packages
   install.packages(c("tidyr", "ggplot2", "psych", "rpart", "rpart.plot", "data.table"))
   
   # Specialized packages
   install.packages("seminr")  # For SEM analysis
   
   # Interactive tools (if needed)
   remotes::install_github("soumyaray/compstatslib")
   ```

3. **Navigate to any homework folder** and open the .Rmd file in RStudio

4. **Run the analysis** by knitting the R Markdown document

## Key Technologies

- **R Programming Language**: Primary tool for statistical analysis
- **R Markdown**: For reproducible research and reporting
- **RStudio**: Recommended IDE for development
- **Key R Packages**:
  - `tidyr`: Data reshaping and manipulation
  - `ggplot2`: Advanced data visualization
  - `psych`: Psychological and psychometric analysis
  - `seminr`: Structural equation modeling
  - `rpart`: Decision trees and recursive partitioning
  - `data.table`: High-performance data manipulation

## Topics Covered

### Statistical Foundations
- Descriptive statistics and data exploration
- Bootstrap resampling and confidence intervals
- Hypothesis testing and statistical inference

### Data Analysis Techniques
- Data cleaning and transformation
- Exploratory data analysis (EDA)
- Time series analysis basics

### Regression and Modeling
- Simple and multiple linear regression
- Polynomial regression
- Log transformations and model diagnostics
- Model validation and cross-validation

### Advanced Analytics
- Principal Component Analysis (PCA)
- Factor analysis and dimensionality reduction
- Structural Equation Modeling (SEM)

### Machine Learning
- Decision trees and classification
- Ensemble methods (bagging)
- Model selection and hyperparameter tuning
- Performance evaluation metrics

### Business Applications
- Customer behavior analysis
- Service quality assessment (Verizon case study)
- Security perception modeling
- Predictive modeling for business decisions
- Media effectiveness analysis
- Recommendation system development
- Mobile app user behavior (PicCollage case study)

## Usage Instructions

### Running Individual Assignments

1. Open the desired homework folder
2. Load the .Rmd file in RStudio
3. Ensure all required data files are in the same directory
4. Install any missing packages prompted by the code
5. Knit the document to generate the output

### Data Files

Each homework folder contains the necessary data files. Common file types include:
- `.txt`: Tab-delimited text files
- `.csv`: Comma-separated value files
- Various business datasets for analysis

### Output Formats

The assignments generate multiple output formats:
- **PDF**: For formal report submission
- **HTML**: For interactive viewing
- **Word Document**: For collaborative editing

---

*This repository represents coursework in Business Analytics and Computational Statistics, demonstrating practical applications of statistical methods to business problems using R programming.*