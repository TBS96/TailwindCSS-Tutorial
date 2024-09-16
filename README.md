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
<br>


# To install & use `daisyUI`:

## 1. Follow upto `5th` step from above.
<br>

## 2. Install `daisyUI` as a Node package:
```bash
npm i -D daisyui@latest
```
<br>

## 3. Add `daisyUI` to `tailwind.config.js` => `module.exports` => `plugins[]`:
```bash
require('daisyui')
```
<br>

## 4. Goto `package.json` => "scripts:{} & add the following:"
```bash
"dev": "vite"
```
<br>

## 5. Open terminal & run:
```bash
npm run dev
```
<br>


# To build for production:

## Goto package.json => "scripts:{} & add the following:"
```bash
"build": "vite build"
```