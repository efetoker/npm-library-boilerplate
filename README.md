# NPM Library Boilerplate

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
