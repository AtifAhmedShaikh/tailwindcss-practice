# Tailwind CSS Practice

This repository is dedicated to practicing Tailwind CSS by implementing various UI designs sourced from websites like frontend.mentor.io and others. The goal is to enhance frontend/UI skills while getting hands-on experience with Tailwind CSS.

## About Tailwind CSS

Tailwind CSS is a utility-first CSS framework that provides low-level utility classes to build custom designs without having to leave your HTML.

## Get Started

1. Clone this repository:

   ```bash
   git clone https://github.com/AtifAhmedShaikh/tailwindcss-practice.git

   ```

#

## How to use Tailwindcss

1. Install tailwind css:

   ```bash
   npm install -D tailwindcss
   npx tailwindcss init
   ```

#

2. Add content in tailwind.config.js

   ```bash
   content: ["./src/**/*.{html,js}"],
   ```

3. Create input.css file inside the src folder src/input.css

4. Add This in your input.css file
   ```bash
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```
5. Generate the output.css file by running this command

   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

6. Now Add Link tag in your HTML file

   ```bash
   <link href="./output.css" rel="stylesheet">
   ```
