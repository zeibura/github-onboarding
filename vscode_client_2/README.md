# Mainframe Messenger for VS Code

Mainframe messenger is an easy way how you can send messages from Visual Studio Code to another user on TSO on green screen. The user you send messages to must be connected to a specific mainframe connection that you configure in extension settings. Mainframe messenger has Zowe conformance and uses Zowe profile to connect to the mainframe.

## Prerequisites

- Java version 11 on your computer.
- A Zowe zosmf profile with credentials defined.

## Connect to the Mainframe

Before you start using the Mainframe Messenger, connect to the mainframe.

1. Open Visual Studio Code and install the Mainframe messenger extension.
2. In extension settings, write the name of your Zowe profile under "zowe profile".
3. Write your mainframe username and password in "username" and "password".
4. If you want use a custom name on your messages, write the name under "custom name".
5. Under "host" write the URL of your mainframe connection in format http(s)://host(port).  
You successfully connected to the mainfraime.

## Using

### Send a Message to an Existing User

1. Create a new file in your VS Code workspace using a file with the extension .txt.
2. Write your message in the file   
**Note:** Your message cannot be longer than 80 characters.
3. Save the file
4. In your workspace, right click .txt file and click on "send using Mainframe Messenger"
5. A box displays at the top of the screen
6. Write the mainframe username of the person you want to send the message to in the box.  
**Note:** The person you send the message to must be logged in to the same mainframe server you put in extension settings
13. Press enter to send your message.  
You successfully sent a message to an existing user.

## Disclaimer

This readme file exists for educational purposes only and does not describe a real extension.
