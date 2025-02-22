# 🚀 How to Access Your Virtual Machine Like a Pro  

## 📝 Prerequisites  
Before you start, make sure you have:  
✅ **Your SSH key file** (`gatitu.pem`)  
✅ **Your VM's public IP** (`20.246.98.159`)  
✅ **A terminal** (Command Prompt, PowerShell, or Linux/Mac Terminal)  

## 📂 Step 1: Navigate to the Right Folder  
Open your terminal and move to the directory where `gatitu.pem` is located.  

# For **Mac/Linux**, use:  
```bash
cd ~/Downloads
For Windows PowerShell, use:

powershell
cd C:\Users\YourUsername\Downloads
🔐 Step 2: Set Secure Permissions for Your Key
To ensure security, modify the permissions of the .pem file:

chmod 400 gatitu.pem

⚠️ (Windows users can skip this step!)

🌐 Step 3: Connect to Your Virtual Machine
Now, let’s SSH into the VM! Run this command:

ssh -i gatitu.pem gatitu@20.246.98.159
# 🎉 Success! You're now inside your virtual machine!
