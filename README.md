# React App - Production Build

This project contains a React.js application. This README explains how to run the production build of the app using the `serve` package.

## Prerequisites

Make sure you have the following installed:

- **Node.js** (v14 or higher recommended)
- **npm** (v6 or higher) or **yarn**
- **serve** package (to serve the production build)

You can install `serve` globally if you don't have it:

```bash
npm install -g serve
# or using yarn
yarn global add serve

# Serve the build folder
serve -s build

# Serve explicitly pointing to index.html
serve -s build/index.html

# Serve on a custom port (example: 3000)
serve -s build -l 3000

