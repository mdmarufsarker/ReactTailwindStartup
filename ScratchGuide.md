## Create your project

    npx create-react-app@latest my-project
    cd my-project

## Install Tailwind CSS

    npm install -D tailwindcss postcss autoprefixer
    npx tailwindcss init -p

## Configure your template paths in tailwind.config.js

    module.exports = {
      content: ['./src/**/*.{js,jsx,ts,tsx}'],
      theme: {
    	extend: {},
      },
      plugins: [],
    };

## Add the Tailwind directives to your CSS in index.css

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

## Start your build process

    npm run start

## Start using Tailwind in your project in App.js

    function App() {
        return (
            <div>
            <h1 className="text-3xl font-bold underline ">Hello world!</h1>
            </div>
        );
    }
