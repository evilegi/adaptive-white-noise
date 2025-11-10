# Contributing to Adaptive White Noise

Thank you for your interest in contributing! This project is designed as a single-file HTML application for maximum simplicity and portability.

## How to Contribute

### Reporting Bugs 🐛

1. Check if the bug has already been reported in Issues
2. If not, create a new issue with:
   - Clear, descriptive title
   - Steps to reproduce the bug
   - Expected vs actual behavior
   - Browser and OS information
   - Screenshots if applicable

### Suggesting Features 💡

1. Check existing issues to avoid duplicates
2. Create a new issue describing:
   - The feature and its use case
   - Why it would be valuable
   - How it might work (optional)

### Submitting Changes 🔧

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**
   - Keep the single-file structure intact
   - Test thoroughly in multiple browsers
   - Ensure offline functionality is maintained
   - Comment complex code sections
4. **Test your changes**
   - Chrome/Edge
   - Firefox
   - Safari (if available)
   - Mobile browsers
5. **Commit your changes**
   ```bash
   git commit -m "Add feature: brief description"
   ```
6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Create a Pull Request**
   - Provide clear description of changes
   - Link any related issues
   - Include before/after screenshots if UI changed

## Code Style Guidelines

### JavaScript
- Use clear, descriptive variable names
- Add comments for complex logic
- Keep functions focused and manageable
- Use ES6+ features where appropriate
- Maintain consistent indentation (4 spaces)

### HTML/CSS
- Semantic HTML structure
- Inline styles are acceptable for this single-file app
- Keep CSS organized by component
- Use CSS custom properties for theming

### Testing Checklist
Before submitting a PR, verify:
- [ ] Works in Chrome/Edge
- [ ] Works in Firefox
- [ ] Works in Safari (if available)
- [ ] Works on mobile browsers
- [ ] Offline functionality intact
- [ ] Settings persist after page reload
- [ ] No console errors
- [ ] Microphone permissions handled gracefully
- [ ] Sleep timer functions correctly
- [ ] All fade features work as expected

## Architecture Notes

This is intentionally a **single-file application** because:
- Easy to download and use offline
- No build process or dependencies
- Simple deployment (just host the HTML file)
- Maximum portability

If proposing changes that would split the file, please discuss in an issue first.

## Questions?

Feel free to open an issue with the "question" label!

Thank you for contributing! 🎉
