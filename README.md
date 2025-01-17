# WhatsApp Message Sender Bot (EXE Version)

A standalone executable that automates sending text messages and images to multiple WhatsApp contacts using WhatsApp Web. No coding or installation required!

---

## **Features**

- **Bulk Messaging:** Send messages to multiple contacts at once.
- **Image Support:** Send images along with text messages.
- **Easy to Use:** No technical knowledge required—just download and run!
- **Customizable:** Edit text files to add phone numbers, messages, and images.

---

## **How It Works**

1. **Reads Phone Numbers:** The bot reads phone numbers from a text file (`numbers.txt`).
2. **Reads Messages:** The bot reads the message content from another text file (`message.txt`).
3. **Sends Messages:** It navigates to WhatsApp Web, enters the phone number, and sends the message.
4. **Sends Images:** If images are present in the `./images` directory, it sends them along with the text message.

---

## **Download and Setup**

### **Prerequisites**

1. **Python Installation:**
   - Download and install Python from [python.org](https://www.python.org/downloads/).
   - During installation, ensure you check the box to **Add Python to PATH**.

2. **Install Requirements:**
   - Open a terminal or command prompt.
   - Navigate to the folder where you extracted the bot files.
   - Run the following command to install the required Python packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Firefox Browser:**
   - Download and install Firefox from [Mozilla Firefox](https://www.mozilla.org/firefox/).
   - The bot uses Firefox as the default browser, so make sure it is installed on your system.

---

### **Configuration**

1. **Download the EXE File:**
   - Download the latest release of the bot from the [Releases](https://github.com/anasnashat/WhatsApp-Sender/tags) page.
   - Extract the ZIP file to a folder on your computer.

2. **Configure the Bot:**
   - Open the extracted folder.
   - Add the phone numbers you want to message in `numbers.txt`, one per line.
   - Add the message you want to send in `message.txt`.
   - Place the images you want to send in the `./images` directory.

3. **Run the Bot:**
   - Double-click the `bot.exe` file to start the bot.
   - Scan the QR code on WhatsApp Web to log in using Firefox.
   - The bot will start sending messages to the numbers listed in `numbers.txt`.

---

## **Important Notes**

- **WhatsApp Web Login:** You must log in to WhatsApp Web by scanning the QR code when prompted.
- **Firefox Browser:** The bot uses Firefox as the default browser. Make sure Firefox is installed and set as your default browser.
- **Windows Only:** This EXE file is built for Windows systems only.

---

## **Troubleshooting**

- **Bot Not Sending Messages:**
  - Ensure you are logged in to WhatsApp Web.
  - Check that the phone numbers in `numbers.txt` are in the correct format (e.g., `1234567890`).
  - Make sure the `message.txt` file contains the message you want to send.

- **Images Not Sending:**
  - Ensure the images are placed in the `./images` directory.
  - Supported image formats: JPG, PNG, GIF, BMP, etc.

- **Firefox Not Opening:**
  - Ensure Firefox is installed and set as the default browser.
  - If Firefox is installed but not opening, try reinstalling it.

---

## **Future Enhancements**

- **Support for Multiple Browsers:** Add support for Chrome and other browsers.
- **Scheduling:** Add the ability to schedule messages for a specific time.
- **Group Messaging:** Extend functionality to send messages to WhatsApp groups.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## **Contact**

For any questions or feedback, feel free to reach out:

- **GitHub:** [anasnashat](https://github.com/anasnashat)
