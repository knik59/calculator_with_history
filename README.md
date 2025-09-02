# Command-Line Calculator with History Management

The **Command-Line Calculator with History Management** is a Python-based project designed to perform both simple and advanced mathematical operations. Unlike traditional calculators that only handle two numbers, this system allows users to enter multi-digit numbers, decimals, and multiple operands in one expression. It follows the **BODMAS rule**, ensuring accurate results, and supports parentheses for grouping.  

Along with solving expressions, the calculator keeps a **history of all calculations with timestamps**, making it both practical and educational.


## Key Functionalities

### Arithmetic Operations
- Performs basic calculations: addition, subtraction, multiplication, and division.  
- Supports advanced operators like modulus (`%`) and exponentiation (`**`).  

### Multi-Operand and Multi-Digit Support
- Handles more than two operands in a single expression.  
- Accepts large multi-digit numbers and decimal values.  

### BODMAS and Parentheses Handling
- Follows **BODMAS/PEMDAS** precedence rules for correct evaluations.  
- Allows the use of parentheses to manage complex expressions.  

### History Management
- Saves every equation, its result, and the timestamp in a history file.  
- Provides commands to view past history or clear history completely.  

### Error Handling
- Detects division by zero and invalid inputs with proper warnings.  

## Usage
1. Run the program in the terminal.  
2. Enter mathematical expressions directly.  
3. Use commands like:
   - `his` → Show past calculations.  
   - `cl` → Clear saved history.  
   - `ex` → Quit the calculator.  
