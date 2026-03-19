NFS File Sharing and Local YUM Repository Setup (Linux)

📌 Project Overview

Implemented centralized file sharing using NFS and configured a local YUM repository for efficient package management.

⚙️ Technologies Used

- Linux
- NFS
- YUM Repository
- Networking

🔧 Implementation Steps

- Installed and configured NFS server
- Shared directory across network
- Mounted NFS on client system
- Created local YUM repository using ISO
- Configured repo file for package installation

📸 Screenshots

=>NFS

![installnfs](SS1-installnfs-utils.png)
![mountfolder](SS2-mountfolder.png)
![exportsfile](SS3-exportsfile.png)
![exportsconfigfile](SS4-exportsconfigfile.png)
![mountpartition](SS5-mountpartition.png)
![partitiondata](SS6-partitiondata.png)

=>YUM Client Config

![all-package-folder](SS1-all-package-folder.png)
![masterrepofile](SS2-masterrepofile.png)
![masterrepo](SS3-masterrepo.png)
![repolist](SS4-repolist.png)
![clientrepo](SS5-clientrepo.png)
![clientrepofile](SS6-clientrepofile.png)
![clientrepolist](SS7-clientrepolist.png)


✅ Outcome

- Achieved centralized file sharing
- Enabled offline package installation
