# TypeScript Starter

A minimal and fast TypeScript project starter template using **SWC** for ultra-fast compilation and modern developer tooling.

## ✨ Features

- ⚡ Fast compilation with SWC
- 📦 CommonJS module system
- 🧩 Decorator support
- 🛣 Path aliasing (`@/*`)
- 🔁 Live reload in development
- 🧹 Prettier, ESLint, and lint-staged
- 🔒 Git hooks via Husky

## 🚀 Scripts

| Command             | Description                                 |
| ------------------- | ------------------------------------------- |
| `npm run build`     | Compile TypeScript using SWC                |
| `npm start`         | Run compiled JavaScript from `dist/main.js` |
| `npm run start:dev` | Watch and reload on changes (build + run)   |

## 📁 Project Structure

```text
├── src/ # Source code (entry point: main.ts)
├── dist/ # Compiled JS files
├── .swcrc # SWC configuration
├── tsconfig.json # TypeScript configuration
└── package.json
```

## 🧑‍💻 Author

Created by [Agung Dirgantara](mailto:agungmasda29@gmail.com) — licensed under [MIT](LICENSE).
