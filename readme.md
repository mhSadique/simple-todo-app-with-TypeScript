# This is a starter TypeScript project with snowpack as bundler

### New things learned about TS compiler:

- You can create however many `.ts` files as you want, and, when you run, just `tsc` or `tsc --watch`, Typescript will create corresponding `.js` files for all the `.ts` files and it will create them inside the folders where the `.ts` files reside
- But if you want TS to output the `.js` files into a particular folder, you need to go inside `tsconfig.json` and change the value of `"outDir"` as `the path to your folder`, like this: `"outDir": "./path-to-the-folder"`

### New things learned about DOM and TS:

- You can use TS code below to find an HTML element `js const list = document.querySelector<HTMLUListElement>('#list'); `

### Limitation of using different npm packages without a bundler

- Browsers do not (probably!) have a way to read scripts from `node_modules` folder, so, you need a bundler to bundle the scripts that browsers can read

- So, for this project, we are gonna use `snowpack` as a bundler
