# Mainframe Messenger for VS Code
Mainframe messenger is an easy way to send messages from Visual Studio Code to another mainframe user. 

## Compatibility 
Mainframe messenger conforms with Zowe.

## Prerequisites
- Java 1.11
- Zowe zOSMF profile with credentials defined


## Getting Started
### Configure the mainframe connection in your extension settings
1. Open Visual Studio Code and install the Mainframe messenger extension
2. In extension settings, write the name of your Zowe profile under "zowe profile"
3. Write your mainframe username and password in "username" and "password"
4. If you want use a custom name on your messages, write the name under "custom name"
5. Under "host" write the URL of your mainframe connection in format http(s)://host(port) 

### Create and Send your Message
1. Create a new file in your VS Code workspace with the extension .txt
2. Write your message in the file (Limit: 80 characters).
3. Save the file
4. In your workspace, right click .txt file and click on "send using Mainframe Messenger"
5. A box appears at the top of the screen
6. Write the mainframe username of the person you want to send the message to in the box.  
**NOTE** The recipient must be logged in to the same mainframe server defined in your extension settings.
7. Press enter to send your message

## Disclaimer

This readme file exists for educational purposes only and does not describe a real extension.
