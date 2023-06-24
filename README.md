# KeyLogger-And-ScreenLogger-Virus

This is a keylogger and screenlogger application that operates in a stealthy manner, bypassing Windows Defender using injection techniques. It modifies its structure to evade structure-based detection and runs as a no-console application, ensuring that it operates silently without the user's awareness.

## Disclaimer

**Please note that using or distributing keyloggers without proper authorization is illegal and unethical. This README is for educational purposes only and does not encourage any malicious activities.**

## Features

- **Keylogging**: The application records keystrokes, including special keys such as Enter, Tab, Space, Backspace, Ctrl, and Esc.
- **Screenlogging**: The application captures screenshots at regular intervals.
- **Clipboard Monitoring**: The application monitors the clipboard and logs its contents.
- **Wi-Fi Password Retrieval**: The application retrieves stored Wi-Fi network names (SSIDs) and their corresponding passwords on the target machine.
- **Email Notification**: The application sends an email containing the captured data, including screenshots, clipboard data, and Wi-Fi passwords.

## Installation

1. Clone the repository or download the source code.
2. Ensure that Python and the required packages (`pynput`, `pyautogui`, `smtplib`, `win32clipboard`) are installed.
3. Customize the code as per your requirements.
4. Set up an email account to be used for sending the captured data.
5. Update the email credentials in the code (`send_mail` function) to match your email account details.
6. Run the application.

## Usage

1. Run the application on the target machine.
2. The application will start silently and begin logging keystrokes, capturing screenshots, and monitoring the clipboard.
3. At regular intervals (configured by `time_interval`), the application will send an email containing the captured data.
4. You can terminate the application by pressing the Esc key.
5. For Making exe file with no consule run this command:
> pyinstaller injection.py --onefile --noconsole

## Legal Considerations

- Ensure that you have proper authorization before using or distributing this application.
- Respect privacy laws and regulations.
- This application is provided "as is" without any warranties. The author is not responsible for any misuse or damages caused by this application.

## Important Note

This application is intended for educational purposes only. The use of keyloggers and similar software without proper authorization is illegal and unethical. Always respect privacy laws and obtain proper consent before using any monitoring or surveillance software.

Please use this application responsibly and in compliance with applicable laws and regulations.
