# Next.js: Incorrect `href` Property in `next/link` Component

This repository demonstrates a common but subtle bug in Next.js applications involving the `next/link` component. Incorrectly specifying the `href` property can lead to broken links and unexpected routing behavior without always producing clear error messages.

## Bug Description

The `bug.js` file contains a Next.js component with `next/link` components.  The `href` property of one or more of the links might be misspelled or have other issues. This causes unexpected behavior – the links might not work correctly, and users could encounter a 404 page or similar errors.

## Solution

The `bugSolution.js` file shows the corrected code with the correctly specified `href` properties, ensuring that all links function as expected.  Double-check that your paths are correct and that they match your Next.js project structure.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `npm install` to install dependencies.
4. Run `npm run dev` to start the development server.
5. Observe the behavior of the links; one should be broken in `bug.js` but functional in `bugSolution.js`.
