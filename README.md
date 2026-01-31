
# Food Ordering System (x86 Assembly)

A console-based food ordering system implemented in x86 assembly language with user authentication, shopping cart, and sales reporting features.

## Features
- User registration and login system
- Member and staff access levels
- Interactive food menu with multiple categories
- Shopping cart functionality
- Order management and tracking
- Sales report generation for staff
- Input validation and error handling

## Installation
```bash
# clone the repo
git clone https://github.com/yourusername/food-ordering-system.git

# assemble and link using MASM/TASM
masm ass.asm;
link ass.obj;

# or using DOSBox
dosbox
masm ass.asm
link ass.obj
ass.exe
```

## Requirements
- MASM (Microsoft Macro Assembler) or TASM (Turbo Assembler)
- DOS environment or DOSBox emulator
- x86 compatible system

## Usage
Run the executable in a DOS environment:
```
ass.exe
```

Follow the on-screen menu to:
1. Register as a new user
2. Login as member or staff
3. Browse food categories and add items to cart
4. View and manage orders
5. Generate sales reports (staff only)

## Project Structure
- `ass.asm` - Main assembly source code containing all program logic and procedures

## Notes
This project was developed as a Computer System Architecture (CSA) assignment demonstrating low-level programming concepts including:
- DOS interrupts for I/O operations
- Memory management and data structures
- Macro definitions for code reusability
- Procedural programming in assembly language
