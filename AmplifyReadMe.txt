
***** To Start Amplify **********************
For all experiencing the issue of Windows Command Prompt not recognizing amplify, the reason behind this error being windows unable to detect PATH to the amplify's executable file.

To solve this, simply edit a PATH key under system Environment Variables and add a new path pointing to amplify. For me it's:

C:\Users\YourUserAccountName\AppData\Roaming\npm\

If you have globally installed amplify/cli then you should find two files named amplify and amplify.cmd in the above mentioned npm directory.


In order for it to work for me I put the executable files in the PATH in Environment Variables like waleedshkt said. Then at the command prompt I typed:
c:\Users\YOU\Appdata\Roaming\npm\amplify.cmd configure