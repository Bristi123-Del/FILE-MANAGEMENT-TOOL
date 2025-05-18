# FILE-MANAGEMENT-TOOL 

*COMPANY*: CODTECH IT SOLUTIONS

NAME*: BRISTI GHOSH

*INTERN ID*: CT04DM178

*DOMAIN*: C++ PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR 

*DESCRIPTION*: In this C++ project, I developed a simple yet functional menu-driven program to demonstrate basic file handling operations such as writing to a file, appending data, and reading from a file. The project was written and tested using Dev C++, a lightweight and beginner-friendly integrated development environment (IDE) that made the development and debugging process smooth and efficient.

To implement file handling, I used standard C++ libraries including <iostream>, <fstream>, and <string>. The <iostream> library is used for standard input and output operations through cin and cout, while <fstream> is essential for handling file operations like opening, reading, writing, and closing files. The <string> library provides string support for handling and storing text input from the user.

The program is designed with three main file-handling functions: writeToFile(), appendToFile(), and readFromFile(). In the writeToFile() function, I used the ofstream class in overwrite mode (default) to open the file and write content to it. This means any previous content in the file is erased and replaced with new input. This function prompts the user to enter multiple lines of text, ending with the word "END". All user input is saved line-by-line to the file.

In the appendToFile() function, I used the same ofstream class but with the ios::app flag, which allows appending new content to the file without deleting the existing content. This makes the program suitable for situations where logs or records are being continuously added over time.

The readFromFile() function uses the ifstream class to read the contents of the file line-by-line using getline(). This allows the user to view everything written in the file so far in a clean and readable format.

I also implemented basic error handling. For instance, if the file fails to open for writing or reading, the program displays an appropriate error message using cerr, ensuring the user is informed when something goes wrong, such as a missing file or a permission issue.

To make the program user-interactive, I used a do-while loop to continuously display a menu until the user chooses to exit. The menu allows the user to choose from four options: write, append, read, or exit. The switch statement is used to process the selected option. I also included a cin.ignore() statement to clear the input buffer before using getline() so that user input behaves as expected.

I wrote and ran this program entirely in Dev C++, which was perfect for this type of console application. Dev C++ provides an easy way to compile and run C++ code and fully supports file handling, which made testing seamless.

This type of program can be applied in many real-world scenarios, such as saving notes, generating logs, storing user data, reading configuration settings, or maintaining text-based records. Overall, this project helped me gain confidence in using file streams in C++, improved my understanding of persistent storage, and strengthened my programming logic and structure.
