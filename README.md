#Tailwind with react

**Step 1:** Create react app with the following code:
```
npx create-react-app my-project
cd my-project
```

**Step 2:** Install tailwindcss via npm, and then run the init command to generate your tailwind.config.js file.
```
npm install -D tailwindcss
npx tailwindcss init
```
**Step 3:** Change the contents of ***tailwind.config.js*** file to:
```
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
```
***Step 4:** Fo to ***./src/index.css*** and add the following css into it:
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

**Step 5:** Start your project:
```
npm start
```
