# electron-react-typescript

- Electron with React + Typescript setup (Offcial docs)

### Steps
- Create new Electron app with a webpack typescript template using Electron Forge 
- Inside the compilerOptions in `tsconfig.json` add `"jsx": "react-jsx"` key-value pair so your app can recorgnise jsx syntax.
- Install react & react dom
- Install @types for react & react dom
- create appjs and initialise react & react dom
- Import app.tsx into `renderer.ts` 
- Add `<div id=root />` to your index.html file
