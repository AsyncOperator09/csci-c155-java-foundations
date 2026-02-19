# Variables and Data Types

Variables represent state.

State is what programs manipulate, store, and evaluate.

Understanding data types is foundational because all logic depends on correct data representation.

---

## Core Concepts

### 1. Primitive Types

Common primitives in Java:

- `int`
- `double`
- `boolean`
- `char`

These represent single, fixed-size values stored directly in memory.

Mental Model:
A labeled container holding a specific type of value.

---

### 2. Reference Types

Examples:

- `String`
- Arrays
- Objects

Reference variables store memory addresses, not raw values.

Mental Model:
A variable pointing to a location in memory.

This distinction becomes critical when learning:
- Functions
- Parameter passing
- Memory references
- Object-oriented programming

---

## Declaration Structure

Conceptual structure:

`type variableName = value;`


Key components:
- Type defines allowed operations
- Name identifies state
- Value initializes the variable

---

## Common Mistakes

- Using incorrect data type for required precision
- Forgetting initialization
- Confusing primitives with references
- Not understanding default values
- Misinterpreting how Strings behave

---

## Real-World Application

Correct data typing influences:

- Memory efficiency
- Precision in financial systems
- Performance in data-heavy applications
- API contracts and validation
- Database mapping

Incorrect data modeling leads to long-term system fragility.

---

## Refinement Notes

Formal study reinforces:

- The importance of explicit typing
- Thinking about data size and precision
- Recognizing when abstraction is needed
- Understanding how data flows through functions

Everything in programming begins with representing state correctly.
