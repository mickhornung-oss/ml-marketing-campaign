# Contributing Guidelines

Thank you for your interest in contributing to ml-marketing-campaign! This document provides guidelines and instructions for contributing to this project.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- pandas, scikit-learn, matplotlib

### Local Setup
1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/ml-marketing-campaign.git`
3. Navigate to the project: `cd ml-marketing-campaign`
4. Create a virtual environment: `python -m venv .venv`
5. Activate it: `.\.venv\Scripts\Activate.ps1` (Windows) or `source .venv/bin/activate` (Linux/Mac)
6. Install dependencies: `pip install -r requirements.txt`

## Development Workflow

### Creating a Feature Branch
```bash
git checkout -b feature/your-feature-name
```

### Code Guidelines
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for Python code
- Use meaningful variable and function names
- Add docstrings to functions and classes
- Keep notebooks organized with clear section headers

### Testing Your Changes
- Test your ML models locally before submitting
- Ensure data preprocessing doesn't break existing workflows
- Validate predictions against baseline metrics

## Submitting Changes

### Commit Messages
- Use clear, descriptive commit messages
- Format: `type: brief description`
- Examples: `feat: add churn model`, `fix: data preprocessing bug`, `docs: update README`

### Pull Request Process
1. Push your changes to your fork
2. Open a Pull Request with:
   - Clear title describing the change
   - Description of what was changed and why
   - Reference to any related issues
   - Proof of testing (screenshots, metrics, etc.)

3. Wait for review and address any feedback

## Areas for Contribution

### Analysis
- Exploratory Data Analysis improvements
- New feature engineering techniques
- Statistical insights

### Models
- Algorithm alternatives (XGBoost, LightGBM, etc.)
- Cross-validation strategy enhancements
- Performance optimization

### Documentation
- Clarify ambiguous sections
- Add more examples
- Improve visualizations

## Questions?

Feel free to:
- Open an Issue for bugs or feature requests
- Discuss ideas in Discussions (if enabled)
- Email the maintainer: [mick.hornung@googlemail.com](mailto:mick.hornung@googlemail.com)

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Happy Contributing!** 🚀
