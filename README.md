# Programming Paradigms

Programming paradigms define how you structure and organize your code. They shape the way you think about problems and design solutions.

## Main Paradigms

1. **Object-Oriented Programming (OOP)**
2. **Procedural Programming**
3. **Functional Programming**

## 🧱 Object-Oriented Programming (OOP)

### Key Concepts:
- Organizes code into **objects** (instances of **classes**)
- Combines data (**properties**) and behavior (**methods**) together
- Models real-world entities and relationships

# Programming Paradigms

## Object-Oriented Programming (OOP)

In OOP, you organize your code using **classes** and **objects**:
- Data is stored in object **properties**
- Logic is encapsulated in object **methods**
- Your entire application is modeled using classes that represent real-world concepts
- Objects are instances of these classes that interact with each other

**Example (E-commerce Application):**
- `Product` class with properties like `name`, `price`, and `quantity`
- `ShoppingCart` class to manage selected products
- `User` class to handle customer information

## Procedural Programming

Procedural programming is often the first paradigm beginners encounter:
- Follows a **linear, top-down** execution flow
- Code consists of a sequence of procedures or functions
- Data and functions are kept separate (no encapsulation)
- Typically uses shared mutable state

**Characteristics:**
- Simple to write for small programs
- Can become difficult to maintain as complexity grows
- Common in scripting and low-level programming

## Functional Programming

Functional programming emphasizes:
- **Pure functions** (same input always produces same output)
- **Immutable data** (no side effects)
- Functions as first-class citizens
- Clear separation between data and behavior

**Key Principles:**
1. Functions should perform single, well-defined tasks
2. Data is passed explicitly via parameters
3. Functions often return new data rather than modifying inputs
4. Encourages function composition over inheritance

## Comparison

| Aspect          | OOP                     | Procedural              | Functional              |
|-----------------|-------------------------|-------------------------|-------------------------|
| **Organization**| Classes & Objects       | Procedures              | Pure Functions          |
| **State**       | Mutable                 | Mutable                 | Immutable               |
| **Focus**       | Data + Behavior         | Execution Steps         | Data Transformations    |
| **Approach**    | Real-world modeling     | Imperative              | Declarative             |
  



