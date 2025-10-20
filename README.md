# OS-Project-1

Files
	Main.cpp
		- Coordinates and connects the encryption and logging processes via pipes
	    Compile: g++ main.cpp -o driver
	Logger.cpp
   	 - Collects commands from main, applies the required formatting, and saves the output to out.txt
    	Compile: g++ logger.cpp -o logger
	Encryption.cpp 
		-Handles three commands from main: set password, encrypt, decrypt
    Compile: g++ encryption.cpp -o encryption

Compile:
./driver out.txt
