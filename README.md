# Tailwind-CSS-Project

To setup tailwind css, run these commands

1. npm init -v // This initializes the directives as a NodeJs project
2. npm install -D tailwindcss postcss autoprefixer vite // install requrired packeges.
3. npx tailwindcss init -p
4. Create a css file "input.css", add it to your html and edit it with this content:
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
5. In your tailwind.confing.js file replace content:[], with content:[*],
6. Add "start":"vite" to your script in package.json
7. ** For Run** npm run start command to start a dev server

