FrontEnd folder -
Project setup -

1. npm create vite@latest .
2. npm install
3. npm run dev

Tailwind Css:

1. npm install -D tailwindcss postcss autoprefixer
2. npx tailwindcss init -p

3) update tailwind.config.js file

   /** @type {import('tailwindcss').Config} \*/
   export default {
   content: [
   "./index.html",
   "./src/**/\*.{js,ts,jsx,tsx}",
   ],
   theme: {
   extend: {},
   },
   plugins: [],
   }

4) npm i -D daisyui@latest
