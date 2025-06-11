# Supplier Quality Management Dataset

## Overview

This repository contains a comprehensive dataset for analyzing supplier quality performance across multiple manufacturing plants. The dataset was compiled as part of a strategic initiative by Enterprise Manufacturers Ltd to centralize supplier quality assessment and establish consistent procurement standards across their operations.

## Business Context

### Problem Statement
Enterprise Manufacturers Ltd operates multiple manufacturing plants that source raw materials and maintenance supplies from various vendors. Prior to this data consolidation effort, the company faced several critical challenges:

- **No centralized procurement system** to track supplier performance
- **Inconsistent vendor relationships** across different plant locations  
- **Limited visibility** into which suppliers were delivering quality materials
- **No standardized metrics** for supplier evaluation

### Strategic Objectives
The program management team identified supplier quality centralization as a priority to:
- Reduce production downtime caused by defective materials
- Standardize vendor selection criteria across all plants
- Implement data-driven supplier performance management
- Optimize procurement processes and costs

## Dataset Description

### File Structure
```
supplier_quality_data.csv
```

### Data Schema
The dataset contains **9 columns** with the following structure:

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `Date` | Date | Date when the defect was recorded |
| `Vendor` | String | Supplier/vendor name providing the material |
| `Plant Location` | String | Manufacturing plant where material was received |
| `Category` | String | Classification of material usage (Production/Maintenance) |
| `Material Type` | String | Specific type of material (Raw materials, components, etc.) |
| `Defect Type` | String | Category of quality issue identified |
| `Defect` | String | Specific defect description |
| `Total Defect Qty` | Integer | Number of defective units received |
| `Total Downtime Minutes` | Integer | Production time lost due to defective materials |

### Key Metrics
- **Defect Quantity**: Measures the scale of quality issues from suppliers
- **Downtime Impact**: Quantifies operational impact in lost production minutes
- **Performance Consistency**: Enables comparison across vendors, plants, and materials

## Analysis Objectives

This dataset enables analysis of several critical business questions:

### Primary Questions
1. **Vendor Performance**: Which vendors are causing the greatest defect quantities?
2. **Plant Impact**: Which plant locations experience the most downtime?
3. **Material-Vendor Combinations**: Are there specific material-supplier pairings that perform poorly?
4. **Vendor-Plant Relationships**: Do certain vendor-plant combinations show poor performance?
5. **Cross-Plant Consistency**: How does the same vendor and material perform across different plants?

### Secondary Analysis Opportunities
- Temporal trends in supplier quality
- Defect type patterns by vendor or material category
- Cost impact analysis of quality issues
- Risk assessment for single-source suppliers
- Pareto analysis (80/20 rule) for quality problems

## Use Cases

### For Data Analysts
- Supplier performance dashboards
- Quality trend analysis
- Statistical modeling of defect patterns
- Predictive analytics for supplier risk

### For Procurement Teams
- Vendor scorecards and KPI tracking
- Supplier selection criteria development
- Contract negotiation data support
- Risk mitigation strategies

### For Operations Management
- Production planning optimization
- Downtime reduction initiatives
- Process improvement identification
- Plant performance benchmarking

## Getting Started

### Prerequisites
- Python 3.7+ or R 4.0+
- Data analysis libraries (pandas, matplotlib, seaborn for Python)
- Business Intelligence tools (Power BI, Tableau, etc.)


### Completeness
- All records contain complete vendor and plant information
- Date ranges and coverage may vary by plant location
- Some defect descriptions may be more detailed than others

### Considerations
- Data represents a consolidation effort across multiple plants
- Historical data availability may vary by location
- Defect classification standards may differ between plants

## Contributing

We welcome contributions to enhance the analysis of this dataset:
- Additional analysis scripts and notebooks
- Data visualization examples
- Statistical models for supplier quality prediction
- Documentation improvements

## License

This dataset is provided for educational and research purposes. Please ensure compliance with your organization's data usage policies.

## Changelog

### Version 1.0
- Initial dataset release with consolidated multi-plant data
- Complete schema documentation
- Basic analysis examples
