
# productive-windows10
Tips, tricks, software etc to make you more productive using Windows 10. Aimed at developers

# Setting up your dev environment

## 0. Enable Developer Mode
Open up Settings (**WinKey + I**) and head to *Updates and Security* (Check english version) -> *For Developers* and select Developer Mode. This will trigger Windows to setup your PC for Windows 10 development, but scroll down and you'll see common used settings that Windows can easily enable for you like Windows Explorer settings, Powershell and Remote Desktop. 

## 1. Virtual Desktops with Peach
Windows 10 introduced virtual desktops that powerusers from the Mac and Linux world have been using for ages now. Virtual Desktops on Windows 10 still lacks features and/or keyboard shortcuts to make you efficient.

This is where **Peach** https://peachapp.net/ comes into play. Peach improves upon the work in Windows 10 and provides great shortcuts for managing your virtual desktops in an easy-to-use manner. So be sure to download it!

## 2. Docker for Windows

> An integrated, easy-to-deploy development environment for building, debugging and testing Docker apps on a Windows PC. Docker for Windows is a native Windows app deeply integrated with Hyper-V virtualization, networking and file system, making it the fastest and most reliable Docker environment for Windows.

Docker is an essential tool for a great development environment, especially on Windows 10. Even though Windows 10 includes the Linux subsystem for running Ubuntu/Suse etc natively Docker will provide you with a clean and easy way of setting up different development environments without messing up your local system (different ruby, node versions etc)

Download it now at https://www.docker.com/docker-windows

## 3. cmder

cmder or ConEmu are Console Emulators that improves upon the terminal experience in Windows 10. Use it for tabbed windows, great customizations with themes, shortcuts etc. 

Download it at http://cmder.net/

## 4. Visual Studio Code

Visual Studio Code has become one of the best code editors out there that works on all platforms (Windows, macOS and Linux) and has tons of great extensions. VS Code is highly recommended for doing code editing, comitting your code with Git or debugging your app.

Download it at https://code.visualstudio.com/

## 5. Windows Subsystem for Linux

These are crazy days. Now you can run Linux apps/programs natively on Windows 10 providing you the best of two worlds (Windows and Linux). Install ruby, node, run nginx, mongodb etc as it was meant to run with the Windows Subsystem for Linux. In the upcoming Fall Creators Update of Windows 10 you will get to choose between Linux distributions so if you're a Ubuntu person or a Suse person etc you will be able to use the environment you're most comfortable working in.

Being a subsystem it is not an isolated system meaning you can access and edit files on all your drives. You can even add Windows apps to your PATH to utilize or start windows programs directly from your terminal

Check out the guide at https://msdn.microsoft.com/en-us/commandline/wsl/install_guide?f=255&MSPPError=-2147217396

## 6. Use your Taskbar more efficiently

Pin your 10 most used apps/services/shortcuts to the taskbar and access them using keyboard shortcuts:
* **WinKey + Number** Starts or opens the pinned app. Use number 1-9 as well as the 0.
* **Shift + WinKey + Number** Opens a new instance/window of that app. Eg: New Windows Explorer window
