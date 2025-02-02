🛠 Onii Ramdisk – Free iCloud Bypass Tool Using Checkm8 Exploit
An open-source fork of iBoy Ramdisk, designed for educational purposes and personal device unlocking.
![Screenshot (4)](https://github.com/user-attachments/assets/0e018ff9-d2a9-4f57-9841-9be708b70383)

📌 About Onii Ramdisk
Onii Ramdisk is a free iCloud bypass tool based on the Checkm8 exploit. It is developed as an open-source alternative to iBoy Ramdisk, which monetizes free exploits for profit. Unlike other tools, Onii Ramdisk does not encrypt its source code, ensuring transparency for all users.

🔹 Purpose: Educational & personal use only
🔹 Supports: A10–A11 devices (iPhone 6s to iPhone X)
🔹 Exploit Used: Checkm8

⚙️ How It Works
🔍 Understanding the Checkm8 Exploit
Checkm8 is a BootROM vulnerability that allows permanent jailbreaking and bypassing security checks on affected devices. Since BootROM is stored in read-only memory (ROM), this exploit cannot be patched by Apple.

🚀 Bypass Process
DFU Mode Exploitation:
Uses "use-after-free" vulnerability in BootROM’s USB handling.
Heap Manipulation:
Controls memory allocation to execute arbitrary code.
Payload Injection:
Injects shellcode to disable security checks.
Bypassing Hello Screen:
Skips Apple's authentication and grants access to the OS.
📥 Installation & Usage
🔧 Prerequisites
macOS or Linux
A compatible iDevice (A10–A11)
USB-C to Lightning cable
▶️ Steps to Use Onii Ramdisk
Put your device into DFU mode.
Run the following commands:
bash
Sao chép
Chỉnh sửa
git clone https://github.com/yourrepo/onii-ramdisk.git
cd onii-ramdisk
chmod +x onii_ramdisk.sh
./onii_ramdisk.sh
Follow on-screen instructions to complete the bypass.
⚠️ Disclaimer
This tool is strictly for educational purposes and for unlocking personally owned devices. Do not use it for illegal activities. If this tool is misused for commercial gain, the project will be shut down to protect the developer’s reputation.

📢 Developer Contact:
📌 Telegram: @always_free_btw x @linhdzvcl
