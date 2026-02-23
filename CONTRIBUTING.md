# Contributing to @barrys27/ui

First off, thank you for considering contributing to `@barrys27/ui`! It's people like you who make the open-source community such an amazing place to learn, inspire, and create.

## Code of Conduct
By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How Can I Contribute?

### Reporting Bugs
* Check the [Issues tab](https://github.com/BarryS27/ui/issues) to see if the bug has already been reported.
* If not, open a new issue. Include a clear title, a description of the problem, and steps to reproduce the issue. 
* Mention your browser and environment (e.g., Chrome 120 on macOS).

### Suggesting Enhancements
* We are always looking for new atomic components or utility improvements.
* Please ensure your suggestions align with our **Design Philosophy** (see below).
* Open an issue with the tag `enhancement` to start a discussion.

### Pull Requests
1. Fork the repository and create your branch from `main`.
2. If you add a new component or utility class, please add a corresponding HTML example in the demo/docs file to verify its visual layout and behavior.
3. Ensure your code follows the existing style and design rules.
4. Issue a Pull Request (PR) with a descriptive title and link to any related issues.

## Design Philosophy & Guidelines

To maintain the "clarity and order" of this library, all contributions must follow these core principles:

1. **The 8-Point Grid**: Static spacing (margins, padding) should follow the 8-point system (8, 16, 24...). For fluid layouts, use `clamp()` functions where the `min` and `max` values strictly adhere to the 8-point scale.
2. **Glassmorphism**: Component containers should utilize frosted-glass effects where appropriate to maintain a modern, layered aesthetic.
3. **Zero-JS Motion**: Animations must be implemented using pure CSS. We strongly encourage utilizing modern CSS features like CSS Transitions, Transforms, and Scroll-driven Animations (`animation-timeline`) instead of JavaScript.
4. **Scss Best Practices**: Use `@use` for modularity. Keep utility classes descriptive and atomic.

## Development Setup

1. Clone your fork: `git clone https://github.com/<your-username>/ui.git`
2. Install dependencies: `npm install`
3. Make your changes in the `src/scss` directory.
4. Run `npm run watch` to automatically compile SCSS to CSS as you code.
5. Build the CSS: `npm run build` (or your specific build script).

## Questions?
Feel free to open an issue for any questions or reach out to the maintainer. Happy coding!