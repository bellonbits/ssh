🚀 How to Access Your Virtual Machine Like a Pro
Step 1: What You Need
Before diving in, make sure you have:
✅ Your .pem key file (in this case, gatitu.pem)
✅ Your VM's public IP address (20.246.98.159)
✅ A terminal (Command Prompt, PowerShell, or Linux/Mac Terminal)

Step 2: Move to the Right Folder
Open your terminal and navigate to the folder where gatitu.pem is stored. If it’s in Downloads, type:

bash
Copy
Edit
cd ~/Downloads
For Windows users with PowerShell:

powershell
Copy
Edit
cd C:\Users\YourUsername\Downloads
Step 3: Set Permissions for the Key File
To keep things secure, change the file permissions for gatitu.pem:

bash
Copy
Edit
chmod 400 gatitu.pem
(Skip this step on Windows; it’s more of a Linux/Mac thing.)

Step 4: Connect to Your Virtual Machine
Now, let’s jump in! Run this command in your terminal:

bash
Copy
Edit
ssh -i gatitu.pem gatitu@20.246.98.159
🚀 BOOM! You’re in! 🚀

Troubleshooting Tips 🛠
Permission Denied Error? Check that the key file has the correct permissions (chmod 400 helps).
Connection Timed Out? Ensure your VM is running and your firewall/security group allows SSH (port 22).
Wrong Path to Key File? Double-check you’re in the correct directory before running the SSH command.
What’s Next?
Now that you’re in your VM, you can:
✅ Install software
✅ Deploy applications
✅ Host websites
✅ Run scripts
