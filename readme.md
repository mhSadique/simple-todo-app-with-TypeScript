# This is a starter TypeScript project

### New things learned:

- You can create however many `.ts` files as you want, and, when you run, just `tsc` or `tsc --watch`, Typescript will create corresponding `.js` files for all the `.ts` files and it will create them inside the folders where the `.ts` files reside
- But if you want TS to output the `.js` files into a particular folder, you need to go inside `tsconfig.json` and change the value of `"outDir"` as `the path to your folder`, like this: `"outDir": "./path-to-the-folder"`
