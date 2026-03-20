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

## =>NFS
## installnfs-utils
![installnfs-utils](nfs_yum_screenshots/SS1-installnfs-utils.png)

## mountfolder
![mountfolder](nfs_yum_screenshots/SS2-mountfolder.png)

## exportsfile
![exportsfile](nfs_yum_screenshots/SS3-exportsfile.png)

## exportsconfigfile
![exportsconfigfile](nfs_yum_screenshots/SS4-exportsconfigfile.png)

## mountpartition
![mountpartition](nfs_yum_screenshots/SS5-mountpartition.png)

## partitiondata
![partitiondata](nfs_yum_screenshots/SS6-partitiondata.png)


## yum client config
## all_package_folder
![all_package_folder](nfs_yum_screenshots/SS1-all_package_folder.png)

## masterrepofile
![masterrepofile](nfs_yum_screenshots/SS2-masterrepofile.png)

## masterrepo
![masterrepo](nfs_yum_screenshots/SS3-masterrepo.png)

## repolist
![repolist](nfs_yum_screenshots/SS4-repolist.png)

## clientrepo
![clientrepo](nfs_yum_screenshots/SS5-clientrepo.png)

## clientrepofile
![clientrepofile](nfs_yum_screenshots/SS6-clientrepofile.png)

## clientrepolist
![clientrepolist](nfs_yum_screenshots/SS7-clientrepolist.png)

✅ Outcome

- Achieved centralized file sharing
- Enabled offline package installation
