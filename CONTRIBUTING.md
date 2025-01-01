# Contributing to Our Organization

Welcome to our organization! This guide will help you understand how to contribute to any of our repositories. We value every contribution and want to make your experience as smooth as possible.

## Our Values

- We believe in open source and giving back to the community
- We welcome contributors of all experience levels
- We value clear communication and documentation
- We support learning and mentorship

## Getting Started with Our Organization

1. Browse our repositories to find projects that interest you
2. Read the project-specific README.md file
3. Look for issues labeled `good-first-issue` or `help-wanted`
4. Join our community channels (if available) to connect with other contributors

## Organization-Wide Guidelines

### Git Workflow

1. **Fork & Clone**
   - Fork the repository you want to contribute to
   - Clone your fork locally
   ```bash
   git clone https://github.com/YOUR-USERNAME/repository-name
   ```

2. **Branching Strategy**
   We use the following branch naming convention:
   ```
   type/description-in-kebab-case
   ```
   Types:
   - `feature/` - New features
   - `fix/` - Bug fixes
   - `docs/` - Documentation updates
   - `refactor/` - Code refactoring
   - `test/` - Test additions or updates

### Commit Standards

We follow conventional commits across all our projects:

```
type(scope): brief description

[optional body]

[optional footer]
```

Examples:
```
feat(auth): implement SSO login
fix(ui): correct button alignment
docs(readme): update installation steps
```

Common types:
- `feat` - New features
- `fix` - Bug fixes
- `docs` - Documentation changes
- `style` - Formatting changes
- `refactor` - Code restructuring
- `test` - Adding/updating tests
- `chore` - Maintenance tasks

### Pull Request Process

1. **Before Creating a PR**
   - Ensure your code follows our style guidelines
   - Update relevant documentation
   - Add/update tests if needed
   - Run all tests locally

2. **PR Title Format**
   ```
   type: brief description of changes
   ```

3. **PR Description Template**
   ```markdown
   ## Description
   [Describe your changes]

   ## Type of Change
   - [ ] Bug fix
   - [ ] New feature
   - [ ] Documentation update
   - [ ] Code refactoring
   - [ ] Other (please specify)

   ## Related Issues
   Fixes #[issue number]

   ## Testing
   [Describe how you tested your changes]
   ```

4. **Review Process**
   - At least one maintainer must approve changes
   - Address review comments promptly
   - Keep discussions focused and professional

### Code Style

- Each project has its own `.editorconfig` file
- Follow the existing code style of the project
- Use meaningful variable and function names
- Comment complex logic
- Remove debugging code before committing

### Documentation

- Update README.md if you change functionality
- Add JSDoc comments for new functions
- Include code examples where helpful
- Write clear commit messages and PR descriptions

## Getting Help

- Check project-specific documentation
- Look for similar issues in the repository
- Ask in the PR or issue comments
- Contact repository maintainers

## Recognition

- Contributors are listed in our organization's hall of fame
- Significant contributors may be invited to become maintainers
- We regularly highlight valuable contributions in our community

## Code of Conduct

All contributors must follow our organization-wide [code of conduct](https://github.com/WnC-Club/.github/blob/main/CODE_OF_CONDUCT.md). This ensures a welcoming and inclusive environment for everyone.

## Project-Specific Guidelines

Individual projects may have additional requirements. Always check:
1. Project's README.md
2. Project-specific CONTRIBUTING.md (if exists)
3. Any setup scripts or documentation

---

Thank you for contributing to our organization! 🌟

Need help? Contact our maintainers or raise an issue.
