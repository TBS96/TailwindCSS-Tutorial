# `TailwindCSS` setup with `Vite`, `PostCSS`, `AutoPrefixer`:

## 0. Setup `npm`:
```bash
npm init -y
```
<br>

## 1. Install & initialize:
```bash
npm install -D tailwindcss postcss autoprefixer vite
```
```bash
npx tailwindcss init -p
```
<br>

## 2. Open `tailwind.config.js` file & set content as ALL (*):
```bash
content: ['*']
```
<br>

## 3. Create folder `CSS` & a file within it, as `main.css` & add the Tailwind directives:
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```
<br>

## 4. Open `package.json` and set the below, under scripts:
```bash
"dev": "vite",
```
<br>

## 5. Open terminal & run:
```bash
npm run start
```