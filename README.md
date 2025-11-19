# WCAG Playground

A comprehensive learning and development repository for enhancing web accessibility following Web Content Accessibility Guidelines (WCAG) standards. This project progresses from fundamental accessibility concepts to advanced implementations using React with comprehensive unit testing.

## 🎯 Project Goal

To build a practical, code-focused learning environment implementing accessibility best practices across web applications, from basic HTML/CSS to sophisticated React components with full test coverage.

## 📚 Project Structure

```
wcag-playground/
├── fundamentals/                 # Basic accessibility concepts
│   ├── html-semantics/          # Semantic HTML structure
│   │   ├── index.html
│   │   ├── styles.css
│   │   └── test.js
│   ├── aria-basics/             # ARIA fundamentals
│   │   ├── index.html
│   │   ├── script.js
│   │   └── test.js
│   ├── keyboard-navigation/     # Keyboard accessibility
│   │   ├── index.html
│   │   ├── script.js
│   │   └── test.js
│   ├── color-contrast/          # Color and contrast guidelines
│   │   ├── index.html
│   │   ├── styles.css
│   │   └── test.js
│   ├── focus-management/        # Focus indicators and management
│   │   ├── index.html
│   │   ├── script.js
│   │   └── test.js
│   └── form-accessibility/      # Accessible form elements
│       ├── index.html
│       ├── script.js
│       └── test.js
├── advanced/                     # Advanced accessibility patterns
│   ├── react-components/        # Accessible React components
│   │   ├── Button/
│   │   │   ├── Button.jsx
│   │   │   ├── Button.css
│   │   │   └── Button.test.jsx
│   │   ├── Form/
│   │   │   ├── Form.jsx
│   │   │   ├── Form.css
│   │   │   └── Form.test.jsx
│   │   ├── Modal/
│   │   │   ├── Modal.jsx
│   │   │   ├── Modal.css
│   │   │   └── Modal.test.jsx
│   │   ├── Navigation/
│   │   │   ├── Navigation.jsx
│   │   │   ├── Navigation.css
│   │   │   └── Navigation.test.jsx
│   │   ├── Dropdown/
│   │   │   ├── Dropdown.jsx
│   │   │   ├── Dropdown.css
│   │   │   └── Dropdown.test.jsx
│   │   ├── Table/
│   │   │   ├── Table.jsx
│   │   │   ├── Table.css
│   │   │   └── Table.test.jsx
│   │   ├── Carousel/
│   │   │   ├── Carousel.jsx
│   │   │   ├── Carousel.css
│   │   │   └── Carousel.test.jsx
│   │   ├── Tabs/
│   │   │   ├── Tabs.jsx
│   │   │   ├── Tabs.css
│   │   │   └── Tabs.test.jsx
│   │   ├── Tooltip/
│   │   │   ├── Tooltip.jsx
│   │   │   ├── Tooltip.css
│   │   │   └── Tooltip.test.jsx
│   │   └── Alert/
│   │       ├── Alert.jsx
│   │       ├── Alert.css
│   │       └── Alert.test.jsx
│   ├── hooks/                   # Custom React hooks for accessibility
│   │   ├── useKeyboardNavigation.js
│   │   ├── useKeyboardNavigation.test.js
│   │   ├── useFocusTrap.js
│   │   ├── useFocusTrap.test.js
│   │   ├── useAriaLiveRegion.js
│   │   └── useAriaLiveRegion.test.js
│   ├── aria-patterns/           # Complex ARIA patterns
│   │   ├── ComboBox.jsx
│   │   ├── ComboBox.test.jsx
│   │   ├── Menu.jsx
│   │   ├── Menu.test.jsx
│   │   ├── Listbox.jsx
│   │   └── Listbox.test.jsx
│   └── state-management/        # Accessible state handling
│       ├── accessibilityContext.js
│       ├── accessibilityContext.test.js
│       └── hooks.js
├── tests/                        # Test configuration and utilities
│   ├── setup.js
│   ├── testUtils.js
│   └── fixtures/
│       ├── mockData.js
│       └── mockScreenReader.js
├── config/                       # Configuration files
│   ├── jest.config.js
│   ├── jest-axe.setup.js
│   ├── .eslintrc.js
│   └── .eslintignore
├── examples/                     # Working examples and demos
│   ├── AccessibleForm.jsx
│   ├── AccessibleNavigation.jsx
│   ├── AccessibleDashboard.jsx
│   ├── AccessibleTable.jsx
│   └── ComplexWidget.jsx
├── package.json
├── .gitignore
└── README.md
```

## 🏗️ Learning Levels

### Level 1: Fundamentals
Introduction to web accessibility principles using vanilla HTML, CSS, and JavaScript:
- **HTML Semantics**: Proper use of heading hierarchy, lists, and structural elements
- **ARIA Basics**: Introduction to ARIA attributes and roles
- **Keyboard Navigation**: Implementing focus management and keyboard shortcuts
- **Color & Contrast**: WCAG color contrast ratio requirements
- **Focus Management**: Managing focus indicators and tab order
- **Form Accessibility**: Accessible form controls, validation, and error messages

