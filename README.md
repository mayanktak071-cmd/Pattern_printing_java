Pattern Printing Project – Java

A console-based Java application that prints various geometric and artistic patterns such as Triangle, Swastik, Diamond, Hourglass, Spider Web, Real Arrow, and more.
The program uses loops, conditions, and mathematical logic to render complex patterns using characters like * and X.


📌 Summary

This project is a menu-driven Java application that allows users to choose from different patterns and print them according to a user-entered size.


Key features:
  - Pattern selection using GUI input (JOptionPane).
  - Automatic adjustment for odd sizes (ensures      symmetrical patterns).
  - Cross-platform screen-clear functionality (Windows CMD + Linux/macOS escape codes).
  - Includes 10 unique pattern designs.
  - Allows users to print multiple patterns in a loop.


📁 Project Structure

  - Pattern_Printing_project.java

The main components inside the program include:


1. mainModule()
  - Displays the menu.
  - Takes user input via JOptionPane.
  - Calls the required pattern function.
  - Asks user if they want to continue.


2. input()
  - Takes size input.
  - Ensures the size is odd, so patterns remain symmetric.


3. Pattern Functions
  - Each function generates a different pattern:

       Function Name	          Pattern Printed
    -------------------------------------------------------
     - Triangle()	              Hollow X-border Triangle
     - Swastik()	              Swastik Pattern
     - whole_squre()	          Hollow Square
     - Hollow_Hourglass()	      Hourglass (solid)
     - Hourglass_Sand_Timer()	  Sand Timer with borders
     - Diamond()	              Hollow Diamond
     - web()	                  Spider Web (cross pattern)
     - Real_acrrow()	          Realistic Arrow Pattern


4. clear()
  - Clears the console screen based on the OS:
  - Windows → CMD cls
  - Linux/macOS → ANSI escape sequences


5. main()
  - Creates an object and runs the program.



⚙️ Working
  - Program starts with a clean screen.
  - Menu is displayed showing all pattern options.
  - User selects a pattern using a pop-up dialog.
  - User is asked for size.
  - The selected pattern function is executed.
  - The program asks if user wants to continue:
     - y → Loop again
     - n → Exit
All patterns are printed directly in the console using nested loops.



🛠️ How This Project Was Created

Built using Core Java (JDK).

  - Heavy usage of:
  - for loops
  - Conditional statements
  - Use of " ".repeat() and character patterns
  - Designed with mathematical logic to maintain symmetry.
  - Tested on Windows environment, validated for cross-platform console output.
  - Implemented JOptionPane for cleaner input interface.
  - The objective of the project is to help beginners understand:
  - Pattern printing logic
  - Nested loops
  - Basic control flow
  - Console-based Java UI
  - Modular Java program design


👨‍💻 Author

* Nme -- Mayank Tak
* Bachelor of Computer Applications (BCA)
