## Program Description:

This program, **PDF Password Protector**, is a Python script designed to secure PDF files by adding password protection. Users can either input their own password or allow the program to generate a strong, random password for them. The program ensures that all passwords meet stringent security criteria, enhancing the protection of sensitive documents.

<br>

### Key Features:
1. **Password Validation**:<br>
   - Ensures user-provided passwords are at least 16 characters long and include:
     - At least one uppercase letter.<br>
     - At least one lowercase letter.<br>
     - At least one digit.<br>
     - At least one special character (`!@#$%^&*()-_+=<>?/`).<br>

2. **Random Password Generation**:<br>
   - Generates a strong password if the user prefers not to create one or their input fails validation.<br>

3. **PDF Encryption**:<br>
   - Reads an input PDF file and outputs a new, password-protected version.<br>

4. **User-Friendly Interaction**:<br>
   - Prompts the user interactively for their preferences.<br>
   - Provides clear error messages and instructions.<br>
   - Keeps prompting for a valid password if the user-provided one doesn't meet the criteria.<br>

5. **Command-Line Interface**:<br>
   - Accepts command-line arguments for specifying the input and output PDF file paths.<br>

6. **Security Disclaimer**:<br>
   - Reminds users that no PDF protection is 100% secure and encourages additional encryption measures for highly sensitive files.<br>

<br>

### How to Use:
1. Run the script from the command line and specify:<br>
   - `-i` or `--input`: Path to the input PDF file.<br>
   - `-o` or `--output`: Path to the output, password-protected PDF file.<br>
2. Choose whether to generate a random password or enter your own.<br>
3. If entering your own password, ensure it meets the strength requirements.<br>

<br>

### Example Command:
```bash
python pdf_protector.py -i input.pdf -o protected_output.pdf

