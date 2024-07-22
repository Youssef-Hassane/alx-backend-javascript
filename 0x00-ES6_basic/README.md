# ES6 Concepts and Linter Configuration

This GitHub repository contains a project focused on mastering JavaScript ES6 concepts and configuring a software linter. Through this project, you will gain a deep understanding of the latest JavaScript features and best practices in code quality assurance using ESLint.

## Concepts Covered

- **JavaScript Programming**: Advanced concepts and syntax introduced in ECMAScript 6 (ES6).
- **Software Linter**: Configuration and usage of ESLint to maintain code quality and consistency.

## Learning Resources

To complete this project, please refer to the following resources:

- **ECMAScript 6 - ECMAScript 2015**
- **Statements and Declarations**
- **Arrow Functions**
- **Default Parameters**
- **Rest Parameter**
- **JavaScript ES6 — Iterables and Iterators**

## Learning Objectives

By the end of this project, you should be able to explain:

- What ES6 is and the new features it introduces.
- The difference between a constant and a variable.
- Block-scoped variables.
- Arrow functions and default function parameters.
- Rest and spread function parameters.
- String templating in ES6.
- Object creation and properties in ES6.
- Iterators and for-of loops.

## Project Requirements

- **Environment**: Ubuntu 18.04 LTS with NodeJS 12.11.x.
- **Editors**: vi, vim, emacs, Visual Studio Code.
- **File Extensions**: All code files should use the `.js` extension and end with a new line.
- **README.md**: A mandatory README file at the root of the project folder.
- **Testing Framework**: Your code will be tested using Jest.
- **Linter**: Your code will be analyzed using ESLint with provided rules.
- **Module Exports**: All functions must be exported.

## Configuration Files

Add the following files to your project directory to configure the environment:

- **[package.json](./package.json)**: Manages project dependencies and scripts.
- **[babel.config.js](./babel.config.js)**: Configures Babel for JavaScript transpiling.
- **[.eslintrc.js](./.eslintrc.js)**: Configures ESLint for code quality and style enforcement.

## Setup Instructions

1. **Install NodeJS 12.11.x**:
   ```sh
   curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
   sudo bash nodesource_setup.sh
   sudo apt install nodejs -y
   nodejs -v  # should print v12.11.1
   npm -v     # should print 6.11.3
