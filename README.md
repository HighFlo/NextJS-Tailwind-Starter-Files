# NextJS-Tailwind-Starter-Files

### CMD

```
npm install -D tailwindcss
npx tailwindcss init
```

#### tailwind.config.js

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

@layer components {
    .heading {
        @apply text-center text-white text-[28px] sm:text-[33px] md:text-[45px] font-bold uppercase
    }
}
````
