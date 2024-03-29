## .NET Types:

Types in .NET represent data structures and behaviors that define objects in a program.
Examples of types include classes, structs, interfaces, enums, delegates, and primitive data types (e.g., int, string).
Types define the blueprint for objects, specifying their properties, methods, and behavior.

## Overview of .NET Data Types

### Classes:

- Classes are reference types used to define blueprints for objects in .NET.
- They encapsulate data (fields) and behavior (methods) into a single unit.
- Objects created from classes can be instantiated multiple times.
- Classes support inheritance, allowing one class to derive from another.

### Structs:

- Structs are lightweight, value types used to represent small, simple data structures.
- They are typically used for small, immutable data types.
- Structs are stored on the stack and are often used for performance-critical scenarios.
- Unlike classes, structs do not support inheritance and are passed by value.

### Interfaces:

- Interfaces define a contract specifying a set of members (methods, properties, events) that implementing classes must provide.
- They enable polymorphism and abstraction by allowing multiple classes to implement the same interface.
- Interfaces cannot contain implementation; they only define the structure that implementing classes must adhere to.
- Classes can implement multiple interfaces.

### Enums (Enumerations):

- Enums are value types used to define named constants.
- They provide a way to represent a set of named integral constants.
- Enums improve code readability and maintainability by giving meaningful names to numeric values.
- Each enum member has an underlying integer value, which can be explicitly specified or auto-assigned.

### Delegates:

- Delegates are reference types used to define method signatures.
- They enable a type-safe way to encapsulate and pass around methods as objects.
- Delegates are similar to function pointers in other languages.
- They are often used for implementing callbacks, event handling, and asynchronous programming.

### Primitive Data Types:

- Primitive data types represent basic data values built into the programming language.
- Examples include integers (int, long), floating-point numbers (float, double), characters (char), and Booleans (bool).
- Primitive data types are used to store simple values directly in memory.
- They provide the building blocks for more complex data structures and operations in a program.

## .NET nameSpaces

- a library of related classes in .net called nameSpace. Namespaces are used to organize and group related types in .NET.

- They provide a way to avoid naming conflicts between types with the same name by organizing them

- the Frame Class library of .Net contains thousands of types of classes under a single namespace

- in addition namespaces can contain Typs, utility data types, format types and ganerators which can generate random numbers and perform math operations.

### Standard and non-standard nameSpaces:

## standard

1. **System.Collections**

- include the popular collection types like stacks, queues, Hash tables etc

2. **System.Diagnostics**

- Allow us to diagnose applications
- provide event logging, tracing, performance counters

3. **System.Globlization**

- provide info and format patteren for calanders, dates, currency and nembers

4. **System.IO**

- provide connection to file system

5. **Syatem.Reflection**

- inspects metadata

6. **System.Security**

- help to protect data and resources
- provide services like cryptography

7. **Syatem.Text**

- support encodings like ASCII or UNICODE
- support regular strings

8. **System.Net**

- provide network communication
- provide interface for protocols like Http, https, ftp

9. **System.Threading**

- allow multithreading and syncronization

## non-standard

1. **System.Configuration**

- provide structure for handling configurations

2. **System.CodeDom**

- provide ability to create Doms that can run code in real-Time

3. **System.Drawing**

- provide ability to manuplate 2d and vector graphics

4. **System.Media**

- provide ability to play Sounds and .wav files

5. **System.Web**

- web related functionality

6. **System.WindowsForms**

- used to Windows build GUI apps
