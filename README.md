# Arbutus Financial Audit Tools

A comprehensive collection of financial audit procedures and analysis tools using Arbutus Analyzer software for conducting detailed financial audits.

## 📋 Project Overview

This repository contains a complete financial audit framework including:
- Data integrity verification procedures
- Automated audit testing scripts (SmartApps)
- Financial analysis and risk assessment tools
- Comprehensive audit documentation and findings
- Sample data files and training materials

## 📁 Repository Structure

### Core Audit Files
```
Arbutus/
├── Account Payable.fil          # Accounts payable data file
├── AccountsReceivable.fmt       # Accounts receivable format definition
├── AP_Trans_2021.fmt           # 2021 AP transactions format
├── Cash_Disburhsment.fmt       # Cash disbursement format
├── Cash_GL.avw                 # Cash general ledger view
├── CustomerCreditLimit.fmt     # Customer credit limit format
├── EmployeeMaster.fmt          # Employee master data format
├── Inventory.fmt               # Inventory data format
├── Payroll_Excel.FIL          # Payroll data file
├── Piutang_Per_Customer.fmt    # Customer receivables format
└── Ghost_employee.fmt          # Ghost employee detection format
```

### Excel Data Files
```
Data Files/
├── AR.xlsx                     # Accounts Receivable data
├── Account Payable.xlsx        # Accounts Payable data
├── Cash Disbursement.xlsx      # Cash disbursement transactions
├── Cash GL.xlsx               # Cash General Ledger
└── Arbutus data Fixed Asset.xlsx     # Fixed asset master data
```

### ATLAS Training Materials
```
Training/
├── ATLAS.xlsx                 # ATLAS audit software examples
├── Aplikasi ATLAS 2018 Version 2.0.1_9-10-2020.xlsx  # ATLAS application v2.0.1
├── Contoh pelatihan Atlas_normalisasi data akuntansi.xlsx  # ATLAS training examples
├── Atlas.rar                  # ATLAS compressed archive files
└── Realsa Data.zip           # Real sample data archive
```

### SmartApps Automated Procedures
```
Prakdit/SmartApps/
├── Accounts Payable/
│   ├── AP02_Duplicate_Invoices_Or_Payments.pro
│   ├── AP03_Creditors_With_Net_Debit_Balances.pro
│   ├── AP04_Creditors_With_Balances_Greater_Than_Credit_Limit.pro
│   ├── AP05_Transactions_Posted_On_Weekends_And_Holidays.pro
│   ├── AP08_Transactions_Around_Specified_Date.pro
│   ├── AP09_Transactions_Posted_On_Specific_Dates.pro
│   ├── AP11_Transactions_By_Userid.pro
│   ├── AP13_Transactions_With_Rounded_Amounts.pro
│   └── AP14_Disbursements_Above_Threshold.pro
├── Accounts Receivable/
│   ├── AR01_Duplicate_Receivables.pro
│   ├── AR02_Debtors_With_Balances_Greater_Than_Credit_Limit.pro
│   ├── AR03_Debtors_With_Total_Amounts_Greater_Than_Credit_Limit.pro
│   └── AR04_Aged_Receivables_Analysis.pro
├── Fixed Asset/
│   └── SmartApps_FA_Header_.pro
└── Fraud Detection/
    └── SmartApps_Fraud_Header_.pro
```

### Documentation
- `Analytics Result.pdf` - Comprehensive audit analytics results
- `Audit Results in Infographics.html` - Interactive audit findings infographic

## 🔍 Audit Procedures

### 1. Cash and Cash Equivalents
- **Data Integrity**: Field verification, duplicate detection, sequence gap analysis
- **Authorization Testing**: 3-level approval hierarchy validation
  - Level 1 (Department Head): Rp 20M - Rp 50M
  - Level 2 (Finance Manager): Rp 50M - Rp 100M  
  - Level 3 (CEO): > Rp 100M

### 2. Accounts Receivable
- **Credit Limit Analysis**: Detection of transactions exceeding customer credit limits
- **Aging Analysis**: Comprehensive receivables aging with risk assessment
- **Negative Balances**: Identification and analysis of credit balances
- **Data Quality**: Customer number gaps and duplications analysis

### 3. Inventory Management
- **Cost Verification**: Total inventory cost validation (Rp 320.557.500)
- **Negative Inventory**: Detection of negative stock levels
- **Data Completeness**: Missing date fields and data integrity checks

### 4. Fixed Assets
- **Depreciation Accuracy**: Comparative analysis of management vs. calculated depreciation
- **Asset Valuation**: Verification of acquisition costs and accumulated depreciation
- **Error Detection**: Identification of calculation discrepancies

### 5. Accounts Payable
- **Duplicate Detection**: Invoice and payment duplication analysis
- **Aging Analysis**: Overdue payables identification
- **Vendor Analysis**: Concentration and credit balance analysis

### 6. Payroll and Employee Data
- **Employee Master Verification**: Employee records validation
- **Payroll Calculations**: Gross pay, tax deductions, and net pay verification
- **Ghost Employee Detection**: Identification of phantom employees
- **Department and Salary Analysis**: Statistical analysis by department and position

## 📊 Key Findings Summary

### ✅ Clean Areas
- Cash disbursement data integrity: **0 errors**
- Inventory product numbering: **No duplications**
- Fixed asset total balances: **All reconciled**

