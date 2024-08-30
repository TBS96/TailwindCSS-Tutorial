# TailwindCSS setup with `Vite`, `PostCSS`, `AutoPrefixer`:

## 1. Setup `npm`:
```bash
npm init -y
```
<br>

## 2. Install & initialize:
```bash
npm install -D tailwindcss postcss autoprefixer vite
```
```bash
npx tailwindcss init -p
```
<br>

## 3. Open `tailwind.config.js` file & set content as ALL (*):
```bash
content: ['*']
```
<br>

## 4. Create folder `CSS` & a file within it, as `main.css` & add the Tailwind directives:
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```
<br>

## 5. Link `CSS/main.css` with `index.html`
```bash
<link rel="stylesheet" href="css/main.css">
```
<br>

## 6. Open `package.json` and set the below, under scripts:
```bash
"start": "vite"
```
<br>

## 7. Open terminal & run:
```bash
npm run start
```