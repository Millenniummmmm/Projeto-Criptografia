Discrete Mathematics Encryption and Decryption Project
Overview
This project was developed as part of a Discrete Mathematics course. It focuses on implementing algorithms to encrypt and decrypt text, with a user interface designed using Qt and the core logic implemented in C.

Features
Text Encryption: Securely converts plaintext into ciphertext.
Text Decryption: Reverses the encryption process, restoring the original plaintext.
User Interface: A simple and intuitive front-end built using Qt.
Core Logic: The encryption and decryption logic is implemented in C, providing efficient performance.
Installation
Requirements
Qt Framework: Ensure that you have the Qt framework installed on your machine to run the front-end.
C Compiler: A C compiler like GCC to compile the back-end code.
Steps:
Clone or download the project files to your local machine.
Open a terminal or command prompt.
Navigate to the project directory.
Compiling the Back-end:
Compile the C source code:

sh
gcc -o ProjetoMD ProjetoMD.c
Ensure that the compiled .exe or binary is available for the Qt front-end to interact with.

Running the Project:
Open the Qt project file (.pro) in Qt Creator.
Build and run the Qt project to start the user interface.
Use the interface to encrypt or decrypt text by interacting with the compiled C back-end.
Usage
The Qt-based GUI allows you to input the text to be encrypted or decrypted.
The input is processed by the C back-end, and the result is displayed on the interface.
Files
ProjetoMD.c: The main C source file containing the encryption and decryption logic.
ProjetoMD.exe: The compiled executable of the C program.
QtProject.pro: The Qt project file for the front-end.
Contributing
If you wish to contribute to this project, feel free to fork the repository and submit a pull request.

License
This project is open-source and available under the MIT License.
