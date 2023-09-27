# Project README:

Project utilizing React Router DOM - SPAs (Single Page Applications). It shows pages with products details, cart information, a home page and an admin area/page, accessed by typing "/admin" next to the default localhost address (example: http://127.0.0.1:5173/admin).

This project also has error handling with elements like: loader, ErrorBoundary and errorElement.
To show an error example, go to the "Produtos" section, click on any "Ver" button, then put at the end of the url path any number above 5 or just a 0 (example: http://127.0.0.1:5173/products/5000). 

The implementation involves React, CSS and Node.js. Execute the 'npm run dev' command in your terminal within the project directory, after installing Node.js and npm. 


------------------------------------------------------------------------------------------------------------------
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh