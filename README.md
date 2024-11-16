<h1>React-Router:</h1>
   <P>npm create vite@latest name-of-your-project -- --template react<br/>
    npm install react-router-dom <br/>
    npm install localforage match-sorter sort-by <br/>
    npm run dev<br/>
    [import {    --main.jsx
    createBrowserRouter,
    RouterProvider,
    } from "react-router-dom";
        const router = createBrowserRouter([
    {
        path: "/",
        element: <div>Hello world!</div>,
    },
    ]); 
    <RouterProvider router={router} />]
    </p>

     

<h1>daisyUI:</h1>
    <p>npm i -D daisyui@latest   
        plugins: [
        require('daisyui'),
    ],</p>

<h1>Tailwind Css</h1>
    <p>npm install -D tailwindcss postcss autoprefixer
    npx tailwindcss init -p  
    content: [
        "./index.html",
        "./src/**/*.{js,ts,jsx,tsx}",
    ],</p>
    <p>index css-- 
    @tailwind base;
    @tailwind components;
    @tailwind utilities;</p>