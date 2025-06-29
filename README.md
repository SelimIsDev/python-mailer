# Python Bulk Email Sender

This is a simple Python script to send bulk emails using Gmail SMTP.

## ⚙️ Requirements

- Python 3.x
- Internet connection
- A Gmail account with **2-Step Verification** enabled
- Gmail **App Password** (16-digit)

## 🔐 Gmail 2-Step Verification and App Password Setup

This script **only works with Gmail accounts that have 2-Step Verification enabled**. Standard passwords won't work due to Gmail's security policies. Follow the steps below to generate a 16-digit App Password:

1. Go to [https://myaccount.google.com/security](https://myaccount.google.com/security)
2. Under **"Signing in to Google"**, enable **2-Step Verification**
3. After enabling 2FA, go back to the **Security** page
4. Click on **"App passwords"**
5. Choose:
   - App: `Mail`
   - Device: `Other`, and name it something like `BulkMailer`
6. Click **Generate**
7. You will see a **16-character App Password**. Copy and use this in place of your normal Gmail password in the script.

🔸 Keep this password secure. It acts like a key to your Gmail account for this application.

## 📁 Usage Instructions

1. **Enter Recipient Emails**  
   Open the file:  
Enter all recipient email addresses **either one per line** or **separated by commas**.  
Example:<br>

 **example1@gmail.com<br>
 **example2@gmail.com<br>
 **example3@gmail.com<br>
<br>
or<br>
<br>
example1@gmail.com, example2@gmail.com, example3@gmail.com<br>

2. **Run the Application**  
- Double-click `main.py`  
- Enter your Gmail address and the **16-digit app password**
- Write your message
- The script will send the message to **all recipients listed in `mails.txt` using SMTP**

## 📨 Notes

- Make sure your internet connection is active while running the script
- Gmail may block suspicious login attempts; App Password bypasses this safely
- Use responsibly — avoid spam

---

