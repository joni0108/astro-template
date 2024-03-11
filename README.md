# astro-template

This is an starting template for Astro framework projects.

## Features

It does have everything you will need to get started with any project using the Astro Framework. It includes:

- [x] - TypeScript
- [x] - ESLint (with Prettier)
- [x] - Jest for testing
- [x] - React for dynamic components/astro islands
- [x] - Husky for pre-commit testing and prettier formatting before commiting to branch
- [x] - Folder structure

## Installation
1. Create a repository using this template.
2. Clone your repository.
3. Read the `..todo`` file to see what steps you must do.

## Common Errors

1. **@ imports not working**: Check the file `tsconfig.json` in the root folder and set it as the project folder.
2. **It does not commit**: Check the logs, to see the issue:

- If it says something about `prettier`, then run `npm run format` in your terminal. This should fix the error and standarize the prettier.
- If it says something like failed tests, it means that one of the tests you wrote is failing for any reason.
- Otherwise, check if you have the repository and local branch setup correctly.
