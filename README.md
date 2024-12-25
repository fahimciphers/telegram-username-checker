# Telegram Username Checker

This project is a Python-based script for checking the availability of Telegram usernames. It generates random usernames and checks their availability by sending HTTP requests to the Telegram website.

---

## Features
- Generates random usernames with customizable lengths.
- Checks username availability on Telegram.
- Displays results with a user-friendly interface.
- Educational use only.

---

## Requirements

Before using this script, ensure you have the following installed:

- **Python 3.6 or later**
- **pip** (Python package installer)
- Required Python packages:
  - `requests`

Install the necessary packages by running:
```bash
pip install requests
```

---

## Installation and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/fahimciphers/telegram-username-checker.git
cd telegram-username-checker
```

### 2. Rename the Script File
If the file is named `start`, rename it to `start.py`:
```bash
mv start start.py
```

### 3. Run the Script
To execute the script, run the following command:
```bash
python3 start.py
```

### 4. Termux Instructions
For Termux users:
- Download Termux from [F-Droid](https://f-droid.org/en/packages/com.termux/).
- Install Python:
  ```bash
  pkg install python
  ```
- Clone the repository and follow the steps above.

### 5. Ubuntu/Linux Instructions
For Ubuntu/Linux users:
- Ensure Python 3 and pip are installed:
  ```bash
  sudo apt update
  sudo apt install python3 python3-pip
  ```
- Clone the repository and follow the steps above.

### 6. Windows Instructions
For Windows users:
- Download and install Python from [python.org](https://www.python.org/downloads/).
- Open Command Prompt or PowerShell.
- Clone the repository using Git or download the ZIP file from the GitHub page.
- Navigate to the script directory and run:
  ```bash
  python start.py
  ```

### 7. macOS Instructions
For macOS users:
- Ensure Python 3 is installed. Use Homebrew if necessary:
  ```bash
  brew install python3
  ```
- Clone the repository and follow the steps above.

---

## How It Works
1. **Random Username Generation**:
   - The script generates usernames consisting of random lowercase letters.
2. **Availability Check**:
   - Sends a GET request to `https://t.me/{username}`.
   - If the response indicates no redirection (status code not 302), the username is considered available.
3. **Result Display**:
   - Available and unavailable usernames are displayed with colored outputs.

---

## Script Walkthrough
- **Header Display**: Provides a cool ASCII art introduction.
- **Username Generator**: Creates random usernames using `random.choices`.
- **Availability Checker**: Sends HTTP requests to Telegram.
- **Footer Display**: Includes credits and warnings.

---

## Notes
- This script is intended for educational purposes only.
- Abide by Telegram's terms of service and avoid misuse.

---

## Example Output
```plaintext
███████████████████████████████████████
█───██────██────███────██───██──██────█
█─████─██─██─██──██─█████─██─██─███───█
█───██─██─██────███────██─██───██──██─█
█─████─██─██─██──██─█████─██─████─███─█
█───██────██────███────██───██──██────█
███████████████████████████████████████
█   Telegram Username Checker      █
█   Author: Fahim Muntasir           █
█   Telegram: @fahimciphers          █
█   Purpose: Educational Use Only    █
███████████████████████████████████████

Enter the number of usernames to search: 5

🔍 Searching for available Telegram usernames...

🔍 Checking username: @abcde |
✅ Available: @abcde
❌ Unavailable: @fghij
❌ Unavailable: @klmno
✅ Available: @pqrst
❌ Unavailable: @uvwxy

🎉 Available Usernames:
 - @abcde
 - @pqrst

🎉 Premium Results Process Complete
✨ Script by Fahim Muntasir | Telegram: @fahimciphers
For educational purposes only.
Stay safe and use responsibly! 🚀
```

---

## Author
- **Fahim Muntasir Siam**
- Telegram: [@fahimciphers](https://t.me/fahimciphers)
- GitHub: [fahimciphers](https://github.com/fahimciphers)

---

## License
This project is licensed under the MIT License.

---

## Disclaimer
This tool is designed for educational purposes only. Use responsibly and avoid violating any platform's policies.



