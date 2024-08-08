# AtoZ-FullstackDeveloper
learning to get job/freelance complete

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p

<!-- --------------------------- -->

/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

<!-- -------------------------------- -->

@tailwind base;
@tailwind components;
@tailwind utilities;
