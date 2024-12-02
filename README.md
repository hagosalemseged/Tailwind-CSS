How to install Tailwind CSS
=============================
1. Install nodejs
2. npm install -D tailwindcss
3. npx tailwindcss init // to initilize the tailwind css
4. Configure your template path in tailwind.config.js
/** @type {import('tailwindcss').Config} */
   module.exports = {
	  content: ["./src/**/*.{html,js}"],
	  theme: {
	    extend: {},
	  },
	  plugins: [],
   }
5. create input.css file and add the following css code to the file
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
6. Start the tailwindcss CLI build process
7. npx tailwindcss -i input.css -o ./css/output.css --watch
