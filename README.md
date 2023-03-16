# React Vite Capacitor

This is a starter template for building mobile applications with React and Vite.

## Getting Started

Clone this repository:

```bash
git clone https://github.com/ej-shafran/react-vite-template.git <PROJECT NAME>
rm -Rf <PROJECT NAME>/.git
```

You'll notice that a lot of the folders have a `.keep` file in them - this is so git can keep track of them. Once you've added files to a folder, you can (_and should_) delete the `.keep` file from it.

Install the dependencies:

```bash
npm install
```

Run the development server:

```bash
npm start
```

You may be used to `create-react-app` automatically opening the server in your browser, but this command **will not do that**; you'll need to type `o` on your keyboard at the terminal the server is running on to open it in the browser. (This is nice because we don't get 30 open tabs of the same project).

To build the app for production:

```bash
npm build
```

## 📁 Project Structure

```any
├── public
├── src
│ ├── assets
│ ├── common
│ │  ├── constants
│ │  ├── functions
│ │  ├── hooks
│ │  └── types
│ ├── components
│ ├── styles
│ ├── App.tsx
│ ├── main.tsx
│ └── vite-env.d.ts
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.js
```
