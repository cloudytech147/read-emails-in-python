# How to Read Emails in Python?

To peruse Emails from an Email Server we utilize the Internet Message Access Protocol IMAP convention. Despite the fact that you can visit the email specialist co-op site like gmail.com and gaze upward the messages present in your Inbox, it is cool to compose a Python script that can peruse or get Emails from your mail Inbox. Also, here in this [Python](https://www.techgeekbuzz.com/learn-python-programming/) instructional exercise, I will walk you through the means you need to follow to bring messages from your Email Inbox.

## [How to Read Emails in Python](https://www.techgeekbuzz.com/how-to-read-emails-in-python/)

For this tutorial, I will be fetching the mails preset in my Gmail inbox, and to be more specific I will be fetching only those emails which are sent from a specific Email address.

When we try to access our Gmail account with any programming languages or Third-party package we receive the following error.

```
imaplib.IMAP4.error: b'[ALERT] Application-specific password required: https://support.google.com/accounts/answer/185833 (Failure)’
```

You're getting this error message because Gmail blocks third-party app or package requests if 2-Step Verification is enabled for your account. You can fix this error by simply turning off two-step verification, but I wouldn't suggest it. Instead, you can use the Gmail app password and generate an alternate app password for your Gmail account. With this, you don't have to turn off your 2-step verification and you can access your Gmail account using Python or a third-party package.

## This Python tutorial is divided into 3 following sections

* In Section 1 you will learn how to generate or set up a Gmail App password.
* In Section 2 we will discuss the libraries we require to write the Python program.
* In Section 3 we will walk through the Python program to read the Emails.

**Step 1**

![image](https://user-images.githubusercontent.com/90754617/135264609-093a6c70-3dc0-423c-8d2f-c9f5f903aa1e.png)

**Step 2**

![image](https://user-images.githubusercontent.com/90754617/135264719-0f8d7c1e-b8fd-4b7d-a002-0b16bbb04d81.png)

**Step 3**

![image](https://user-images.githubusercontent.com/90754617/135264769-b885a5e3-4484-460c-95db-5c5e2aad79c8.png)

**Step 4**

![image](https://user-images.githubusercontent.com/90754617/135265108-789f48b3-c99a-40c2-8d13-9fd18e18dd8f.png)

## Conclusion

In this Python tutorial, you learned “How to Read Emails In Python”. In this tutorial, I have read the emails from my Gmail account, and I did not want to stop the 2 step verification that’s why I use the Google App Password to connect my Python script to my Gmail  Account. You do not need to do it if you are using a different email provider or server there you can log in to your account with the Plain password.

