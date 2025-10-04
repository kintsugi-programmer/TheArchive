# FULLSTACK_WEBDEV

# Table of Contents
- [FULLSTACK\_WEBDEV](#fullstack_webdev)
- [Table of Contents](#table-of-contents)
- [1 JavaScript Asynchronous Programming - Complete Notes](#1-javascript-asynchronous-programming---complete-notes)
  - [Introduction to "Advanced" JavaScript](#introduction-to-advanced-javascript)
    - [Clarification on Terminology](#clarification-on-terminology)
    - [Learning Philosophy](#learning-philosophy)
  - [Understanding Asynchronous JavaScript](#understanding-asynchronous-javascript)
    - [What is Synchronous Code?](#what-is-synchronous-code)
    - [What is Asynchronous Code?](#what-is-asynchronous-code)
  - [Why Do We Need Asynchronous Behavior?](#why-do-we-need-asynchronous-behavior)
    - [Common Scenarios Requiring Pauses:](#common-scenarios-requiring-pauses)
  - [Critical JavaScript Limitation](#critical-javascript-limitation)
    - [JavaScript's Built-in Capabilities](#javascripts-built-in-capabilities)
    - [Runtime Environment Support](#runtime-environment-support)
  - [The Event Loop Architecture](#the-event-loop-architecture)
    - [Core Components Diagram](#core-components-diagram)
    - [Step-by-Step Execution Flow](#step-by-step-execution-flow)
    - [Real Example Walkthrough](#real-example-walkthrough)
  - [Key Concepts Summary](#key-concepts-summary)
    - [Single-Threaded Nature](#single-threaded-nature)
    - [Non-Blocking Execution](#non-blocking-execution)
    - [Environment Dependency](#environment-dependency)
  - [Important Notes for Further Learning](#important-notes-for-further-learning)
    - [What's Coming Next](#whats-coming-next)
    - [Study Recommendations](#study-recommendations)
    - [Memory Aid](#memory-aid)
- [2 JavaScript Closures: Comprehensive Notes](#2-javascript-closures-comprehensive-notes)
  - [What is a Closure?](#what-is-a-closure)
    - [Key Definition](#key-definition)
    - [Basic Example](#basic-example)
  - [How Closures Work](#how-closures-work)
    - [Lexical Scoping Foundation](#lexical-scoping-foundation)
    - [Memory Management](#memory-management)
  - [Practical Use Cases](#practical-use-cases)
    - [1. Data Encapsulation and Private Variables](#1-data-encapsulation-and-private-variables)
    - [2. Function Factories and Counters](#2-function-factories-and-counters)
    - [3. Module Pattern](#3-module-pattern)
    - [4. Event Handlers and Callbacks](#4-event-handlers-and-callbacks)
  - [Interview Questions and Common Patterns](#interview-questions-and-common-patterns)
    - [Q1: Basic Closure Understanding](#q1-basic-closure-understanding)
    - [Q2: Closure with Parameters](#q2-closure-with-parameters)
    - [Q3: Loop and Closure Issue](#q3-loop-and-closure-issue)
  - [Memory Considerations](#memory-considerations)
    - [Potential Memory Leaks](#potential-memory-leaks)
    - [Best Practices](#best-practices)
  - [Key Benefits](#key-benefits)
  - [Summary](#summary)
- [3 JavaScript Promises - Comprehensive Study Notes](#3-javascript-promises---comprehensive-study-notes)
  - [What are Promises?](#what-are-promises)
  - [Promise States](#promise-states)
  - [Creating a Promise](#creating-a-promise)
    - [Basic Syntax](#basic-syntax)
    - [Key Components:](#key-components)
    - [Example with setTimeout (Simulating Async Operation):](#example-with-settimeout-simulating-async-operation)
  - [Consuming Promises](#consuming-promises)
    - [Using .then() and .catch()](#using-then-and-catch)
    - [Method Details:](#method-details)
  - [Promise Chaining](#promise-chaining)
    - [Chaining Benefits:](#chaining-benefits)
  - [Asynchronous Nature of JavaScript](#asynchronous-nature-of-javascript)
    - [Why Promises are Always Asynchronous](#why-promises-are-always-asynchronous)
    - [Event Loop and Promise Execution](#event-loop-and-promise-execution)
  - [Error Handling Best Practices](#error-handling-best-practices)
    - [Proper Error Handling Chain:](#proper-error-handling-chain)
    - [Important Notes:](#important-notes)
  - [Advanced Promise Methods](#advanced-promise-methods)
    - [Promise.all()](#promiseall)
    - [Promise.allSettled()](#promiseallsettled)
  - [Common Patterns and Tips](#common-patterns-and-tips)
    - [1. Returning Values in .then()](#1-returning-values-in-then)
    - [2. Promise vs Async/Await](#2-promise-vs-asyncawait)
    - [3. Error Propagation](#3-error-propagation)
  - [Key Takeaways](#key-takeaways)
  - [Practical Example](#practical-example)
- [4 JavaScript Prototypal Inheritance: A Complete Guide](#4-javascript-prototypal-inheritance-a-complete-guide)
  - [What is Prototypal Inheritance?](#what-is-prototypal-inheritance)
  - [How the Prototype Chain Works](#how-the-prototype-chain-works)
  - [Constructor Functions and Prototypal Inheritance](#constructor-functions-and-prototypal-inheritance)
    - [Basic Constructor Example](#basic-constructor-example)
  - [Key Concepts and Properties](#key-concepts-and-properties)
    - [The `__proto__` Property](#the-__proto__-property)
    - [Difference Between `prototype` and `__proto__`](#difference-between-prototype-and-__proto__)
  - [Advanced Inheritance Patterns](#advanced-inheritance-patterns)
    - [Using Object.create()](#using-objectcreate)
  - [Memory Efficiency and Performance](#memory-efficiency-and-performance)
  - [Common Interview Questions and Examples](#common-interview-questions-and-examples)
    - [Adding Methods to Built-in Prototypes](#adding-methods-to-built-in-prototypes)
    - [Demonstrating Property Lookup](#demonstrating-property-lookup)
  - [Best Practices and Modern Considerations](#best-practices-and-modern-considerations)
  - [Summary](#summary-1)
- [5 SQL Crash Course: Complete Database Operations Guide](#5-sql-crash-course-complete-database-operations-guide)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents-1)
  - [Database Setup](#database-setup)
    - [Creating a Database](#creating-a-database)
    - [Accessing Query Tool](#accessing-query-tool)
  - [Table Creation \& Data Types](#table-creation--data-types)
    - [Basic Table Structure](#basic-table-structure)
    - [Data Types Explained](#data-types-explained)
      - [**VARCHAR(n)**](#varcharn)
      - [**DECIMAL(precision, scale)**](#decimalprecision-scale)
      - [**BOOLEAN**](#boolean)
      - [**SERIAL**](#serial)
      - [**PRIMARY KEY**](#primary-key)
  - [Data Insertion](#data-insertion)
    - [Single Record Insertion](#single-record-insertion)
    - [Multiple Records Insertion](#multiple-records-insertion)
  - [Querying Data](#querying-data)
    - [Basic SELECT Operations](#basic-select-operations)
      - [Select All Data](#select-all-data)
      - [Select Specific Columns](#select-specific-columns)
      - [Using Column Aliases](#using-column-aliases)
    - [Filtering with WHERE Clause](#filtering-with-where-clause)
      - [Pattern Matching with LIKE](#pattern-matching-with-like)
      - [Comparison Operations](#comparison-operations)
    - [Sorting Results](#sorting-results)
  - [Data Updates](#data-updates)
    - [UPDATE Syntax](#update-syntax)
    - [Example: Update Price and Availability](#example-update-price-and-availability)
  - [Data Deletion](#data-deletion)
    - [DELETE Syntax](#delete-syntax)
    - [Example: Remove a Product](#example-remove-a-product)
  - [Best Practices](#best-practices-1)
    - [1. **Query Safety**](#1-query-safety)
    - [2. **Data Types**](#2-data-types)
    - [3. **SQL Formatting**](#3-sql-formatting)
    - [4. **Performance Considerations**](#4-performance-considerations)
    - [5. **Naming Conventions**](#5-naming-conventions)
  - [Common SQL Operators Summary](#common-sql-operators-summary)
  - [Case Study: Chai Store Database](#case-study-chai-store-database)
  - [Conclusion](#conclusion)


# 1 JavaScript Asynchronous Programming - Complete Notes

## Introduction to "Advanced" JavaScript

### Clarification on Terminology
- **There is no such thing as "Advanced JavaScript"** - it's all part of the same language
- The term "advanced" is commonly used in academic curricula, especially in India
- What's often called "advanced" includes:
  - Frameworks and libraries
  - Higher-level language features
  - Asynchronous behavior
  - Promises and callbacks

### Learning Philosophy
- **Project-based learning is most effective**
- No single teacher or book can cover everything comprehensively
- Learning through practical implementation helps with understanding and retention
- Theory should be combined with hands-on projects

## Understanding Asynchronous JavaScript

### What is Synchronous Code?
Synchronous code executes **line by line, in sequence**:

```javascript
console.log("chaicode");

for (let index = 0; index < 10; index++) {
    console.log(index);
}
```

- Every statement waits for the previous one to complete
- Predictable execution order
- No pauses or delays

### What is Asynchronous Code?
Asynchronous code allows for **pauses and non-sequential execution**:

```javascript
console.log("chaicode");

setTimeout(function sayHello() {
    console.log("I would like to say hello");
}, 4000);

for (let index = 0; index < 10; index++) {
    console.log(index);
}
```

**Output order:**
1. "chaicode"
2. Numbers 0-9 from the loop
3. "I would like to say hello" (after 4 seconds)

## Why Do We Need Asynchronous Behavior?

### Common Scenarios Requiring Pauses:

1. **Network Calls**
   - Database requests
   - Server communications
   - API calls
   - Can take milliseconds to seconds depending on:
     - Geographic distance (India → Germany → USA)
     - Network conditions
     - Server response time

2. **File Operations**
   - Reading from disk
   - Writing to files
   - Much slower than memory operations
   - Requires waiting for disk I/O

3. **Timer Functions**
   - `setTimeout()`
   - `setInterval()`
   - Delayed execution
   - Animation timing

4. **User Input**
   - Form submissions
   - Mouse events
   - Keyboard input
   - Device interactions

## Critical JavaScript Limitation

### JavaScript's Built-in Capabilities
- **JavaScript CANNOT execute network calls natively**
- **JavaScript CANNOT execute most timer functions natively**
- **JavaScript needs external help** from the runtime environment

### Runtime Environment Support
JavaScript relies on:
- **Browser environment** (for web applications)
- **Node.js** (for server-side)
- **Bun** (alternative runtime)
- **Deno** (secure runtime)

These environments provide the actual capabilities for:
- Network requests
- File system access
- Timer functions
- System interactions

## The Event Loop Architecture

### Core Components Diagram

```
┌─────────────────┐
│   Your Code     │
│   (Functions)   │
└─────────────────┘
         │
         ▼
┌─────────────────┐
│   Call Stack    │
└─────────────────┘
         ▲
         │
┌─────────────────┐
│   Event Loop    │ ←─── Continuously monitors
└─────────────────┘
         │
         ▼
┌─────────────────┐    ┌─────────────────┐
│  Regular Queue  │    │   VIP Queue     │
│                 │    │  (Priority)     │
└─────────────────┘    └─────────────────┘
         ▲                       ▲
         │                       │
         └───────────────────────┘
                     │
                     ▼
            ┌─────────────────┐
            │   Environment   │
            │ (Browser/Node)  │
            └─────────────────┘
```

### Step-by-Step Execution Flow

1. **Code Execution Starts**
   - All functions enter the **Call Stack**
   - Event Loop continuously monitors the Call Stack

2. **Regular Functions**
   - Executed immediately by Event Loop
   - Removed from Call Stack when complete

3. **Asynchronous Functions** (Timer, Network, File I/O)
   - Event Loop identifies it cannot execute these
   - **Passes function to Environment** (Browser/Node.js)
   - Environment handles the actual execution

4. **Environment Processing**
   - Browser/Node.js executes the asynchronous operation
   - When complete, places callback in appropriate **Queue**

5. **Queue Management**
   - **VIP Queue**: High priority operations
   - **Regular Queue**: Standard callback operations
   - Event Loop processes VIP Queue first

6. **Callback Execution**
   - Event Loop checks if Call Stack is empty
   - If empty, moves callbacks from Queue to Call Stack
   - Executes the callback function

### Real Example Walkthrough

```javascript
console.log("chaicode");           // 1. Goes to Call Stack
setTimeout(sayHello, 4000);        // 2. Goes to Environment
for (let i = 0; i < 10; i++) {     // 3. Goes to Call Stack
    console.log(i);
}
```

**Execution Timeline:**
1. `console.log("chaicode")` → **Call Stack** → Execute → Remove
2. `setTimeout(sayHello, 4000)` → **Environment** (Browser/Node) → Timer starts
3. `for loop` → **Call Stack** → Execute all iterations → Remove
4. (4 seconds later) Timer complete → `sayHello` → **Queue** → **Call Stack** → Execute

## Key Concepts Summary

### Single-Threaded Nature
- JavaScript itself runs on a **single thread**
- Asynchronous operations are handled by the **environment**
- Event Loop coordinates between JavaScript and environment

### Non-Blocking Execution
- JavaScript doesn't wait for asynchronous operations
- Continues executing other code while waiting
- Callbacks are executed when asynchronous operations complete

### Environment Dependency
- JavaScript's asynchronous capabilities depend entirely on the runtime
- Browser provides web APIs (fetch, DOM events, timers)
- Node.js provides file system, network, and timer APIs

## Important Notes for Further Learning

### What's Coming Next
- **Promises**: Modern way to handle asynchronous operations
- **Callbacks**: Traditional asynchronous handling method
- **Network calls**: Making API requests and handling responses
- **Practical projects**: Implementing real-world asynchronous scenarios

### Study Recommendations
1. **Review this diagram multiple times**
2. **Draw the Event Loop architecture yourself**
3. **Experiment with timer functions**
4. **Observe execution order in different scenarios**
5. **Practice with small asynchronous examples**

### Memory Aid
- **Async = A-sync = Not synchronized = Can have pauses**
- **Event Loop = Traffic controller for JavaScript execution**
- **Environment = The actual worker for heavy operations**
- **Queues = Waiting areas for completed operations**

This foundation is crucial for understanding all advanced JavaScript concepts including Promises, async/await, and modern web development patterns.

# 2 JavaScript Closures: Comprehensive Notes

## What is a Closure?

A **closure** is a fundamental JavaScript concept where an inner function has access to variables from its outer (enclosing) scope, even after the outer function has finished executing. In simple terms, closures are **functions that "remember" the environment in which they were created**.[1][2][3]

### Key Definition
**A closure is the combination of a function bundled together with references to its surrounding state (the lexical environment)**. The function retains access to variables from the outer scope through an internal property called `[[Environment]]`.[3][1]

### Basic Example
```javascript
function outer() {
    let counter = 0;
    
    return function() {
        counter++;  // Accesses variable from outer scope
        return counter;
    };
}

const increment = outer();
console.log(increment()); // 1
console.log(increment()); // 2
console.log(increment()); // 3
```

In this example, the inner function forms a closure with the `counter` variable, maintaining access to it even after `outer()` finishes execution.[2][4]

## How Closures Work

### Lexical Scoping Foundation
Closures are built on **lexical scoping**, which determines variable accessibility based on where variables are declared in the code structure. JavaScript functions have access to:[5][6]
- Their own scope
- Variables in outer function scopes  
- Global scope variables[5]

### Memory Management
When a function creates a closure:
1. The inner function maintains a reference to its lexical environment through `[[Environment]]`
2. The outer function's execution context normally would be destroyed, but the closure keeps the lexical environment alive
3. Variables are retained in memory as long as the closure exists[7]

**Important**: Closures only retain variables they actually reference, not the entire outer scope.[8]

## Practical Use Cases

### 1. Data Encapsulation and Private Variables
Closures enable creating private variables that cannot be accessed directly from outside:

```javascript
function createBankAccount(initialBalance) {
    let balance = initialBalance;  // Private variable
    
    return {
        getBalance: function() {
            return balance;
        },
        deposit: function(amount) {
            balance += amount;
            return balance;
        },
        withdraw: function(amount) {
            if (amount > balance) {
                console.log('Insufficient funds');
                return;
            }
            balance -= amount;
            return balance;
        }
    };
}

const account = createBankAccount(100);
console.log(account.getBalance()); // 100
account.deposit(50);
console.log(account.getBalance()); // 150
// balance is not directly accessible from outside
```

This pattern provides **data integrity** by restricting direct access to variables.[9][10]

### 2. Function Factories and Counters
Closures are perfect for creating specialized functions with pre-configured behavior:

```javascript
function createCounter(start = 0, step = 1) {
    let count = start;
    
    return function() {
        count += step;
        return count;
    };
}

const counter1 = createCounter(0, 1);
const counter2 = createCounter(100, 5);

console.log(counter1()); // 1
console.log(counter1()); // 2
console.log(counter2()); // 105
console.log(counter2()); // 110
```

Each counter maintains its own independent state.[4][11]

### 3. Module Pattern
The **Module Pattern** uses closures to create self-contained, reusable modules with public and private members:

```javascript
const counterModule = (function() {
    let count = 0;  // Private variable
    
    function privateIncrement() {  // Private method
        count++;
        console.log('Count incremented privately');
    }
    
    return {  // Public API
        increment: function() {
            count++;
            console.log(count);
        },
        decrement: function() {
            count--;
            console.log(count);
        },
        getCount: function() {
            return count;
        }
    };
})();

counterModule.increment(); // 1
counterModule.increment(); // 2
console.log(counterModule.getCount()); // 2
// count and privateIncrement are not accessible from outside
```

This pattern is widely used in JavaScript libraries and frameworks.[12][13]

### 4. Event Handlers and Callbacks
Closures preserve state in asynchronous operations and event handling:

```javascript
function setupEventHandlers() {
    let clickCount = 0;
    
    document.getElementById('button').addEventListener('click', function() {
        clickCount++;
        console.log(`Button clicked ${clickCount} times`);
    });
}
```

The event handler maintains access to `clickCount` even after `setupEventHandlers` completes.[12]

## Interview Questions and Common Patterns

### Q1: Basic Closure Understanding
```javascript
function outer() {
    var a = 10;
    function inner() {
        console.log(a);
    }
    return inner;
}

outer()(); // Output: 10
```
**Answer**: Yes, this forms a closure. The inner function retains access to variable `a` from the outer scope.[14]

### Q2: Closure with Parameters
```javascript
function outer(str) {
    let a = 10;
    function inner() {
        console.log(a, str);
    }
    return inner;
}

outer('Hello')(); // Output: 10 "Hello"
```
**Answer**: Inner functions have access to both variables and parameters of outer functions.[14]

### Q3: Loop and Closure Issue
```javascript
// Common mistake
for (var i = 0; i < 3; i++) {
    setTimeout(function() {
        console.log(i); // Prints 3, 3, 3
    }, 1000);
}

// Solution using closure
for (let i = 0; i < 3; i++) {
    setTimeout(function() {
        console.log(i); // Prints 0, 1, 2
    }, 1000);
}
```

## Memory Considerations

### Potential Memory Leaks
While closures are powerful, they can cause memory leaks if not handled properly:

1. **Unremoved Event Listeners**: Event handlers that hold references to large objects
2. **Circular References**: When closures reference objects that reference the closure back
3. **Long-lived Closures**: Closures that persist longer than necessary[15][16]

### Best Practices
- Remove event listeners when no longer needed
- Set closure references to `null` when done
- Avoid creating unnecessary closures in performance-critical code
- Be mindful of what variables closures capture[15]

## Key Benefits

1. **Data Privacy**: Create private variables and methods
2. **State Preservation**: Maintain state across function calls
3. **Module Organization**: Build self-contained, reusable modules
4. **Flexible Function Creation**: Create specialized functions dynamically
5. **Callback Management**: Handle asynchronous operations effectively[17][9]

## Summary

Closures are essential for modern JavaScript development, enabling powerful patterns like data encapsulation, module creation, and state management. They work by maintaining references to their lexical environment, allowing inner functions to access outer scope variables even after the outer function completes. While incredibly useful, developers must be mindful of memory implications and follow best practices to avoid potential leaks. Understanding closures is crucial for JavaScript interviews and building robust, maintainable applications.
# 3 JavaScript Promises - Comprehensive Study Notes

## What are Promises?

JavaScript Promises are a utility that allows you to handle asynchronous operations in a more organized and readable way. A Promise represents a value that may not be available yet but will be resolved at some point in the future[1][6].

**Key Concept**: Promises are used to handle operations that take time, such as:
- Network calls/API requests
- File operations
- Database queries
- Timer functions
- Any deliberately created asynchronous behavior

## Promise States

A Promise is always in one of three possible states[6][20][25]:

| State | Description |
|-------|-------------|
| **Pending** | The initial state - operation is still in progress |
| **Fulfilled** | Operation completed successfully - promise is resolved |
| **Rejected** | Operation failed - promise is rejected |

**Important**: Once a promise is settled (fulfilled or rejected), it becomes immutable and cannot change state[20].

## Creating a Promise

### Basic Syntax

```javascript
const fetchData = new Promise((resolve, reject) => {
    // Asynchronous operation here
    let success = true;
    
    if (success) {
        resolve("Data fetched successfully");
    } else {
        reject("Error fetching data");
    }
});
```

### Key Components:

1. **`new Promise()`** - Constructor to create a promise
2. **Executor Function** - Takes two parameters: `resolve` and `reject`
3. **`resolve()`** - Function to call when operation succeeds
4. **`reject()`** - Function to call when operation fails

### Example with setTimeout (Simulating Async Operation):

```javascript
const fetchData = new Promise((resolve, reject) => {
    setTimeout(() => {
        let success = true;
        
        if (success) {
            resolve("Data fetched successfully");
        } else {
            reject("Error fetching data");
        }
    }, 3000); // 3 second delay
});
```

## Consuming Promises

### Using .then() and .catch()

```javascript
fetchData
    .then((data) => {
        console.log(data); // Handle success
    })
    .catch((error) => {
        console.error(error); // Handle failure
    });
```

### Method Details:

- **`.then()`** - Handles the fulfilled state of a promise[21][24]
- **`.catch()`** - Handles the rejected state of a promise[8][21]
- Both methods return new promises, enabling chaining[21][28]

## Promise Chaining

One of the most powerful features of promises is the ability to chain multiple asynchronous operations[28]:

```javascript
fetchData
    .then((data) => {
        console.log(data);
        return data.toLowerCase(); // Return value for next .then()
    })
    .then((processedData) => {
        console.log(processedData); // Receives returned value
        // Can chain more operations
    })
    .catch((error) => {
        console.error(error); // Catches any error in the chain
    });
```

### Chaining Benefits:
- Eliminates callback hell
- Makes code more readable and maintainable
- Each `.then()` returns a new promise
- Single `.catch()` can handle errors for the entire chain[28]

## Asynchronous Nature of JavaScript

### Why Promises are Always Asynchronous

JavaScript promises are **always asynchronous** regardless of whether they contain synchronous or asynchronous functions[1]. This is by design to ensure consistent behavior and prevent blocking the main thread.

### Event Loop and Promise Execution

When a promise is executed:
1. The promise goes into a **pending** state
2. JavaScript continues executing other synchronous code
3. When the promise settles, callbacks are queued in the **microtask queue**
4. The **event loop** processes these callbacks when the call stack is empty[5]

## Error Handling Best Practices

### Proper Error Handling Chain:

```javascript
fetch('/api/data')
    .then(response => response.json())
    .then(data => {
        // Process data
        return processedData;
    })
    .then(result => {
        // Use result
    })
    .catch(error => {
        // Handle any error in the chain
        console.error('Error:', error);
    });
```

### Important Notes:
- Place `.catch()` at the end to handle all errors in the chain[16]
- The order of `.then()` and `.catch()` matters significantly[23]
- Errors "bubble up" to the nearest `.catch()` handler[16]

## Advanced Promise Methods

### Promise.all()
Waits for all promises to resolve; rejects if any promise rejects[6][25]:

```javascript
Promise.all([promise1, promise2, promise3])
    .then(results => {
        // Array of all results
    })
    .catch(error => {
        // Any rejection
    });
```

### Promise.allSettled()
Waits for all promises to settle regardless of outcome[25]:

```javascript
Promise.allSettled([promise1, promise2, promise3])
    .then(results => {
        // Array of outcome objects
    });
```

## Common Patterns and Tips

### 1. Returning Values in .then()
Whatever you return from a `.then()` callback becomes the resolved value for the next `.then()` in the chain[12].

### 2. Promise vs Async/Await
- Promises use `.then()` and `.catch()` chaining
- Async/await is syntactic sugar that makes promise-based code look synchronous[7][15]

### 3. Error Propagation
Errors in promise chains propagate down until caught by a `.catch()` handler[16].

## Key Takeaways

1. **Promises solve callback hell** - They provide a cleaner way to handle asynchronous operations
2. **Always asynchronous** - Promises are non-blocking by design
3. **Three states** - Pending, fulfilled, or rejected
4. **Immutable once settled** - Cannot change state after resolution
5. **Chainable** - `.then()` and `.catch()` return new promises
6. **Error handling** - Use `.catch()` for comprehensive error management
7. **Method chaining** - Enables sequential processing of asynchronous operations

## Practical Example

```javascript
// Creating a promise-based function
function fetchUserData(userId) {
    return new Promise((resolve, reject) => {
        // Simulate API call
        setTimeout(() => {
            if (userId) {
                resolve({ id: userId, name: "John Doe" });
            } else {
                reject("User ID is required");
            }
        }, 2000);
    });
}

// Consuming the promise
fetchUserData(123)
    .then(user => {
        console.log("User fetched:", user);
        return user.name.toUpperCase();
    })
    .then(uppercaseName => {
        console.log("Processed name:", uppercaseName);
    })
    .catch(error => {
        console.error("Error:", error);
    });
```

This comprehensive understanding of promises forms the foundation for modern JavaScript asynchronous programming and prepares you for more advanced concepts like async/await.

# 4 JavaScript Prototypal Inheritance: A Complete Guide

Prototypal inheritance is one of JavaScript's fundamental concepts that enables objects to inherit properties and methods from other objects. This powerful mechanism allows for code reuse, memory efficiency, and the creation of complex object hierarchies without traditional classes.

## What is Prototypal Inheritance?

Prototypal inheritance is JavaScript's method of allowing objects to inherit properties and methods from other objects through a prototype chain. Unlike classical inheritance found in languages like Java or C++, JavaScript uses a prototype-based approach where objects directly inherit from other objects.[1][2]

Every object in JavaScript has an internal property called `[[Prototype]]` (accessible through `__proto__` or `Object.getPrototypeOf()`) that references another object called its prototype. When you try to access a property on an object, JavaScript first checks the object itself, and if the property isn't found, it searches up the prototype chain until it finds the property or reaches the end of the chain.[3][4]

## How the Prototype Chain Works

The prototype chain operates through a simple lookup mechanism:[5]

1. **Object Property Check**: JavaScript first looks for the property on the object itself
2. **Prototype Search**: If not found, it checks the object's prototype
3. **Chain Traversal**: This process continues up the prototype chain
4. **End of Chain**: The search stops when the property is found or `null` is reached

Here's a basic example demonstrating this concept:

```javascript
const parent = {
  greet: function() {
    console.log("Hello from the parent object!");
  }
};

const child = Object.create(parent);
child.sayHi = function() {
  console.log("Hi from the child object!");
};

child.greet(); // "Hello from the parent object!"
child.sayHi(); // "Hi from the child object!"
```

The `child` object doesn't have a `greet` method, so JavaScript searches up the prototype chain and finds it in the `parent` object.[4]

## Constructor Functions and Prototypal Inheritance

Constructor functions provide a common way to implement prototypal inheritance. When you create a function in JavaScript, it automatically gets a `prototype` property that can be used to add shared methods and properties.[6]

### Basic Constructor Example

```javascript
function Person(name) {
  this.name = name;
}

// Adding a method to the prototype
Person.prototype.greet = function() {
  console.log(`Hello, my name is ${this.name}`);
};

const hitesh = new Person("Hitesh");
hitesh.greet(); // "Hello, my name is Hitesh"
```

In this example:[7]
- The `Person` function serves as a constructor
- `Person.prototype.greet` adds a shared method to all `Person` instances
- The `hitesh` object can access the `greet` method through prototype inheritance
- All instances of `Person` share the same `greet` method, making it memory efficient

## Key Concepts and Properties

### The `__proto__` Property

The `__proto__` property provides direct access to an object's prototype. While useful for understanding, it's deprecated in favor of `Object.getPrototypeOf()` and `Object.setPrototypeOf()` for production code.[8][9]

```javascript
function Test() {}
Test.prototype.myName = function() {
  console.log("myName");
};

const test = new Test();
console.log(test.__proto__ === Test.prototype); // true
test.myName(); // "myName"
```

### Difference Between `prototype` and `__proto__`

Understanding the distinction is crucial:[10]

- **`prototype`**: A property of constructor functions that becomes the prototype for instances created with `new`
- **`__proto__`**: A property of object instances that points to their actual prototype

```javascript
function Person(name) {
  this.name = name;
}

Person.prototype.age = 25;

const willem = new Person('Willem');

console.log(willem.__proto__ === Person.prototype); // true
console.log(willem.age); // 25 (found through prototype chain)
```

## Advanced Inheritance Patterns

### Using Object.create()

`Object.create()` provides a clean way to set up prototype inheritance:[11]

```javascript
// Shape - superclass
function Shape() {
  this.x = 0;
  this.y = 0;
}

Shape.prototype.move = function(x, y) {
  this.x += x;
  this.y += y;
  console.log("Shape moved.");
};

// Rectangle - subclass
function Rectangle() {
  Shape.call(this); // call super constructor
}

// Set up inheritance
Rectangle.prototype = Object.create(Shape.prototype);
Rectangle.prototype.constructor = Rectangle;

const rect = new Rectangle();
rect.move(1, 1); // "Shape moved."
```

This pattern:[12]
- Creates proper inheritance between `Rectangle` and `Shape`
- Maintains the constructor reference
- Allows method overriding and extension

## Memory Efficiency and Performance

Prototypal inheritance offers significant memory advantages. Methods defined on prototypes are shared across all instances rather than duplicated:[13]

```javascript
function Circle(radius) {
  this.r = radius;
}

Circle.prototype.area = function() {
  return Math.PI * this.r * this.r;
};

const c1 = new Circle(3);
const c2 = new Circle(5);

// Both instances share the same area method
console.log(c1.area === c2.area); // true
```

## Common Interview Questions and Examples

Prototypal inheritance is frequently tested in JavaScript interviews. Here are typical scenarios:[14][15]

### Adding Methods to Built-in Prototypes

```javascript
// Adding a sum method to Array prototype
Array.prototype.sum = function() {
  let sum = 0;
  for (let i = 0; i < this.length; i++) {
    sum += this[i];
  }
  return sum;
};

const arr1 = [1, 2, 3, 4, 5];
console.log(arr1.sum()); // 15
```

### Demonstrating Property Lookup

```javascript
const animal = {
  type: "Unknown",
  makeSound: function() {
    console.log(`The ${this.type} makes a sound.`);
  }
};

const dog = Object.create(animal);
dog.type = "Dog";
dog.makeSound(); // "The Dog makes a sound."
```

## Best Practices and Modern Considerations

While understanding prototypal inheritance is essential, modern JavaScript development often uses ES6 classes, which provide syntactic sugar over the prototype system. However, the underlying mechanism remains the same.[11]

**Key recommendations**:
- Avoid directly manipulating `__proto__` in production code[9]
- Use `Object.create()` or `Object.setPrototypeOf()` for setting up inheritance
- Understand that ES6 classes are built on top of prototypes
- Be mindful of performance implications in deep prototype chains[16]

## Summary

Prototypal inheritance is JavaScript's mechanism for sharing properties and methods between objects through prototype chains. This system enables memory-efficient code reuse and forms the foundation of JavaScript's object-oriented capabilities. Whether using constructor functions, `Object.create()`, or modern ES6 classes, understanding prototypal inheritance is essential for mastering JavaScript and succeeding in technical interviews.[17]

The concept demonstrates JavaScript's unique approach to inheritance: **objects inherit from objects**, creating a flexible and powerful system for building complex applications while maintaining performance and memory efficiency.[17]

[1](https://stackoverflow.com/questions/12201082/prototypal-inheritance-concept-in-javascript-as-a-prototype-based-language)
[2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Inheritance_and_the_prototype_chain)
[3](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Advanced_JavaScript_objects/Object_prototypes)
[4](https://www.geeksforgeeks.org/javascript/prototype-inheritance-in-javascript/)
[5](https://dev.to/shingaiz/detailed-explanation-of-javascript-prototype-chain-prototype-1392)
[6](https://www.geeksforgeeks.org/javascript/js-constructor-method/)
[7](https://www.explainthis.io/en/swe/most-common-js-prototype-questions)
[8](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/proto)
[9](https://www.linkedin.com/pulse/what-prototype-inheritance-javascript-amit-kumar)
[10](https://stackoverflow.com/questions/9959727/what-is-the-difference-between-prototype-and-proto)
[11](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)
[12](https://www.geeksforgeeks.org/javascript/js-prototype/)
[13](https://www.toptal.com/javascript/javascript-prototypes-scopes-and-performance-what-you-need-to-know)
[14](https://www.alooba.com/skills/concepts/javascript-49/prototypal-inheritance/)
[15](https://dev.to/codecraftjs/prototypal-inheritance-in-javascript-3fjc)
[16](https://www.dhiwise.com/post/prototype-chains-in-javascript-understanding-advanced-techniques)
[17](https://dmitripavlutin.com/javascript-prototypal-inheritance/)
[18](https://javascript.info/prototype-inheritance)
[19](https://playcode.io/javascript/prototype)
[20](https://www.greatfrontend.com/questions/quiz/explain-how-prototypal-inheritance-works)
[21](https://www.greatfrontend.com/questions/quiz/what-is-the-prototype-chain-and-how-does-it-work)
[22](https://www.hellojavascript.info/docs/general-javascript-questions/prototypes-inheritance/function-prototype)
[23](https://isamatov.com/javascript-prototype-vs-constructor/)
[24](https://www.youtube.com/watch?v=wstwjQ1yqWQ)
[25](https://www.interviewbit.com/javascript-interview-questions/)
[26](https://www.geeksforgeeks.org/javascript/understanding-the-prototype-chain-in-javascript/)
[27](https://www.w3schools.com/js/js_object_prototypes.asp)
[28](https://www.youtube.com/watch?v=76cHJkx_S3o)
[29](https://dev.to/jps27cse/understanding-javascript-prototypes-a-key-to-mastering-oop-1j1b)
[30](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__lookupGetter__)
[31](https://stackoverflow.com/questions/18298435/prototype-and-constructor-in-javascript-plain-english)
[32](https://www.geeksforgeeks.org/javascript/difference-between-proto-and-prototype/)
[33](https://stackoverflow.com/questions/3079887/javascript-inheritance-with-object-create)


# 5 SQL Crash Course: Complete Database Operations Guide

## Overview
This comprehensive SQL crash course covers everything from basic database creation to advanced CRUD operations, providing a practical foundation for working with relational databases like PostgreSQL and MySQL.

## Table of Contents
1. [Database Setup](#database-setup)
2. [Table Creation & Data Types](#table-creation--data-types)
3. [Data Insertion](#data-insertion)
4. [Querying Data](#querying-data)
5. [Data Updates](#data-updates)
6. [Data Deletion](#data-deletion)
7. [Best Practices](#best-practices)

---

## Database Setup

### Creating a Database
**GUI Method:**
- Right-click on PostgreSQL server
- Select "Create" → "Database"
- Enter database name (e.g., "chai_store_db")
- Save

**SQL Command Method:**
```sql
CREATE DATABASE chai_store_db;
```

### Accessing Query Tool
- Right-click on your database
- Select "Query Tool" to open SQL editor
- This is where you'll write and execute SQL commands

---

## Table Creation & Data Types

### Basic Table Structure
```sql
CREATE TABLE chai_store (
    id SERIAL PRIMARY KEY,
    chai_name VARCHAR(50),
    price DECIMAL(5,2),
    chai_type VARCHAR(50),
    available BOOLEAN
);
```

### Data Types Explained

#### **VARCHAR(n)**
- Variable-length character strings
- `n` specifies maximum length
- Uses only the space needed (efficient storage)
- Example: `VARCHAR(50)` can store up to 50 characters

#### **DECIMAL(precision, scale)**
- Fixed-point numbers for precise calculations
- `precision`: Total number of significant digits
- `scale`: Number of digits after decimal point
- Example: `DECIMAL(5,2)` stores numbers like 999.99
- Perfect for currency and financial data

#### **BOOLEAN**
- Stores true/false values
- Can accept: `TRUE`, `FALSE`, `NULL`
- PostgreSQL also accepts: `1`, `0`, `yes`, `no`, `y`, `n`, `t`, `f`

#### **SERIAL**
- Auto-incrementing integer
- Automatically generates unique sequential numbers
- Commonly used for primary keys
- Starts at 1 and increments by 1 for each new record

#### **PRIMARY KEY**
- Ensures unique identification for each row
- Optimizes database performance through indexing
- Cannot be NULL or duplicate
- Essential for relational database integrity

---

## Data Insertion

### Single Record Insertion
```sql
INSERT INTO chai_store (chai_name, price, chai_type, available)
VALUES ('masala chai', 30.00, 'spiced', TRUE);
```

### Multiple Records Insertion
```sql
INSERT INTO chai_store (chai_name, price, chai_type, available)
VALUES 
    ('masala chai', 30.00, 'spiced', TRUE),
    ('green chai', 25.00, 'herbal', TRUE),
    ('black chai', 20.00, 'classic', TRUE),
    ('iced chai', 35.00, 'cold', FALSE),
    ('oolong', 40.00, 'specialty', TRUE);
```

**Key Points:**
- No need to specify `id` - it's auto-generated by SERIAL
- Use single quotes for string values
- Multiple values separated by commas
- Each row in parentheses

---

## Querying Data

### Basic SELECT Operations

#### Select All Data
```sql
SELECT * FROM chai_store;
```

#### Select Specific Columns
```sql
SELECT chai_name, price FROM chai_store;
```

#### Using Column Aliases
```sql
SELECT 
    chai_name AS "Chai Name",
    price AS "Cost in INR"
FROM chai_store;
```

### Filtering with WHERE Clause

#### Pattern Matching with LIKE
```sql
-- Find all chai varieties containing "chai"
SELECT * FROM chai_store 
WHERE chai_name LIKE '%chai%';

-- Find items starting with "iced"
SELECT * FROM chai_store 
WHERE chai_name LIKE 'iced%';
```

**Wildcard Patterns:**
- `%` - Matches any sequence of characters
- `_` - Matches any single character

#### Comparison Operations
```sql
-- Items less than ₹30
SELECT * FROM chai_store 
WHERE price < 30;

-- Exact match
SELECT * FROM chai_store 
WHERE chai_name = 'black chai';
```

### Sorting Results
```sql
-- Highest to lowest price
SELECT * FROM chai_store 
ORDER BY price DESC;

-- Lowest to highest price (default)
SELECT * FROM chai_store 
ORDER BY price ASC;
```

---

## Data Updates

### UPDATE Syntax
```sql
UPDATE table_name 
SET column1 = value1, column2 = value2 
WHERE condition;
```

### Example: Update Price and Availability
```sql
UPDATE chai_store 
SET price = 38.00, available = TRUE 
WHERE chai_name = 'iced chai';
```

**Critical Safety Rule:**
- **Always use WHERE clause** with UPDATE
- Without WHERE, it updates ALL rows in the table
- Test with SELECT first to verify which rows will be affected

---

## Data Deletion

### DELETE Syntax
```sql
DELETE FROM table_name 
WHERE condition;
```

### Example: Remove a Product
```sql
DELETE FROM chai_store 
WHERE chai_name = 'black chai';
```

**Safety Guidelines:**
- **Always use WHERE clause** with DELETE
- Test with SELECT first: `SELECT * FROM chai_store WHERE chai_name = 'black chai';`
- Without WHERE, it deletes ALL rows in the table

---

## Best Practices

### 1. **Query Safety**
- Always test SELECT queries before UPDATE/DELETE operations
- Use WHERE clauses to limit scope of modifications
- Double-check conditions before executing destructive operations

### 2. **Data Types**
- Choose appropriate data types for storage efficiency
- Use DECIMAL for financial data requiring precision
- Use VARCHAR instead of CHAR for variable-length text
- Use BOOLEAN for true/false flags

### 3. **SQL Formatting**
- Use consistent capitalization (keywords in UPPERCASE recommended)
- Format multi-line queries for readability
- End statements with semicolons
- Use meaningful column and table names

### 4. **Performance Considerations**
- Primary keys automatically create indexes for fast lookups
- Use appropriate data type sizes (don't over-allocate)
- Consider indexing frequently queried columns

### 5. **Naming Conventions**
- Use descriptive names for tables and columns
- Use underscores for multi-word names (e.g., `chai_name`)
- Be consistent across your database schema

---

## Common SQL Operators Summary

| Operator | Description | Example |
|----------|-------------|---------|
| `=` | Equal to | `price = 30` |
| `<` | Less than | `price < 30` |
| `>` | Greater than | `price > 30` |
| `<=` | Less than or equal | `price <= 30` |
| `>=` | Greater than or equal | `price >= 30` |
| `<>` or `!=` | Not equal | `price <> 30` |
| `LIKE` | Pattern matching | `name LIKE '%chai%'` |
| `IN` | In a list of values | `type IN ('spiced', 'herbal')` |
| `BETWEEN` | Within a range | `price BETWEEN 20 AND 40` |
| `IS NULL` | Is null value | `description IS NULL` |
| `IS NOT NULL` | Is not null | `description IS NOT NULL` |

---

## Case Study: Chai Store Database

The tutorial uses a practical example of managing a chai store's inventory with the following requirements:

1. **Database**: `chai_store_db`
2. **Table**: `chai_store`
3. **Columns**:
   - `id`: Auto-incrementing primary key
   - `chai_name`: Product name (up to 50 characters)
   - `price`: Price with 2 decimal places
   - `chai_type`: Category/type of chai
   - `available`: Boolean flag for availability

This real-world scenario demonstrates how SQL databases are used in business applications for inventory management, reporting, and data analysis.

---

## Conclusion

This crash course provides a solid foundation in SQL that applies across different database systems (PostgreSQL, MySQL, SQLite, etc.). The core SQL commands and concepts covered here are standardized and will work with minimal variations across different platforms.

**Next Steps:**
- Practice with more complex queries involving JOINs
- Learn about database relationships and foreign keys
- Explore advanced features like views, stored procedures, and triggers
- Study database design principles and normalization
- Practice with real-world datasets

**Remember**: SQL is a powerful tool for data management, and mastering these fundamentals opens doors to advanced database operations, data analysis, and backend development opportunities.