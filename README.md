![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System-Lab-1/assets/170050432/85939291-0077-49d5-b6ec-7902bbebab43)

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System-Lab-1/assets/170050432/5f267dbe-1bae-4523-8fec-80d99baf3acf)


# Installing Suricata & TCPdump using APT on VM running Debian-Based Distribution of Linux

In this lab, I used the Advanced Package Tool (APT) and "sudo" to install and uninstall applications in a Linux Bash shell.

# 1. Task 1. Ensure that APT is installed using "apt" command

   ![image](https://github.com/iahalkhatib/Bash-Shell-Install-Uninstall-Using-APT/assets/170050432/3a0a30a7-4839-45fc-b9aa-743617f71c3d)

   *It is already preinstalled since we are working with a Debian based disribution of Linux system. 

# 2. Task 2. Install and uninstall the Suricata application

In this task, I will install Suricata, (a network analysis tool used for intrusion detection), using "sudo apt install suricata" command and verify that it installed correctly. 
Then, I will uninstall the application.

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/4bad8a46-8352-4970-a328-94f4968f3e99)
![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/740ab5be-3067-4fee-a1f0-c036cfe34217)

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/569a37dd-dbb8-43fd-a0b0-f63c9d152a22)
![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/796b6cda-c1b4-42d4-802b-a42ac5417f82)

   *Notice the appication name and version number nd usage information. 

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/3e202fc0-4c62-442d-bddd-d5415ca56164)


   * Now for the uninstall using "sudo apt remove suricata" command

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/7b1496a5-edc7-4f3e-9792-53f09dfc6d77)

   * Verify the program uninstalled using "suricata" command

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/2d84568e-a5aa-4a4d-ba52-0b505a6d8961)


# 3. Task 3. Install TCPDump application using "sudo apt install tcpdump" command

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/78d549d5-1e7d-4e17-a62b-c4f431d2617e)

# 4. Task 4. Check installed applications using "apt list --installed" command

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/d44c23ba-deee-48b2-a922-087b87c0be17)

   * Notice the application name and version 

# 5. Task 5. Reinstall suricata application using "sudo apt install suricata" command

![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/67f766bb-c62d-4a80-9e9d-b50252a5c35a)
![image](https://github.com/iahalkhatib/Install-Uninstall-Applications-on-Linux-Debian-Based-System/assets/170050432/c4fcf7a8-a223-4edb-b426-76aa991c6515)

   * Verify applicagions that have been installed using "apt list --installed" command

# Conclusion 

*Confirm APT is installed in Bash

*Install Suricata with APT

*Uninstall Suricata with APT

*Install tcpdump with APT

*Reinstall Suricata with APT


