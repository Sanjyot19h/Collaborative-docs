# 🤝 Contributing Guide

Thank you for contributing to Collaborative Docs!

## Workflow

### 1. Create an Issue
- Go to the **Issues** tab
- Click **New Issue**
- Fill in the template

### 2. Create a Branch
```bash
git checkout -b docs/your-topic-name
```

### 3. Make Your Changes
- Edit files inside the `docs/` folder
- Use proper Markdown formatting

### 4. Commit and Push
```bash
git add .
git commit -m "docs: describe your change - fixes #ISSUE_NUMBER"
git push origin docs/your-topic-name
```

### 5. Open a Pull Request
- Go to GitHub and click **Compare & Pull Request**
- Fill in the description
- Link the issue number

### 6. Wait for Review
- A maintainer will review your PR
- Make changes if requested
- Once approved it will be merged ✅

## Commit Message Format
| Prefix | Use For |
|--------|---------|
| `docs:` | Adding or updating documentation |
| `fix:` | Fixing a typo or broken content |
| `feat:` | Adding a new doc page |
| `chore:` | Maintenance tasks |