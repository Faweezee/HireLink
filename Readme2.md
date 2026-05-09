---

## 🧩 Frontend Setup (Initial Configuration)

The frontend has been initialized using **Next.js** with TypeScript support.

### ESLint Configuration

The project uses a custom ESLint configuration based on Next.js recommended rules:

```ts
import { defineConfig, globalIgnores } from "eslint/config";
import nextVitals from "eslint-config-next/core-web-vitals";
import nextTs from "eslint-config-next/typescript";

const eslintConfig = defineConfig([
  ...nextVitals,
  ...nextTs,
  globalIgnores([
    ".next/**",
    "out/**",
    "build/**",
    "next-env.d.ts",
  ]),
]);

export default eslintConfig;