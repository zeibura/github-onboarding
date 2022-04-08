# Mainframe Messenger for VS Code

Mainframe messenger is a tool for easily sending messages from Visual Studio Code to another user on TSO. The receiver of the message must be connected to the specific mainframe connection that you configure in the extension settings. Mainframe messenger has Zowe conformance and uses a Zowe profile to connect to mainframe.

## Prerequisites
Before installing Mainframe Messenger, make sure you meet the following prerequisites:
1. You have Java version 11 on your computer.
2. You have a Zowe zosmf profile with credentials defined.


## Getting Started

1. Open Visual Studio Code and install the Mainframe messenger extension.
2. In extension settings, write the name of your Zowe profile under "zowe profile".
3. Write your mainframe username and password in "username" and "password".
4. If you want use a custom name on your messages, write the name under "custom name".

## Using
Follow these steps to send a message:
1. Under "host" write the URL of your mainframe connection in format http(s)://host(port).
2. Create a new file in your VS Code workspace with the extension .txt
3. Write your message in the file.

***NOTE*** Your message cannot be longer than 80 characters

4. Save the file
5. In your workspace, right click .txt file and click on "send using Mainframe Messenger".
6. A box displays at the top of the screen.
7. Write the mainframe username of the person you want to send the message to in the box.

**NOTE** The person you send the message to must be logged in to the same mainframe server you put in extension settings.

8. Press enter to send your message

## Disclaimer

This readme file exists for educational purposes only and does not describe a real extension.
