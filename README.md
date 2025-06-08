# Arbutus Financial Audit Tools

A comprehensive collection of financial audit procedures and analysis tools using Arbutus Analyzer software for conducting detailed financial audits.

## 📋 Project Overview

This repository contains a complete financial audit framework including:
- Data integrity verification procedures
- Automated audit testing scripts (SmartApps)
- Financial analysis and risk assessment tools
- Comprehensive audit documentation and findings

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
- `Slide Presentasi.pdf` - Comprehensive audit presentation
- `infografis prakdit.html` - Interactive audit findings infographic

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

## 📊 Key Findings Summary

### ✅ Clean Areas
- Cash disbursement data integrity: **0 errors**
- Inventory product numbering: **No duplications**
- Fixed asset total balances: **All reconciled**

### ⚠️ Areas Requiring Attention
- **Accounts Payable**: 2 duplicate invoice numbers detected
- **Inventory**: 2 items with negative balances (-Rp 200,000)
- **Fixed Assets**: 5 depreciation calculation errors identified
- **Receivables**: 2 transactions exceeding credit limits

### 🔴 Critical Issues
- **100% of payables** are overdue (>181 days)
- **Rp 80.5M** in overdue receivables (40.25% of total)
- Missing date fields in inventory records

## 🚀 Getting Started

### Prerequisites
- Arbutus Analyzer software
- Access to company financial data files
- Appropriate audit permissions

### Usage Instructions

1. **Data Import**: Load the `.fmt` format files into Arbutus Analyzer
2. **Run SmartApps**: Execute the automated procedures in the Prakdit folder
3. **Review Results**: Analyze outputs using the provided format definitions
4. **Documentation**: Reference the presentation and infographic for detailed findings

### Running Specific Tests

```bash
# Example: Run AP duplicate detection
Open: AP02_Duplicate_Invoices_Or_Payments.pro

# Example: Analyze receivables aging
Open: AR04_Aged_Receivables_Analysis.pro

# Example: Fixed asset depreciation verification
Open: SmartApps_FA_Header_.pro
```

## 📈 Audit Results Dashboard

View the interactive audit results in `infografis prakdit.html` which provides:
- Real-time data integrity status
- Visual risk assessment charts
- Detailed finding explanations
- Compliance status indicators

## 🔧 File Formats

- **`.fmt`** - Arbutus format definition files
- **`.fil`** - Arbutus data files
- **`.avw`** - Arbutus analysis view files
- **`.pro`** - Arbutus SmartApp procedure files

## 📝 Compliance & Standards

This audit framework follows:
- Indonesian Financial Accounting Standards
- Internal audit best practices
- Risk-based audit methodology
- Data analytics audit techniques

## 🤝 Contributing

When contributing to this audit framework:
1. Ensure all procedures are tested with sample data
2. Document any new SmartApps thoroughly
3. Update the infographic with new findings
4. Maintain consistency with existing naming conventions

## 📞 Support

For questions regarding:
- Arbutus Analyzer usage
- Audit procedure interpretation  
- Data format requirements
- Finding explanations

Please refer to the presentation slides or contact the audit team.

## ⚖️ License

This audit framework is proprietary and intended for authorized audit use only.

---

**Last Updated**: 2024
**Audit Period**: 2021 Financial Year
**Tool Version**: Arbutus Analyzer
