# PowerShell GUI Calculator

## Overview
This calculator uses Windows Forms to provide a graphical user interface (GUI) in PowerShell. It allows users to input two numbers, choose a math operator from a dropdown list, and instantly see the result. A built-in tooltip explains what each operator means.

## Features
- GUI interface with form inputs
- Supports basic math operators: `+`, `-`, `*`, `/`, `%`, `^`
- Input validation with error handling
- Hoverable tooltip for operator definitions

## Supported Operators

| Operator | Function        | Example            | Description                               |
|----------|------------------|--------------------|-------------------------------------------|
| `+`      | Addition          | `5 + 3 = 8`         | Adds two numbers                          |
| `-`      | Subtraction       | `9 - 4 = 5`         | Subtracts the second from the first       |
| `*`      | Multiplication    | `2 * 3 = 6`         | Multiplies both numbers                   |
| `/`      | Division          | `8 / 2 = 4`         | Divides first by second; blocks division by zero |
| `%`      | Modulus           | `10 % 3 = 1`        | Returns remainder of division             |
| `^`      | Exponentiation    | `2 ^ 3 = 8`         | Raises first number to the power of the second |

## How to Run

1. Save the script as `calc.ps1`.
2. Open PowerShell.
3. Run the script with:

```powershell
powershell -ExecutionPolicy Bypass -File "C:\path\to\calc.ps1"
```
Requirements
- Windows OS with PowerShell 5.0+
- .NET Framework for Windows Forms support