### Level 2: Intermediate
Building on fundamentals with more complex scenarios (vanilla JS):
- Advanced form patterns and validation
- Navigation patterns (menus, breadcrumbs, pagination)
- Data tables with accessibility
- Images, icons, and media accessibility
- Animations and prefers-reduced-motion support
- Dynamic content updates

### Level 3: Advanced
Professional-grade accessibility implementations using React:
- Fully accessible React components
- Custom React hooks for accessibility patterns
- Complex ARIA patterns (combobox, menu, listbox)
- Live regions and dynamic announcements
- Focus management and focus trap patterns
- State management for accessible features
- Comprehensive unit tests with jest-axe
- Production-ready component library

## 🛠️ Technologies & Tools

### Development
- HTML5 & CSS3
- JavaScript (ES6+)
- React 18+

### Testing & Quality Assurance
- Jest - Unit testing framework
- React Testing Library - Component testing
- jest-axe - Accessibility testing
- @testing-library/jest-dom - DOM matchers

### Code Quality
- ESLint with jsx-a11y plugin
- Prettier - Code formatting

## 🧪 Testing Strategy

### Unit Tests
- Component rendering and behavior
- Keyboard interaction handling
- Focus management verification
- ARIA attribute correctness
- Event handler functionality

### Accessibility Tests
- jest-axe automated scans
- ARIA attribute validation
- Keyboard navigation path verification
- Component interaction patterns

### Test Coverage
- Minimum 80% code coverage
- 100% coverage for accessibility-critical paths
- Screen reader compatibility verification

## 💻 Implementation Approach

Each section follows a consistent pattern:

1. **Vanilla Implementation First**: Start with HTML/CSS/JS in fundamentals
2. **Code Comments**: Inline comments explaining accessibility decisions
3. **Comprehensive Tests**: Unit and accessibility tests for each feature
4. **Real-world Examples**: Working examples in the examples folder
5. **Progressive Enhancement**: Build from simple to complex patterns

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Run all tests
npm test

# Run tests in watch mode
npm test -- --watch

# Run accessibility tests
npm test -- --grep="accessibility"

# Run specific fundamentals tests
npm test -- fundamentals/

# Run specific advanced component tests
npm test -- advanced/react-components/
```

## 📝 Development Guidelines

### Semantic HTML
- Use appropriate semantic elements (nav, main, article, aside, section, etc.)
- Maintain proper heading hierarchy (h1 → h6)
- Use landmark regions correctly

### ARIA Usage
- Semantic HTML first, ARIA as enhancement
- Test ARIA attributes with jest-axe
- Maintain proper ARIA role, state, and property hierarchy

### React Best Practices
- Use ref forwarding for focus management
- Implement keyboard event handlers properly
- Update ARIA live regions for dynamic content
- Use custom hooks for common accessibility patterns
- Forward component props for flexibility

### Testing
- Every accessibility feature must have a test
- Test keyboard navigation paths
- Verify ARIA attributes in tests
- Use testing-library queries for accessible element selection
- Include jest-axe checks in component tests

## 🔄 Component Development Checklist

- [ ] Component renders correctly
- [ ] All ARIA attributes applied correctly
- [ ] Keyboard navigation fully functional (Tab, Enter, Escape, Arrow keys)
- [ ] Focus management working properly
- [ ] Focus indicators visible
- [ ] Color contrast meets WCAG AA standards
- [ ] Unit tests passing (80%+ coverage)
- [ ] jest-axe accessibility audit passing
- [ ] No eslint-plugin-jsx-a11y violations
- [ ] Tested with screen reader (NVDA or VoiceOver)

## 📦 Available Scripts

```bash
npm test              # Run all tests
npm test -- --watch  # Watch mode
npm test -- --coverage # Coverage report
npm run lint         # ESLint check
npm run lint:fix     # Fix ESLint issues
```

## 🎯 WCAG Compliance Levels

- **Level A**: Basic accessibility features (fundamentals)
- **Level AA**: Enhanced accessibility (most fundamentals + some advanced)
- **Level AAA**: Specialized accessibility features (advanced components)

## 📋 Project Phases

### Phase 1: Fundamentals
- [ ] HTML semantics
- [ ] ARIA basics
- [ ] Keyboard navigation
- [ ] Color contrast
- [ ] Focus management
- [ ] Form accessibility

### Phase 2: Advanced Components
- [ ] Buttons
- [ ] Forms
- [ ] Modals
- [ ] Navigation
- [ ] Tables
- [ ] Dropdowns
- [ ] Carousels
- [ ] Tabs
- [ ] Tooltips
- [ ] Alerts

### Phase 3: Advanced Patterns
- [ ] Custom hooks
- [ ] ARIA patterns (combobox, menu, listbox)
- [ ] State management
- [ ] Complex interactions

## 📄 License

This project is provided as an educational resource.

---

**Maintained with ♿ for accessibility**