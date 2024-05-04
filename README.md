# NextJS-Tailwind-Starter-Files

### CMD

```
npm install -D tailwindcss
npx tailwindcss init
```

#### tailwind.config.js & tailwind.config.ts

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./app/**/*.{js,ts,jsx,tsx,mdx}",
    "./pages/**/*.{js,ts,jsx,tsx,mdx}",
    "./components/**/*.{js,ts,jsx,tsx,mdx}",

    // Or if using 'src' directory:
    "./src/**/*.{js,ts,jsx,tsx,mdx}",
    ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

#### src/input.css

````
@tailwind base;
@tailwind components;
@tailwind utilities;
````
