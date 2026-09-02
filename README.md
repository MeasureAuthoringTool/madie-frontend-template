# MADiE Frontend Template

A starter frontend application for MADiE microfrontends built with React, TypeScript, single-spa, Tailwind CSS, and Material UI.

## Overview

This repository is a template for creating new frontend modules in the MADiE ecosystem. It provides a basic single-spa shell setup and includes styling, test configuration, and standard build tooling.

## Tech Stack

- React 17
- TypeScript
- single-spa
- Webpack 5
- Tailwind CSS
- Material UI
- Jest + Testing Library

## Prerequisites

- Node.js 18+
- npm

## Getting Started

1. Install dependencies:
   npm install

2. Start the app locally:
   npm start

3. Open the app in a browser at:
   http://localhost:8500

## Available Scripts

- npm start — starts the webpack dev server
- npm run build — builds the app for production
- npm run lint — runs ESLint
- npm run test — runs the Jest test suite
- npm run coverage — runs tests with coverage
- npm run format — formats project files
- npm run check-format — checks formatting

## Project Structure

src/
  madie-madie-frontend-template.tsx
  root.component.tsx
  root.component.test.tsx
  styles/
  types/

## Customizing for a New App

Before using this template for a real app:

- replace occurrences of madie-frontend-template with your app name
- rename the entry file and matching module references
- update package metadata in package.json
- adjust the root component and app-specific logic

## Testing

Run:

npm test

## License

This project is licensed under the MIT License. See LICENSE for details.
