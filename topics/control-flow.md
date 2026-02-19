# Control Flow

Control flow determines how a program makes decisions and repeats actions.

At its core, control flow answers two questions:

1. Should this code execute?
2. How many times should this code execute?

---

## Core Constructs

### 1. Conditional Statements

- `if`
- `if-else`
- `if-else if-else`

Purpose:
Execute logic only when a condition evaluates to true.

Mental Model:
A branching path. The program evaluates a boolean expression and selects one path.

Example (conceptual):

```
if (condition) {
execute A
} else {
execute B
}
```


---

### 2. Loops

- `while`
- `for`
- `do-while`

Purpose:
Repeat logic until a condition changes.

Mental Model:
A controlled repetition engine.

Important distinction:
- `while` checks before execution
- `do-while` checks after execution
- `for` is structured for counting/iteration

---

## Common Mistakes

- Off-by-one errors in loops
- Forgetting to update loop counters
- Using assignment (`=`) instead of comparison (`==`)
- Writing overly nested conditionals instead of simplifying logic
- Failing to consider edge cases

---

## Real-World Application

Control flow is foundational in:

- Input validation
- Authentication logic
- Payment processing decisions
- API request routing
- State machines
- Retry mechanisms

Nearly every production system relies heavily on accurate conditional logic.

---

## Refinement Notes

From experience, the biggest improvements in control flow come from:

- Writing logic on paper before coding
- Simplifying nested conditions
- Naming boolean variables clearly
- Testing edge cases early

Strong control flow reduces defects more than clever syntax ever will.


