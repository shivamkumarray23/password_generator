# password_generator
## **Project Title:**

**Password Generator using Python Tkinter**

## **1. Introduction**

This project is a **Password Generator Application** built using Python’s `tkinter` GUI library. The program allows users to input the desired number of characters and generates a strong random password using ASCII characters ranging from symbols to numbers and alphabets. It also includes the functionality to copy the generated password directly to the clipboard with a single click and receive a confirmation message.

The project provides a simple and effective way to generate secure passwords for users. It demonstrates the use of GUI elements, event handling, and string manipulation in Python.
## **2. Main Objectives**

1. To create a GUI-based password generator using Python’s `tkinter` module.
2. To generate strong and random passwords using ASCII values.
3. To allow users to specify the desired password length.
4. To enable copying the password to the clipboard with a message popup.
5. To understand event-driven programming and GUI design using Python.

## **3. Software & Tools Used**

* **Programming Language**: Python 3.x
* **Library**: tkinter (GUI), random
* **IDE**: PyCharm / VS Code / IDLE
* **Platform**: Desktop (Windows recommended)
* **Input Device**: Keyboard and Mouse
## **4. System Design**

The application is structured using `tkinter` components:

* **LabelFrames**: Used to separate sections for user input and output display.
* **Entry widgets**: One for the user to enter the number of characters and one to display the password.
* **Buttons**:

  * **Generate Password** button: Triggers password creation.
  * **Copy to Clipboard** button: Copies the generated password and shows a popup.
* **Messagebox**: Used to show a success message after copying.

The layout is arranged using `.pack()` and `.grid()` for clarity and alignment.
## **5. Functionalities Implemented**

* Input box to define the password length.
* Random password generation using `randint()` and ASCII characters.
* Password display in an uneditable entry field.
* Copy password to clipboard functionality.
* Confirmation popup using `messagebox.showinfo()`.
## **6. Workflow**

1. The user opens the application.
2. Enters the number of characters in the input field.
3. Clicks the **Generate Strong Password** button.
4. A password is generated and displayed.
5. The user can click **Copy to Clipboard** to copy the password.
6. A popup message confirms the copy action.

## **7. Sample Input/Output**

| **Action**                | **Expected Output**                       |
| ------------------------- | ----------------------------------------- |
| Enter number: 10          | Generated password like `B#d9$L!2tP`      |
| Click “Copy to Clipboard” | Popup: “password is copied to clipboard”  |
| Enter number: 15          | Generated password like `@9Lp^r$kQ!8@2Zx` |

## **8. Advantages**

* Generates strong, unpredictable passwords.
* Simple and clean GUI interface.
* Immediate copy functionality for user convenience.
* Good project to understand GUI design and string manipulation in Python.
* Easily extendable for additional password options (e.g., include/exclude symbols or numbers).

## **9. Limitations**

* Does not allow user customization (e.g., exclude symbols or use only letters).
* No strength indicator for generated password.
* No option to store previously generated passwords.

## **10. Future Enhancements**

* Add checkbox options for including/excluding uppercase, lowercase, digits, and symbols.
* Add password strength rating (weak/medium/strong).
* Allow saving generated passwords to a file.
* Add a secure login or PIN to access the generator.
* Add light/dark mode for better usability.

## **11. Conclusion**

The Password Generator Application built using Python’s `tkinter` is a practical tool that allows users to quickly generate secure passwords of any desired length. It provides a user-friendly GUI and instant clipboard functionality. This project is ideal for beginners to understand event-driven programming, ASCII handling, GUI layout, and clipboard access in Python.
