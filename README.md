# cursor-documents

A Node.js project built with TypeScript.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Runtime | Node.js |
| Language | TypeScript |
| Package Manager | npm |
| Build | `tsc` (TypeScript Compiler) |
| Dev Runner | `tsx` or `ts-node` |
| Linting | ESLint |
| Formatting | Prettier |
| Environment | [dotenv](https://github.com/motdotla/dotenv) |

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm

## Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd cursor-documents
```

### 2. Install dependencies

```bash
npm install
```

### 3. Environment variables

Create a `.env` file in the project root:

```env
# Add your environment variables here
```

### 4. Run the project

```bash
# Development (with hot reload)
npm run dev

# Build for production
npm run build

# Run compiled output
npm start
```

## Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Compile TypeScript to JavaScript |
| `npm start` | Run the compiled application |
| `npm run lint` | Lint TypeScript source files |
| `npm run format` | Format code with Prettier |
| `npm test` | Run tests |

> **Note:** Some scripts are planned as the TypeScript setup is completed. See `cursor.md` for project conventions and roadmap.

## Project Structure

```
cursor-documents/
├── src/              # TypeScript source code
│   └── index.ts      # Entry point
├── dist/             # Compiled JavaScript (build output)
├── package.json
├── tsconfig.json
├── .eslintrc.json
├── .prettierrc
├── cursor.md         # Cursor AI project guide
└── README.md
```

## License

ISC
