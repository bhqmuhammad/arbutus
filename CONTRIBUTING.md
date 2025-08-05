# Contributing to Arbutus Financial Audit Tools

Thank you for your interest in contributing to the Arbutus Financial Audit Tools repository! This project provides comprehensive financial audit procedures and analysis tools for conducting detailed financial audits.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Contribution Guidelines](#contribution-guidelines)
- [Reporting Issues](#reporting-issues)
- [Submitting Changes](#submitting-changes)
- [Style Guidelines](#style-guidelines)
- [Community and Support](#community-and-support)

## 🤝 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🚀 How to Contribute

There are many ways to contribute to this project:

### 🐛 Reporting Bugs
- Use the GitHub issue tracker to report bugs
- Check if the issue already exists before creating a new one
- Provide detailed information about the bug and steps to reproduce

### 💡 Suggesting Enhancements
- Use GitHub issues to suggest new features or improvements
- Clearly describe the enhancement and its potential benefits
- Consider the scope and complexity of the proposed change

### 📖 Improving Documentation
- Help improve README files, code comments, and documentation
- Fix typos, improve clarity, or add missing information
- Update outdated information or broken links

### 🔧 Contributing Code
- Submit bug fixes, new features, or improvements
- Follow the established coding standards and guidelines
- Ensure your changes don't break existing functionality

## 🛠️ Development Setup

### Prerequisites

Before contributing, ensure you have:

- **Arbutus Analyzer Software**: Required for working with `.fil`, `.fmt`, and `.pro` files
- **ATLAS Audit Software**: Optional, for advanced audit procedures
- **Microsoft Excel**: For viewing and editing `.xlsx` data files
- **Archive Tools**: For extracting `.rar` and `.zip` files
- **Git**: For version control

### Getting Started

1. **Fork the Repository**
   ```bash
   # Fork the repository on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/arbutus.git
   cd arbutus
   ```

2. **Set Up Remote**
   ```bash
   # Add the original repository as upstream
   git remote add upstream https://github.com/bhqmuhammad/arbutus.git
   ```

3. **Extract Sample Data** (Optional)
   ```bash
   # Extract archives for testing (if needed)
   unzip "Arbutus.zip"
   unrar x "Atlas.rar"
   unzip "Realsa Data.zip"
   ```

## 📝 Contribution Guidelines

### 🎯 Focus Areas

When contributing, focus on these priority areas:

1. **Audit Procedures**: Improve existing SmartApps or create new ones
2. **Data Quality**: Enhance data validation and integrity checks
3. **Documentation**: Improve clarity and completeness
4. **Training Materials**: Add examples and tutorials
5. **Error Detection**: Enhance fraud detection capabilities

### 📁 File Organization

- **`/Arbutus/`**: Core Arbutus Analyzer files (`.fil`, `.fmt`, `.avw`)
- **`/Prakdit/SmartApps/`**: Automated audit procedures
- **`/Data Files/`**: Excel data files for analysis
- **`/Training/`**: ATLAS software and training materials
- **Root**: Documentation and result files

### 🔍 Audit Procedure Standards

When adding or modifying audit procedures:

1. **Naming Convention**: Use descriptive names following the pattern:
   - `MODULE##_Description_Of_Procedure.pro`
   - Example: `AP05_Transactions_Posted_On_Weekends_And_Holidays.pro`

2. **Documentation**: Include:
   - Purpose and scope of the procedure
   - Input data requirements
   - Expected output format
   - Risk level and materiality thresholds

3. **Testing**: Ensure procedures work with sample data
4. **Error Handling**: Include appropriate error checking and validation

### 📊 Data File Standards

When adding or modifying data files:

1. **Format Consistency**: Maintain consistent field names and formats
2. **Data Privacy**: Ensure all data is anonymized and non-sensitive
3. **Documentation**: Document data structure and field definitions
4. **Validation**: Include data integrity checks

## 🐛 Reporting Issues

When reporting issues, please include:

### 🔍 Bug Reports
- **Environment**: Arbutus version, OS, Excel version
- **Steps to Reproduce**: Detailed steps to recreate the issue
- **Expected Behavior**: What should happen
- **Actual Behavior**: What actually happens
- **Screenshots**: If applicable
- **Data Files**: Relevant sample data (anonymized)

### 💡 Feature Requests
- **Use Case**: Why is this feature needed?
- **Proposed Solution**: How should it work?
- **Alternatives**: Other solutions considered
- **Impact**: Who would benefit from this feature?

## 📤 Submitting Changes

### 🔄 Pull Request Process

1. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b bugfix/issue-description
   ```

2. **Make Changes**
   - Follow the coding standards
   - Test your changes thoroughly
   - Update documentation as needed

3. **Commit Changes**
   ```bash
   git add .
   git commit -m "Brief description of changes"
   ```

4. **Update Your Fork**
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

5. **Push and Create PR**
   ```bash
   git push origin your-branch-name
   # Create pull request on GitHub
   ```

### ✅ Pull Request Checklist

Before submitting, ensure:

- [ ] Code follows project style guidelines
- [ ] Changes are tested with sample data
- [ ] Documentation is updated (if applicable)
- [ ] Commit messages are clear and descriptive
- [ ] No sensitive data is included
- [ ] Files are properly formatted and named
- [ ] Large binary files are appropriately handled

## 🎨 Style Guidelines

### 📄 Documentation
- Use clear, concise language
- Include examples where helpful
- Follow Markdown best practices
- Keep line length reasonable (80-100 characters)

### 📊 Data Files
- Use consistent field naming (PascalCase or snake_case)
- Include proper headers and metadata
- Ensure data is anonymized
- Document any calculations or formulas

### 🔧 Arbutus Procedures
- Follow Arbutus scripting conventions
- Include error handling and validation
- Use meaningful variable names
- Add comments for complex logic

### 📁 File Naming
- Use descriptive, consistent names
- Avoid spaces and special characters
- Include version numbers when appropriate
- Follow existing naming patterns

## 🆘 Getting Help

### 📞 Support Channels

- **GitHub Issues**: For bugs and feature requests
- **GitHub Discussions**: For questions and general discussion
- **Email**: Contact the maintainer for sensitive issues

### 📚 Resources

- [Arbutus Analyzer Documentation](https://www.arbutussoftware.com/)
- [ATLAS Audit Software Guide](training materials in repository)
- [Financial Audit Best Practices](relevant industry resources)

### 🤔 Questions?

If you have questions about:
- **Technical Issues**: Create a GitHub issue
- **Contribution Process**: Check this guide or ask in discussions
- **Audit Procedures**: Refer to existing documentation or ask for guidance

## 🏆 Recognition

Contributors will be recognized in:
- Repository contributors list
- Release notes (for significant contributions)
- Documentation credits
- Community acknowledgments

## 📜 License

By contributing to this project, you agree that your contributions will be licensed under the same [MIT License](LICENSE) that covers the project.

---

**Thank you for contributing to Arbutus Financial Audit Tools!** 🎉

Your contributions help improve financial audit processes and support the auditing community worldwide.

For more information, visit the [project repository](https://github.com/bhqmuhammad/arbutus) or contact the maintainer [@bhqmuhammad](https://github.com/bhqmuhammad).