### ⚠️ Areas Requiring Attention
- **Accounts Payable**: 2 duplicate invoice numbers detected
- **Fixed Assets**: 5 depreciation calculation errors identified
- **Receivables**: 2 transactions exceeding credit limits

### 🔴 Critical Issues
- **100% of payables** are overdue (>181 days)
- **Rp 80.5M** in overdue receivables (40.25% of total)
- Missing date fields in inventory records

## 🚀 Getting Started

### Prerequisites
- Arbutus Analyzer software
- ATLAS audit software (optional)
- Microsoft Excel (for viewing data files)
- File extraction software (for .rar and .zip files)
- Access to company financial data files
- Appropriate audit permissions

### File Formats Supported
- **`.fmt`** - Arbutus format definition files
- **`.fil`** - Arbutus data files
- **`.avw`** - Arbutus analysis view files
- **`.pro`** - Arbutus SmartApp procedure files
- **`.xlsx/.xls`** - Excel data files
- **`.csv`** - Comma-separated values
- **`.pdf`** - Documentation and results
- **`.html`** - Interactive reports and infographics
- **`.rar/.zip`** - Compressed archive files

### Usage Instructions

1. **Extract Archives**: 
   - Extract `Atlas.rar` for additional ATLAS tools and examples
   - Extract `Realsa Data.zip` for real sample data files

2. **Data Import**: 
   - Load the `.fmt` format files into Arbutus Analyzer
   - Import Excel files for comparative analysis
   - Use extracted data for additional validation

3. **Run SmartApps**: Execute the automated procedures in the Prakdit folder

4. **Review Results**: Analyze outputs using the provided format definitions

5. **Documentation**: Reference the presentation and infographic for detailed findings

### Running Specific Tests

```bash
# Example: Run AP duplicate detection
Open: AP02_Duplicate_Invoices_Or_Payments.pro

# Example: Analyze receivables aging
Open: AR04_Aged_Receivables_Analysis.pro

# Example: Fixed asset depreciation verification
Open: SmartApps_FA_Header_.pro
```

### Working with Archive Files

```bash
# Extract training materials:
Extract: Atlas.rar
# Contains additional ATLAS software tools and examples

# Extract sample data:
Extract: Realsa Data.zip
# Contains real-world sample data for testing procedures
```

## 📈 Audit Results Dashboard

View the interactive audit results in `Audit Results in Infographics.html` which provides:
- Real-time data integrity status
- Visual risk assessment charts
- Detailed finding explanations
- Compliance status indicators

## 🎓 Training Resources

### ATLAS Software Training
- **ATLAS.xlsx**: Basic ATLAS functionalities
- **Aplikasi ATLAS 2018 Version 2.0.1**: Complete ATLAS application guide
- **Contoh pelatihan Atlas_normalisasi data akuntansi.xlsx**: Data normalization examples
- **Atlas.rar**: Additional ATLAS tools and resources (compressed)
- **Realsa Data.zip**: Real sample data for practical training

### Sample Data for Learning
- All Excel files can be used for training purposes
- Real sample data available in compressed archives
- Multiple format examples for different audit scenarios

## 📝 Data Quality Assurance

### Comprehensive Data Coverage
- **Financial Statements**: Complete GL, AP, AR data
- **Operational Data**: Fixed assets
- **Supporting Documentation**: Customer limits, employee records
- **Training Materials**: Real-world sample data and tools

## 🔧 Technical Specifications

### Data Processing Capabilities
- Multi-format data import (Arbutus, Excel, compressed archives)
- Automated data validation and integrity checks
- Real-time error detection and reporting
- Cross-reference validation between multiple sources

### Archive Management
- Compressed file support for efficient storage
- Organized training materials and sample data
- Easy extraction and deployment of audit tools

## 📝 Compliance & Standards

This audit framework follows:
- Indonesian Financial Accounting Standards
- Internal audit best practices
- Risk-based audit methodology
- Data analytics audit techniques
- International auditing standards

## 🤝 Contributing

When contributing to this audit framework:
1. Ensure all procedures are tested with sample data
2. Document any new SmartApps thoroughly
3. Update the infographic with new findings
4. Maintain consistency with existing naming conventions
5. Test with both Arbutus and Excel data formats
6. Properly compress large files for efficient storage

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Author**: Muhammad Baihaqi (@bhqmuhammad)  
**Project**: Arbutus Financial Audit Framework  
**Last Updated**: June 9, 2025 at 11:07 UTC

---

**Audit Period**: 2021 Financial Year  
**Tool Version**: Arbutus Analyzer & ATLAS 2018 v2.0.1  
**Data Files**: Excel files, compressed archives, and Arbutus formats  
**Repository Status**: Active (Latest commit: June 9, 2025 at 11:07 UTC)

## 🔗 Quick Links

- [View Interactive Results](Audit%20Results%20in%20Infographics.html)
- [Download Analytics Report](Analytics%20Result.pdf)
- [Browse All Commits](https://github.com/bhqmuhammad/arbutus/commits) for complete file history

*Note: Results may be incomplete due to API limitations. View the [complete commit history](https://github.com/bhqmuhammad/arbutus/commits?sort=updated&order=desc) for all changes.*
