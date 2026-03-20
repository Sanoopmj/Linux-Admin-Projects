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

## To Get File 

## setenforce
![setenforce](ftp_screenshots/SS1-setenforce.png)

## clientsetenforce
![clientsetenforce](ftp_screenshots/SS2-clientsetenforce.png)

## installVSFTPD 
![installVSFTPD](ftp_screenshots/SS3-installVSFTPD.png)

## startservice
![startservice](ftp_screenshots/SS4-startservice.png)

## getfile
![getfile](ftp_screenshots/SS5-getfile.png)


## To Upload File

## createfolder
![createfolder](ftp_screenshots/SS1-createfolder.png)

## createfile
![createfile](ftp_screenshots/SS2-createfile.png)

## VSFTPDconfigfile
![VSFTPDconfigfile](ftp_screenshots/SS3-VSFTPDconfigfile.png)

## enableanonymous
![enableanonymous](ftp_screenshots/SS4-enableanonymous.png)

## loginftp
![loginftp](ftp_screenshots/SS5-loginftp.png)

## uploadfile
![uploadfile](ftp_screenshots/SS6-uploadfile.png)



✅ Outcome

- Successfully transferred files between client and server
- Implemented secure and controlled FTP access
