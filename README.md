# Factorial Calculator

This is a COBOL program that calculates the factorial of a given number. Follow the instructions below to compile and run the program.

---

## Prerequisites

1. **Install a COBOL Compiler**:
   - Download and install [GnuCOBOL](https://sourceforge.net/projects/open-cobol/), a free and open-source COBOL compiler.

2. **Verify Installation**:
   - Ensure the compiler is correctly installed by running the following command:
     ```bash
     cobc -v
     ```
   - You should see version details of the COBOL compiler.

---

## Save the Program

1. Copy the COBOL code into a file named `factorial.cbl`.

---

## Compile the Program

1. Open a terminal and navigate to the directory where you saved `factorial.cbl`.

2. Run the following command to compile the program:
   ```bash
   cobc -x -o factorial factorial.cbl

