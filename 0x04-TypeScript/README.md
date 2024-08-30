# 0x04. TypeScript

## Overview
This project explores TypeScript, a strongly typed programming language that builds on JavaScript. The project covers various aspects of TypeScript, including basic types, interfaces, classes, functions, generic types, namespaces, ambient namespaces, and nominal typing.

## Learning Objectives
By the end of this project, you should be able to:

- Understand and use basic types in TypeScript.
- Create and implement interfaces and classes.
- Work with the DOM using TypeScript.
- Utilize generic types.
- Use namespaces effectively.
- Merge declarations in TypeScript.
- Implement an ambient namespace to import an external library.
- Apply basic nominal typing in TypeScript.

## Requirements
- All files are transpiled on Ubuntu 18.04.
- Use TypeScript (`.ts` extension) where possible.
- No TypeScript compiler warnings or errors.
- The project is managed using Visual Studio Code and configured with TypeScript, Webpack, Jest, and ESLint.

## Tasks
### Task 0: Creating an Interface for a Student
- Create an interface `Student` with `firstName`, `lastName`, `age`, and `location`.
- Render a table displaying the students' first names and locations using Vanilla JavaScript.

### Task 1: Building a Teacher Interface
- Create a `Teacher` interface with various attributes.
- Add the ability to extend the `Teacher` interface dynamically with additional properties.

### Task 2: Extending the Teacher Interface with Directors
- Extend the `Teacher` interface to create a `Directors` interface with additional attributes.

### Task 3: Printing Teachers
- Implement a function `printTeacher` that formats teacher names.
- Define an interface for the function.

### Task 4: Writing a Student Class
- Create a `StudentClass` with a constructor and methods.
- Implement interfaces for both the class and the constructor.

### Task 5: Advanced Types Part 1
- Create interfaces for `Director` and `Teacher`, each with their respective methods.
- Implement classes that follow these interfaces and a function `createEmployee` to instantiate them.

### Task 6: Employee-specific Functions
- Write functions to determine if an employee is a `Director` and to execute tasks based on their role.

### Task 7: String Literal Types
- Implement a string literal type `Subjects` and a function `teachClass` to determine the subject being taught.

### Task 8: Ambient Namespaces
- Define types and interfaces for rows and implement ambient type declarations for a library.

### Task 9: Namespace & Declaration Merging
- Use namespaces to organize classes and interfaces.
- Implement declaration merging for a `Teacher` interface.

### Task 10: Updating main.ts
- Export constants and log various operations in the console using classes created in previous tasks.

### Task 11: Brand Convention & Nominal Typing
- Create interfaces with unique identifiers and functions to sum major and minor credits.

## Setup Instructions
1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Build the project using `npm run build`.
5. Run tests using `npm test`.


