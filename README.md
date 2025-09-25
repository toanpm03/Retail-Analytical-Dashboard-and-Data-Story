# Sales analysis (Domain: Retail)
- Author: Toan Pham Minh
  
- Project Type: Retail Analytics

- Tech Stack: Power BI, Python
## Background

QlikView is the dataset used in the QlikView application, a software used to visualize and analyze data. This data set is organized as tables and linked together through common fields (key fields) to form a relational data structure.

QlikView dataset includes sample data such as Sales, Inventory, Human Resources, provided in the software so that users can easily practice and learn. In addition, users can also create and use their own data sets in QlikView for data visualization and analysis.

All datasets in QlikView are designed to allow users to perform complex data queries, generate reports, charts, and visual data models to help users better understand data. data and make more accurate business decisions.

## Model
<img width="294" height="301" alt="data_model" src="https://github.com/user-attachments/assets/12593784-1b60-447f-8d53-c2e7c556dc8a" />

## Project Structure
```text
├── data/
│   ├── 0. QlikView_2013 invoice detail.xlsx            # detailed invoice in 2013
│   ├── 0. QlikView_2014 invoice detail.xlsx            # detailed invoice in 2014
│   ├── 0. QlikView_Invoice Header.xlsx                 # overall invoice from 2013 to 2014
│   ├── 0. QlikView_Lookup Table.xlsx                   # dimension tables
├── docs/
│   └── data_dictionary.xlsx                            # glossary of data
│   ├── data_model.png                                  # data model
│   └── report.ppt                                      # automated report
│   ├── recommendation.pdf                              # sales analysis
├── notebooks/                     
│   ├── price_optimization.ipynb                        # implementation
└── README.md
