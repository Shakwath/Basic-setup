<h1>React-Router:</h1>
   <P>npm create vite@latest name-of-your-project -- --template react<br/>
    npm install react-router-dom <br/>
    npm install localforage match-sorter sort-by <br/>
    npm run dev<br/>
    [import {    --main.jsx <br/>
    createBrowserRouter,<br/>
    RouterProvider,<br/>
    } from "react-router-dom";<br/>
        const router = createBrowserRouter([<br/>
    {<br/>
        path: "/",<br/>
        element: <div>Hello world!</div>,<br/>
    },<br/>
    ]); <br/>
    <RouterProvider router={router} />]<br/>
    </p>

     

<h1>daisyUI:</h1>
    <p>npm i -D daisyui@latest  <br/> 
        plugins: [  <br/>
        require('daisyui'), <br/>
    ],</p>

<h1>Tailwind Css</h1>
    <p>npm install -D tailwindcss postcss autoprefixer<br/>
    npx tailwindcss init -p  <br/>
    content: [  <br/>
        "./index.html",<br/>
        "./src/**/*.{js,ts,jsx,tsx}",<br/>
    ],</p>
    <p>index css-- <br/>
    @tailwind base;<br/>
    @tailwind components;<br/>
    @tailwind utilities;</p><br/>