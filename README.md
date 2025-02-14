# JavaScript Learning

A structured JavaScript learning repository covering concepts from the fundamentals to advanced topics.

The repository includes:

- Concept explanations
- Practical code examples
- Exercises and solutions
- Interview questions and answers

## What You'll Learn

### Fundamentals

- Variables: `var`, `let`, `const`
- Data types
- Operators
- Type conversion
- Strings and template literals

### Control Flow

- `if`, `else if`, `else`
- `switch`
- `for`, `while`, and `do...while`
- `break` and `continue`

### Functions and Scope

- Function declarations and expressions
- Arrow functions
- Parameters and return values
- Scope
- Closures
- Higher-order functions
- Callback functions

### Arrays and Objects

- Creating and accessing arrays and objects
- Array methods
- `map()`
- `filter()`
- `reduce()`
- `find()`
- Destructuring
- Spread and rest operators

### DOM and Events

- DOM selectors
- Creating and modifying elements
- Event handling
- Event propagation
- Forms and form validation

### Asynchronous JavaScript

- Callbacks
- Promises
- `async` / `await`
- `fetch()`
- Error handling
- Event loop

### Object-Oriented JavaScript

- Objects
- Prototypes
- Constructor functions
- Classes
- Inheritance
- Encapsulation
- `this`

### Advanced JavaScript

- Hoisting
- Closures
- Execution context
- Call stack
- Event loop
- Memory management
- Garbage collection

### Modern JavaScript

- ES6+ features
- Modules
- Destructuring
- Spread and rest
- Optional chaining
- Nullish coalescing
- Default parameters

### Real-World JavaScript

- Working with APIs
- JSON
- Local storage
- Error handling
- Common programming patterns
- Writing maintainable JavaScript

### Performance and Best Practices

- Code organization
- Performance optimization
- Avoiding common mistakes
- Clean code principles
- Debugging techniques

## Repository Structure

```text
Javascript-guide/
├── JsCodes/
├── JsConcepts/
│   ├── Arrays/
│   ├── Classes/
│   ├── Closure/
│   ├── DataTypes/
│   ├── DOM/
│   ├── EventLoop/
│   ├── Events/
│   ├── Functions/
│   ├── Loops/
│   ├── Objects/
│   ├── Promises/
│   ├── Scopes/
│   ├── Strings/
│   └── Variables/
├── Resources/
└── README.md
```

Each concept should include, where applicable:

- Explanation
- Examples
- Practice exercises
- Solutions
- Interview questions

## Who Is This For?

This repository is intended for:

- Beginners learning JavaScript
- Developers strengthening their JavaScript fundamentals
- Developers preparing for JavaScript interviews
- Anyone looking for a structured JavaScript reference

## How to Use This Repository

1. Clone the repository.

```bash
git clone https://github.com/your-username/javascript-guide.git
cd javascript-guide
```

2. Start with the fundamentals.
3. Study each concept and run the examples.
4. Complete the exercises before checking the solutions.
5. Use the interview questions to test your understanding.
6. Experiment with the code and practice debugging.

## Goal

The goal of this repository is to build a strong understanding of JavaScript through structured learning and practical coding.

Start with the fundamentals, practice consistently, and gradually move toward advanced concepts.

#### Keep your start Date in for JavaScript Learning Journey

**Started:** 1st Apr 2021

```js
const input = "1st Apr 2021";

const [day, month, year] = input.split(" ");

const output = `${year}-${month}-${day}`;

console.log(output);
output : 2021-Apr-1st
```

### Date String Formatting

A simple example of splitting a string into variables and reordering the values to create a new date format.

```js
const input = "1st Apr 2021";

const [day, month, year] = input.split(" ");

const output = `${year}-${month}-${day}`;

console.log(output);
```

Output:

```text
2021-Apr-1st
```

This example introduces:

- `split()` to convert a string into an array
- Array destructuring to assign values to variables
- Template literals to create a new string
