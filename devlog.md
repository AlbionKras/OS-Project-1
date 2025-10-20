2025-10-19 7:30

I will implement the logger and validate its format and error handling. After that, I will develop the driver, integrate it with the logger through pipes, and refine the user interface. Finally, I will implement the encryption module and complete the end-to-end wiring with the driver, verifying that commands, responses, and logging all function as intended.
 
  I will use c/cpp for this project and implement
  The three separate programs required:
  
  Logger: Reads lines from stdin and writes timestamped log lines to a file until it reads "QUIT" 
  
  Encryption Program: responsible for encrypting and decrypting strings.

  Driver: Interacts with the user to run the entire program using fork/pipe/dup2 in C/C++. Displays a menu, validates user input, sends commands to the encryption program, and logs every command and result

  
2025-10-19 8:30 pm

In this session, I will implement the logger in C++

I will start by defining the command-line interface (logger <logfile>), validating that the logfile argument is present, and opening it in append mode. I will then write an initial [START] Logging Started entry, enter a read loop on stdin, and for each line, emit a single log record with a 24-hour timestamp, the action, and the remaining text as the message. I will flush after each write for real-time visibility. When the action is QUIT, I will record [QUIT] Logging Stopped, close the file, and exit.


