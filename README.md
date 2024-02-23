# Password Manager
This is a simple password manager application built using Python's Tkinter library. It allows users to generate secure passwords, save them along with website information, and retrieve passwords when needed.

# Features
**Generate Password:** Automatically generates a strong password consisting of letters (uppercase and lowercase), numbers, and symbols.

**Save Password:** Allows users to save website details along with associated email/username and password securely.

**Retrieve Password:** Enables users to search for saved passwords by entering the website name.

# Dependencies

**Python 3.x**

**Tkinter** (usually included in Python standard library)

**pyperclip** (for copying generated passwords to the clipboard)
# Installation and Usage
Clone or download the repository to your local machine.
Make sure you have Python installed.
Install the required dependencies using pip:

**bash**
>pip install pyperclip
> 
Run the password_manager.py script:
**bash**
>python password_manager.py
> 
The application window will open, allowing you to use the password manager.
# Usage
**Generating Password:** Click the "Generate Password" button to generate a secure password.

**Saving Password:** Fill in the website, email/username, and password fields, then click the "Add" button to save the credentials.

**Retrieving Password:** Enter the website name in the designated field and click the "Search" button to retrieve the associated password.
# Note
Make sure to keep your data.json file (which stores the saved passwords) secure.

You can modify the default email/username by changing the EMAIL variable in the script.
