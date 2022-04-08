# Mainframe Messenger for VS Code

Mainframe messenger is an easy way to send messages from Visual Studio Code to another user on TSO on green screen.  Mainframe messenger has Zowe conformance and uses Zowe profile to connect to mainframe.

## Prerequisites
- Recipient must be connected to a specific mainframe connection that you specify in extension settings.
- Java version 11
- Zowe z/OSMF profile with credentials defined

## Getting Started
1. Configure mainframe connection and provide details to intended messenger recipient
2. In extension settings, write the name of your Zowe profile under "zowe profile"
3. Write your mainframe username and password in "username" and "password"
4. If you want use a custom name on your messages, write the name under "custom name"
5. Under "host" write the URL of your mainframe connection in format http(s)://host(port)

## How to use Mainframe Messenger

1. Open Visual Studio Code and install the Mainframe messenger extension
2. Create a new file in your VS Code workspace with the extension .txt
3. Write your message in the file
   - **NOTE:** Your message cannot be longer than 80 characters

4. Save the file
5. In your workspace, right click .txt file and click on "send using Mainframe Messenger"
6. A box displays at the top of the screen
7. Write the mainframe username of the person you want to send the message to in the box

    - **NOTE:** The person you send the message to must be logged in to the same mainframe server you put in extension settings

8. Press enter to send your message

## Disclaimer

This readme file exists for educational purposes only and does not describe a real extension.
