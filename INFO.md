# Project to-better-auth

##  1 - PART 0: Setup Next.js application with TypeScript, Tailwind CSS, shadcn/ui

```
[https://www.youtube.com/watch?v=N4meIif7Jtc&t=234s]
```

### 1.1 Create project

```
[https://www.youtube.com/watch?v=N4meIif7Jtc&t=234s]

npx create-next-app@16.4.6
√ What is your project named? ... to-better-auth
√ Would you like to use the recommended Next.js defaults? » No, customize settings
√ Would you like to use TypeScript? ... Yes
√ Which linter would you like to use? » ESLint
√ Would you like to use React Compiler? ... No
√ Would you like to use Tailwind CSS? ... Yes
√ Would you like your code inside a `src/` directory? ... Yes
√ Would you like to use App Router? (recommended) ... Yes
√ Would you like to use Cache Components? ... No
√ Would you like to customize the import alias (`@/*` by default)? ... No
√ Would you like to include AGENTS.md to guide coding agents to write up-to-date Next.js code? ... Yes
√ Would you like to help improve Next.js by letting agents prepare anonymized feedback for your review as you code? (Disable anytime with `experimental.agentFeedback: false`.) ... No
```

### 1.2 Install shadcn

```
npx shadcn@3.3.1 init
Need to install the following packages:
shadcn@3.3.1
Ok to proceed? (y) 

npm warn deprecated node-domexception@1.0.0: Use your platform's native DOMException instead
✔ Preflight checks.
✔ Verifying framework. Found Next.js.
✔ Validating Tailwind CSS config. Found v4.
✔ Validating import alias.
√ Which color would you like to use as the base color? » Zinc
✔ Writing components.json.
✔ Checking registry.
✔ Updating CSS variables in src\app\globals.css
✔ Updating src\app\globals.css
✔ Installing dependencies.
✔ Created 1 file:
  - src\lib\utils.ts

Success! Project initialization completed.
You may now add components.
```

### 1.3 Add components

```
npx shadcn@3.3.1 add button label input sonner
✔ Checking registry.
✔ Installing dependencies.
✔ Created 4 files:
  - src\components\ui\button.tsx
  - src\components\ui\label.tsx
  - src\components\ui\input.tsx
  - src\components\ui\sonner.tsx
```

```
npm install --save-dev --save-exact @biomejs/biome
```

## 2 - PART 1: Email and Password Authentication (CLIENT SIDE)

```
[https://www.youtube.com/watch?v=N4meIif7Jtc&t=468s]
```

### 2.1 Install Better Auth


```
1. Installation

npm install better-auth@1.7.25

2. Set environment variables

File: .env
BETTER_AUTH_SECRET="g8xBEIEdViADnDulCGH0TgCcRrYCUAf1"

3. Set Base URL

File: .env
BETTER_AUTH_URL=http://localhost:3000 # Base URL of your app

4. Set Next Public API Url

File: .env
NEXT_PUBLIC_API_URL="http://localhost:3000"
```

Current: 10:17

