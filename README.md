# NPM Library Boilerplate

[![Build Status](https://github.com/efetoker/npm-library-boilerplate/actions/workflows/ci.yml/badge.svg)](https://github.com/efetoker/npm-library-boilerplate/actions/workflows/ci.yml)
[![GitHub license](https://img.shields.io/github/license/efetoker/npm-library-boilerplate)](https://github.com/efetoker/npm-library-boilerplate/blob/main/LICENSE)
[![Code Style: Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)

A professional boilerplate for creating modern NPM libraries with TypeScript.

## ✨ Features

- **TypeScript**: Type-safe code.
- **Jest**: Robust testing.
- **ESLint & Prettier**: Enforced code quality and style.
- **tsup**: Fast bundling for CJS and ESM formats.
- **GitHub Actions**: CI workflow for automated testing and building.

## 🚀 Getting Started

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/efetoker/npm-library-boilerplate.git my-new-library
    cd my-new-library
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

## 🛠️ Usage

### Development

- Run the builder in watch mode: `npm run dev`
- Run tests: `npm test`
- Run linter: `npm run lint`
- Build for production: `npm run build`

## 📦 Publishing

The `prepublishOnly` script will automatically run tests, lint, and build the project before publishing.

```bash
npm publish
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https.github.com/efetoker/npm-library-boilerplate/issues).

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💖 Code of Conduct

We are committed to providing a welcoming and inclusive environment for everyone. Please see our [Code of Conduct](CODE_OF_CONDUCT.md) for more information.
