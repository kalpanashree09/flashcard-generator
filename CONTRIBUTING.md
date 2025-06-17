# Contributing to Flashcard Generator

Thank you for your interest in contributing to the Flashcard Generator! This document provides guidelines and information for contributors.

## 🚀 Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/yourusername/flashcard-generator.git
   cd flashcard-generator
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Start the development server**:
   ```bash
   npm run dev
   ```

## 🛠️ Development Workflow

### Branch Naming
- `feature/description` - for new features
- `fix/description` - for bug fixes
- `docs/description` - for documentation updates
- `refactor/description` - for code refactoring

### Commit Messages
Follow conventional commit format:
- `feat: add new flashcard generation algorithm`
- `fix: resolve export functionality bug`
- `docs: update README with deployment instructions`
- `style: improve card flip animation`

## 📝 Code Standards

### TypeScript
- Use strict TypeScript configuration
- Define interfaces for all props and data structures
- Avoid `any` types - use proper typing

### React Components
- Use functional components with hooks
- Keep components focused and single-purpose
- Extract reusable logic into custom hooks

### Styling
- Use Tailwind CSS classes
- Follow mobile-first responsive design
- Maintain consistent spacing using the 8px grid system

### File Organization
```
src/
├── components/     # Reusable UI components
├── utils/         # Utility functions and helpers
├── types/         # TypeScript type definitions
└── hooks/         # Custom React hooks (if needed)
```

## 🧪 Testing

Currently, the project doesn't have tests, but we welcome contributions to add:
- Unit tests for utility functions
- Component tests for React components
- Integration tests for user workflows

## 🎨 Design Guidelines

### Visual Design
- Follow the existing color scheme (blue/purple gradients)
- Maintain consistent spacing and typography
- Ensure proper contrast ratios for accessibility

### User Experience
- Keep interactions intuitive and responsive
- Provide clear feedback for user actions
- Handle error states gracefully

## 📋 Pull Request Process

1. **Create a feature branch** from `main`
2. **Make your changes** following the code standards
3. **Test your changes** thoroughly
4. **Update documentation** if needed
5. **Submit a pull request** with:
   - Clear description of changes
   - Screenshots for UI changes
   - Reference to related issues

### Pull Request Template
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement

## Testing
- [ ] Tested locally
- [ ] No console errors
- [ ] Responsive design verified

## Screenshots
(If applicable)
```

## 🐛 Bug Reports

When reporting bugs, please include:
- **Environment**: Browser, OS, device
- **Steps to reproduce**: Clear, numbered steps
- **Expected behavior**: What should happen
- **Actual behavior**: What actually happens
- **Screenshots**: If applicable

## 💡 Feature Requests

For new features, please:
- Check existing issues first
- Provide clear use case and rationale
- Consider implementation complexity
- Discuss with maintainers before starting work

## 📚 Areas for Contribution

We welcome contributions in these areas:

### High Priority
- **Real AI Integration**: Connect to actual AI APIs
- **PDF Processing**: Implement real PDF text extraction
- **Testing Suite**: Add comprehensive tests
- **Performance**: Optimize for large text inputs

### Medium Priority
- **Accessibility**: Improve keyboard navigation and screen reader support
- **Internationalization**: Add multi-language support
- **Themes**: Add dark mode and custom themes
- **Analytics**: Add usage tracking (privacy-focused)

### Low Priority
- **Advanced Export**: Add more export formats (Anki, Quizlet)
- **Study Modes**: Add spaced repetition algorithms
- **Collaboration**: Multi-user flashcard sharing
- **Mobile App**: React Native version

## 🤝 Community

- Be respectful and inclusive
- Help others learn and grow
- Share knowledge and best practices
- Provide constructive feedback

## 📞 Questions?

If you have questions about contributing:
- Open a GitHub issue with the `question` label
- Check existing issues and discussions
- Contact maintainers directly

Thank you for contributing to make studying more effective for everyone! 🎓