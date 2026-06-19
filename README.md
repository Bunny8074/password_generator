# Password Generator
## Features

- Generates strong and secure passwords
- User can specify the desired password length
- Includes:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters (!, @, #, $, etc.)
- Ensures at least one character from each category
- Randomly shuffles characters for better security
- Easy to use and lightweight

---

## Requirements

- Python 3.x

No external libraries are required. The program uses built-in Python modules:
- `string`
- `secrets`

---

## Project Structure

```
Password-Generator/
│── password_generator.py
└── README.md
```

---

## How to Run

1. Save the code as `password_generator.py`.
2. Open a terminal or command prompt.
3. Navigate to the project folder.
4. Run the program:

```bash
python password_generator.py
```

---

## Example

### Input

```
=== INFOBYTE PASSWORD GENERATOR ===

Enter password length: 12
```

### Output

```
Generated Password: A8@kP#2mQ!x9
```

*The generated password will be different each time because it is randomly created.*

---

## How It Works

1. The user enters the desired password length.
2. The program checks that the length is at least 4.
3. It selects:
   - One uppercase letter
   - One lowercase letter
   - One digit
   - One special character
4. The remaining characters are chosen randomly from all available character sets.
5. The password characters are shuffled to improve randomness.
6. The final secure password is displayed.

---

## Future Enhancements

- Allow users to choose whether to include symbols or numbers
- Copy generated password directly to the clipboard
- Save generated passwords securely
- Build a graphical user interface (GUI)
- Create a web-based password generator

---

## License

This project is open source and intended for educational and personal learning purposes.
