# docker on Windows 10 Home Single (20H2) (64 bit)
- I wanted to install docker on my Windows 10 Home Edition 64 bit machine.
- I downloaded the "Docker Desktop Installer.exe" for windows from https://www.docker.com/products/docker-desktop.
- I ran the "Docker Desktop Installer.exe" which displayed the option to download/install Windows Tools for WSL2 (Windows Sybsystem for Linux).
- I cancelled the setup and searched for WSL2.
- I ended up with this https://www.youtube.com/watch?v=5RQbdMn04Oc video from where I enabled the following features in Windows via "Turn Windows features on or off",
- Virtual Machine Platform
- Windows Hypervisor Platform
- Windows Subsystem for Linux
- ![image](https://user-images.githubusercontent.com/19230214/124648994-8d89d780-deb5-11eb-96e0-478fb63d1948.png)
- After enabling the above featured I restarted the machine.
- Then I downloaded and installed "WSL2 Linux Kernel update package for 64x machines" from https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi.
- I restarted the machine once.
- Then I installed the "Docker Desktop Installer.exe" for Windows but unchecked the option to download/install Windows Tools for WSL2.
- I restarted the machine once.
- I got the Docker Desktop installed and running in my Windows 10 Home Single version(20H2) Machine.
- ![image](https://user-images.githubusercontent.com/19230214/124649825-9d55eb80-deb6-11eb-8c3b-b54580b2c1c7.png) 
- You can check your Windows 10 Home Edition version by running "winver" in Windows. 

