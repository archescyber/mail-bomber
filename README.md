# Mail Bomber

## Description

This project is a Python-based tool designed for sending mass emails. It allows users to send emails quickly and efficiently while providing features to prevent spam filters from blocking the messages.

## Features

- Sends bulk emails to a list of recipients.
- Allows users to utilize multiple email addresses to minimize the risk of being flagged as spam.
- Configurable settings to customize the email content and delivery options.
- Provides an option to read the `mail.txt`  file, which contains email addresses and their corresponding SMTP keys.
  
## Important Note

Users must ensure that they read and understand the `mail.txt` file format before running the program. This file is essential for the tool to function properly.

## How to get SMTP key?

**• Enable Two-Step Verification:** Activate two-step verification on your Google account.


**• Create an App Password:** Type "app password" in the search bar of your Google account to access the password creation section.


**• Generate SMTP Password:** Create an app password named "SMTP" in the password creation section and copy it.


**• SMTP Password Ready:** Your SMTP password is now ready to be used with the software.


### mail.txt File Format

The `mail.txt`  file should be formatted as follows:

- Each line should contain an entry in the format:  `email:smtp_key`
  
**Example:**
```
example1@example.com:smtp_key_1 
example2@example.com:smtp_key_2 
example3@example.com:smtp_key_3
```
Make sure there are no extra spaces before or after the entries. Each email and SMTP key pair must be on its own line.

## Installation

1. Clone the repository:

```
git clone https://github.com/archescyber/mail-bomber/
```
2. Install the required dependencies:

```
pip install -r requirements.txt
```


## Usage

1. Run the script:

```
python main.py
```

2. The tool will send emails according to the configurations specified in the mail.txt file.



## Important Notes

Using different email addresses helps to prevent spam filters from flagging your emails.

Ensure that your environment has Python installed and configured properly.

Use this tool responsibly and for legitimate purposes only.


## Contribution

Feel free to contribute to the project by submitting issues or pull requests. All contributions are welcome!


