# Password Generator

This is a simple Python program that generates random passwords of a specified length while ensuring a minimum level of strength. The strength of the password is determined by the presence of four properties: lowercase letters, uppercase letters, digits, and special characters.

## Usage

1. Make sure you have Python installed on your system.
2. Clone or download this repository to your local machine.
3. Navigate to the "Password Generator" directory.

### Running the Program

Execute the following command in your terminal or command prompt:

```bash
python passwordgenerator.py
```

You will be prompted to enter the desired length of the password. Once you enter the length, the program will generate a random password and display it on the screen.

### Password Strength Criteria

To be considered a strong password, a generated password must meet the following criteria:

- Contains at least one lowercase letter.
- Contains at least one uppercase letter.
- Contains at least one digit.
- Contains at least one special character (e.g., !@#$%^&*()_+{}[]:;"'<>,.?/~).

If the generated password meets these criteria, it will be considered strong and displayed. Otherwise, the program will regenerate a new password until a strong one is generated.

## File Structure

- `passwordgenerator.py`: This is the main Python script that generates passwords.
- `README.md`: This documentation file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to use and modify this code to suit your needs. Happy password generating!
