# Bruteforce Passwords - by Oussama

## Description

`Bruteforce Passwords` is a batch script designed to automate password attempts on a specified network resource. This tool iterates through a list of passwords and attempts to authenticate against a given IP address with a specified username. The script is useful for testing the strength of password protections on network shares.

![image](https://github.com/user-attachments/assets/058b59e7-78db-4ee0-bca2-6aaf9b9f6e2f)


## Features

- **Interactive Input**: Prompts for IP address, username, and a list of passwords.
- **Automated Attempts**: Iterates through each password in the provided list and attempts authentication.
- **Success Notification**: Displays a message when the correct password is found.
- **Failure Notification**: Informs the user if none of the passwords were successful.

## Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/bruteforce-passwords.git
   cd bruteforce-passwords
   ```

2. **Prepare the Password List**

   Create a text file named `passlist.txt` with a list of passwords, each on a new line.

3. **Run the Script**

   Double-click `bruteforce_passwords.bat` or execute it from the command line:

   ```cmd
   bruteforce_passwords.bat
   ```

   - Enter the IP Address of the network resource.
   - Enter the Username you want to test.
   - Enter `passlist.txt` as the path to your password list file.

4. **Review Results**

   The script will display attempts and notify you if the correct password is found or if all attempts have been exhausted.

## Disclaimer

This script is intended for educational purposes and should only be used in environments where you have permission to test. Unauthorized use of this script on systems you do not own or have permission to access may be illegal and unethical.

## Contact

For questions or feedback, please contact [Me](https://www.linkedin.com/in/oussamamahmoudicybersec/)
