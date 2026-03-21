- Redhat Package manager (RPM) - .rpm extension
  - `rpm -i telnet.rpm` (Install package)
  - `rpm -e telnet` (Uninstall package)
  - `rpm -q telnet` (Query Package) - helps to install all the dependencies and package together
  - `rpm -qa` #To list all the available packages
<img width="670" height="187" alt="image" src="https://github.com/user-attachments/assets/a6d713a8-90da-4b43-9a61-32bf1a3e3f0f"/>


---
- yum uses rpm underneath it
  - `yum install ansible` - Downloads ansible including with dependencies
  - `yum repolist` - To Check all the available repos in the package manager
  - `/etc/yum.repos.d` - place where all the repos will be located
- Other commands
    - `yum list ansible` - shows if ansible instslled ansible
    - `yum remove ansible` - removed the package
    - `yum --showduplicates list ansible` - lists all the previous verisons of ansible
