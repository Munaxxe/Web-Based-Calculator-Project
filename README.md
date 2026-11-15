# Web-Based Calculator

A lightweight browser-based calculator built with **HTML, CSS and
JavaScript**. The project demonstrates how core web technologies can be
combined to create an interactive calculator interface with basic
arithmetic functionality.

## Overview

The **Munaxxe Web-Based Calculator** is a simple interactive calculator
that runs directly in a web browser. It provides a visual keypad for
entering numbers and arithmetic operators, displays the current
expression, and evaluates the expression when the equals button is
selected.

The interface is built with HTML, styled using CSS and made interactive
through JavaScript functionality embedded in the HTML document.

The project focuses on the fundamentals of front-end development,
including page structure, CSS Grid layout, event handling and basic
expression evaluation.

## Features

-   **Basic arithmetic:** Supports addition, subtraction, multiplication
    and division.
-   **Interactive keypad:** Enter values using the on-screen number and
    operator buttons.
-   **Double-zero input:** Includes a dedicated `00` button for quicker
    number entry.
-   **Clear function:** The `C` button clears the current display.
-   **Expression evaluation:** The equals (`=`) button evaluates the
    entered arithmetic expression.
-   **Information button:** Displays a project attribution message.
-   **Custom interface:** Uses a dark page background, blue keypad
    buttons and a contrasting display.
-   **Browser-based:** Runs in a modern web browser without a separate
    installation process.

## Interface

The calculator interface is arranged using CSS Grid. Its display spans
the keypad width, while the number and operator controls are positioned
in a compact calculator layout.

The styling uses a black background, blue controls and a Poppins
typeface to establish the visual identity of the application.

## Technologies Used

  -----------------------------------------------------------------------
  Technology                          Role
  ----------------------------------- -----------------------------------
  HTML5                               Defines the calculator structure,
                                      display and interactive controls

  CSS3                                Handles layout, typography, colours
                                      and button styling

  JavaScript                          Processes button interactions and
                                      evaluates arithmetic expressions
  -----------------------------------------------------------------------

## Project Structure

``` text
Web-Based-Calculator-Project/
├── index.html    # Calculator structure and button functionality
├── style.css     # Calculator layout and visual styling
└── README.md     # Project documentation
```

## Getting Started

### Requirements

-   A modern web browser.
-   Git, if you want to clone the repository.

No package manager, framework or build tools are required.

### Run Locally

1.  Clone the repository:

    ``` bash
    git clone https://github.com/Munaxxe/Web-Based-Calculator-Project.git
    ```

2.  Open the project folder:

    ``` bash
    cd Web-Based-Calculator-Project
    ```

3.  Open `index.html` in your preferred web browser.

4.  Use the on-screen buttons to enter an expression and select `=` to
    calculate the result.

## How It Works

1.  The HTML document defines the calculator display and keypad.
2.  Each keypad control updates the display when selected.
3.  The clear control resets the display.
4.  The equals control evaluates the expression currently shown in the
    display.
5.  CSS Grid and styling rules organise the controls and define the
    calculator's appearance.

## Current Scope and Limitations

The current implementation is intentionally simple. It supports the four
basic arithmetic operators through the on-screen keypad.

The current version does not implement a dedicated scientific mode,
calculation history, keyboard input, parentheses, or a separate
expression parser. Decimal input is also not provided by the current
keypad.

The equals button currently uses JavaScript's `eval()` function to
evaluate the display expression. This is a concise approach for a small
demonstration, but it is not recommended for production applications. A
more robust implementation would use a restricted expression parser that
validates permitted tokens and operators before calculation.

## Potential Improvements

-   Add decimal-point input and support for negative values.
-   Implement keyboard input.
-   Add backspace and improved input validation.
-   Support parentheses and operator precedence through a dedicated
    expression parser.
-   Replace `eval()` with a safer calculation engine.
-   Add calculation history.
-   Improve responsiveness and accessibility across screen sizes.
-   Add automated tests for arithmetic operations and invalid
    expressions.

## Author

**Munashe Walter Jojo**

Industrial Electronics Engineering \| Programming \| Prototyping

-   GitHub: [@Munaxxe](https://github.com/Munaxxe)
-   Project repository: [Web-Based Calculator
    Project](https://github.com/Munaxxe/Web-Based-Calculator-Project)

------------------------------------------------------------------------

*An exploration of front-end development through practical interface
design and interactive programming.*
