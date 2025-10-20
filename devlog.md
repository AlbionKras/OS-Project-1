2025-10-19 7:30

I will implement the logger and validate its format and error handling. After that, I will develop the driver, integrate it with the logger through pipes, and refine the user interface. Finally, I will implement the encryption module and complete the end-to-end wiring with the driver, verifying that commands, responses, and logging all function as intended.
 
  I will use c/cpp for this project and implement
  The three separate programs required:
  
  Logger: Reads lines from stdin and writes timestamped log lines to a file until it reads "QUIT" 
  
  Encryption Program: responsible for encrypting and decrypting strings.

  Driver: Interacts with the user to run the entire program using fork/pipe/dup2 in C/C++. Displays a menu, validates user input, sends commands to the encryption program, and logs every command and result

  



