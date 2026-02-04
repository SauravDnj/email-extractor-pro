# Contributing to Email Extractor Pro

First off, thank you for considering contributing to Email Extractor Pro! 🎉

## 📋 Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)

## 🤝 Code of Conduct

### Our Pledge
We are committed to providing a welcoming and inspiring community for all.

### Our Standards
- ✅ Be respectful and inclusive
- ✅ Welcome newcomers and help them learn
- ✅ Focus on what is best for the community
- ✅ Show empathy towards others

## 🚀 How Can I Contribute?

### Reporting Bugs 🐛
Before creating bug reports, please check existing issues. When creating a bug report, include:

- **Clear title** - Descriptive and specific
- **Steps to reproduce** - Detailed steps to reproduce the issue
- **Expected behavior** - What you expected to happen
- **Actual behavior** - What actually happened
- **Screenshots** - If applicable
- **Environment** - Browser version, OS, etc.

**Example:**
```
Title: PDF extraction fails with scanned documents

Description:
When uploading a scanned PDF (image-based), the extractor 
shows "0 emails found" even though emails are visible.

Steps to reproduce:
1. Upload scanned_invoice.pdf
2. Click "Extract Emails"
3. See "0 emails found"

Expected: Should detect emails or show OCR suggestion
Actual: Shows 0 emails with no helpful message

Environment: Chrome 120, Windows 11
```

### Suggesting Features 💡
Feature requests are welcome! Include:

- **Clear description** - What feature you want
- **Motivation** - Why this feature would be useful
- **Examples** - How it would work
- **Alternatives** - Other solutions you considered

### Code Contributions 👨‍💻

#### Types of Contributions Welcome:
- 🐛 Bug fixes
- ✨ New features
- 📝 Documentation improvements
- 🎨 UI/UX enhancements
- ⚡ Performance improvements
- 🌐 Translations
- ✅ Tests

## 💻 Development Setup

### Prerequisites
- Git
- Python 3.7+ (for Python scripts)
- Modern web browser (for testing web interfaces)
- Text editor or IDE

### Getting Started

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/email-extractor-pro.git
   cd email-extractor-pro
   ```

3. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

4. **Install dependencies (if working on Python)**
   ```bash
   pip install -r requirements.txt
   ```

5. **Make your changes**
   - Edit the files
   - Test thoroughly
   - Follow style guidelines

6. **Test your changes**
   - Test web interfaces in multiple browsers
   - Test Python scripts with different inputs
   - Ensure no breaking changes

## 📤 Pull Request Process

### Before Submitting
- [ ] Code follows project style guidelines
- [ ] Self-review of code completed
- [ ] Comments added for complex code
- [ ] Documentation updated if needed
- [ ] No new warnings generated
- [ ] Tested in multiple browsers (for web)

### Submitting

1. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add: brief description of your changes"
   ```

2. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Open a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your fork and branch
   - Fill in the PR template

### PR Title Format
```
Type: Brief description

Types:
- Add: New feature
- Fix: Bug fix
- Update: Improvement to existing feature
- Docs: Documentation changes
- Style: Code style/formatting
- Refactor: Code restructuring
- Test: Adding tests
- Chore: Maintenance tasks
```

**Examples:**
- `Add: Dark mode toggle for web interface`
- `Fix: PDF extraction fails on large files`
- `Update: Improve Excel export formatting`
- `Docs: Add installation guide for Windows`

### PR Description Template
```markdown
## Description
Brief description of what this PR does

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement
- [ ] Other (specify)

## Changes Made
- Change 1
- Change 2
- Change 3

## Testing Done
- [ ] Tested in Chrome
- [ ] Tested in Firefox
- [ ] Tested Python script
- [ ] Added/updated tests

## Screenshots (if applicable)
[Add screenshots here]

## Additional Notes
Any additional context or notes
```

## 🎨 Style Guidelines

### JavaScript/HTML/CSS

#### JavaScript
```javascript
// Use camelCase for variables and functions
const emailList = [];
function extractEmails() { }

// Use const for constants
const MAX_EMAILS = 200;

// Add comments for complex logic
// Calculate available emails by excluding history
const available = allEmails.filter(email => !previouslySelected.has(email));

// Use template literals
const message = `Found ${count} emails`;
```

#### HTML
```html
<!-- Use semantic HTML5 -->
<section class="email-list">
  <header>
    <h2>Email Results</h2>
  </header>
</section>

<!-- Descriptive class names -->
<div class="stat-box">
  <div class="stat-number">200</div>
</div>
```

#### CSS
```css
/* Use meaningful class names */
.btn-primary { }
.stat-box { }

/* Group related styles */
.card {
  background: white;
  border-radius: 15px;
  padding: 30px;
}

/* Use CSS custom properties for colors */
:root {
  --primary-color: #667eea;
  --success-color: #28a745;
}
```

### Python

```python
# Follow PEP 8 style guide
# Use snake_case for functions and variables
def extract_emails(text):
    email_list = []
    return email_list

# Use docstrings
def select_random_emails(count=200):
    """
    Randomly select specified number of emails.
    
    Args:
        count (int): Number of emails to select
        
    Returns:
        list: Selected email addresses
    """
    pass

# Use type hints where helpful
def process_pdf(file_path: str) -> List[str]:
    pass
```

### Git Commit Messages

```
Type: Brief description (50 chars or less)

More detailed explanation if needed (wrap at 72 chars).
Explain what and why, not how.

Types:
- Add: New feature or capability
- Fix: Bug fix
- Update: Improvement to existing feature
- Docs: Documentation only changes
- Style: Formatting, missing semicolons, etc.
- Refactor: Code restructuring
- Test: Adding tests
- Chore: Maintenance tasks
```

**Good Examples:**
```
Add: Dark mode support for all web interfaces
Fix: PDF extraction hanging on large files
Update: Improve email validation regex pattern
Docs: Add troubleshooting section to README
```

**Bad Examples:**
```
fixed stuff
update
asdfasdf
WIP
```

## 🧪 Testing Guidelines

### Manual Testing
When testing your changes:

1. **Web Interfaces**
   - Test in Chrome, Firefox, Safari, Edge
   - Test on mobile browsers
   - Test with different file sizes
   - Test error conditions

2. **Python Scripts**
   - Test with various PDF formats
   - Test with large files
   - Test edge cases (0 emails, 1 email, 500 emails)
   - Test error handling

3. **Cross-browser Testing**
   - Check all features work
   - Verify styling is consistent
   - Test file downloads
   - Test localStorage

### Test Cases to Cover
- [ ] Upload valid PDF
- [ ] Upload invalid file
- [ ] Extract emails successfully
- [ ] Handle 0 emails found
- [ ] Select random 200
- [ ] Export to Excel
- [ ] History tracking works
- [ ] Reset history works
- [ ] Copy to clipboard
- [ ] Mobile responsiveness

## 📚 Documentation

### When to Update Documentation
Update documentation when you:
- Add a new feature
- Change existing functionality
- Fix a bug that affects usage
- Add new dependencies
- Change configuration

### Documentation Files
- `README.md` - Main documentation
- `PDF_EXTRACTOR_GUIDE.txt` - PDF extractor guide
- Code comments - For complex logic
- Docstrings - For Python functions

## ❓ Questions?

If you have questions:
1. Check existing documentation
2. Search existing issues
3. Open a new issue with the "question" label

## 🎉 Recognition

Contributors will be:
- Listed in the README
- Mentioned in release notes
- Thanked in commit messages

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to Email Extractor Pro! 🚀

Your contributions help make this project better for everyone.
