Secure FTP Server Configuration using VSFTPD (Linux)

📌 Project Overview

Configured a secure FTP server using VSFTPD on a Linux system to enable controlled file transfer between client and server.

⚙️ Technologies Used

- Linux (RHEL/CentOS)
- VSFTPD
- Networking
- Firewall (firewalld)

🔧 Implementation Steps

- Installed VSFTPD package
- Configured FTP settings in vsftpd.conf
- Disabled anonymous login and enabled local users
- Created FTP user and assigned permissions
- Configured firewall to allow FTP traffic
  

📸 Screenshots

=>To Get File

![setenforce](SS1-setenforce.png)
![clientsetenforce](SS2-clientsetenforce.png)
![installVSFTPD](SS3-installVSFTPD.png)
![startservice](SS4-startservice.png)
![getfile](SS5-getfile.png)

=>To Upload File

![createfolder](SS1-createfolder.png)
![createfile](SS2-createfile.png)
![VSFTPDconfigfile](SS3-VSFTPDconfigfile.png)
![enableanonymous](SS4-enableanonymous.png)
![loginftp](SS5-loginftp.png)
![uploadfile](SS6-uploadfile.png)


✅ Outcome

- Successfully transferred files between client and server
- Implemented secure and controlled FTP access
