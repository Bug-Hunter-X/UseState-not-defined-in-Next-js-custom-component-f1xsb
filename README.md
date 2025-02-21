# Next.js useState Error in Custom Component

This repository demonstrates a common error encountered in Next.js applications where the `useState` hook is not defined within a custom component.  The error message typically looks like: `'useState' is not defined`. This usually arises from incorrect import statements or a lack of necessary context in the component's scope.

## How to Reproduce

1. Clone this repository.
2. Navigate to the `pages` directory.
3. Run `npm install` or `yarn install` to install dependencies.
4. Run `npm run dev` or `yarn dev` to start the development server.
5. Observe the error in the browser console.

## Solution

The solution involves ensuring that the `useState` hook is imported correctly from the 'react' library.  This requires importing 'react' in the custom component file. The solution is demonstrated in `bugSolution.js`.