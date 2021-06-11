# Python Workshop Series Setup

For the JHU Python workshop series we recommend [Anaconda](https://www.anaconda.com/products/individual), an all-in-one installer for Python. Anaconda Python includes a user interface to make it easy to launch Python applications and manage packages and environments without using command-line commands.

We will be using Python 3 for the JHU Python workshop series, so if you choose not to install Python using Anaconda (although we recommend it) please ensure you install Python version 3.x (e.g., 3.8 is fine).

We will teach Python using [Jupyter Notebooks](https://jupyter.org/), a programming environment that runs in a web browser (Jupyter Notebook will be installed by Anaconda). For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, Safari and Firefox browsers are all supported (some older browsers, including Internet Explorer version 9 and below, are not). 

# Installation Instructions by Operating System

1. [Windows Installation Instructions](#win)
2. [macOS Installation Instructions](#mac)
3. [Linux Installation Instructions](#linux)

<a name="win"/>

## Windows Installation Instructions

1. Download the [Windows Anaconda installer](https://repo.anaconda.com/archive/Anaconda3-2021.05-Windows-x86_64.exe). 
2. Double click the installer .exe to to launch.
3. Click next on the setup window.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/windows-setup.png?token=AA3SGJ3BPVAUZFIZOU7A2W3AZSQDM" alt="Anaconda Windows Setup" width="450">
4. Review the licensing terms and select "I Agree" if you accept the terms of the agreement. 
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/windows-license.png?token=AA3SGJ4V6HEKY64VG4RNCU3AZSZCK" alt="Anaconda Windows License Agreement" width="450">
5. Ensure the Install for: "Just Me (recommended)" radio button is selected, then press "Next". 
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/windows-privileges.png?token=AA3SGJ2BLXNNCZ4PRXQOQ7TAZS2LI" alt="Anaconda Windows Installation Privileges" width="450">
6. Select a destination folder to install Anaconda, then press the "Next" button. You should not need to change the default path.
   <br/>
   <br/>
   <img src="https://github.com/jhu-data-services/python-installation-instructions/blob/main/images/windows-path.png" alt="Anaconda Windows Installation Privileges" width="450">
7. At the Advanced Installation Options window, ensure that "Add Anaconda3 to my PATH environment variable" is not selected, and "Register Anaconda3 as my default Python 3.8" is selected. Then select "Install". If you have an existing Python installation that you are currently using, then do not select "Register Anaconda3 as my default Python 3.8", as this will replace your current Python version as the default. 
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/windows-env-variables.png?token=AA3SGJ3M5GJGBHROK5NQWK3AZS4O4" alt="Anaconda Windows Advanced Installation Options" width="450">
<a name="mac"/>
8. Finally, press "Next" on the following pop-up dialog boxes. After a successful installation you will see the “Thanks for installing Anaconda” dialog box. You may then press the "Finish" button. This concludes your Anaconda Python installation.

## macOS Installation Instructions

1. Download the [macOS Anaconda installer](https://repo.anaconda.com/archive/Anaconda3-2021.05-MacOSX-x86_64.pkg). 
2. Double click the .pkg installer in your Downloads folder.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-filelocation.png?token=AA3SGJ6HOE2ZRPEEKTLNEBDAZTTVQ" alt="Anaconda macOS .pkg installer start" width="600">
3. You will receive a security prompt letting you know that the Anaconda installer will check your computer to see if it can be installed. Press "Continue" to proceed with the installation.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-safety.png?token=AA3SGJ5HLSSKIYO7UJNTXD3AZTUNQ" alt="Anaconda macOS installer start" width="500">
4. Now the Anaconda installer will begin. On the Welcome window select "Continue" to proceed with the installation.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-intro.png?token=AA3SGJZMKI4N72J5ZYE4F43AZTUM2" alt="Anaconda macOS read me" width="450">
5. Press "Continue" at the Read Me window. The Important Information box contains information about advanced configuration of Anaconda, but the defaults settings are preferred for the JHU Python workhsop series.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-readme.png?token=AA3SGJ6IOD5J3LDOR3BFTRDAZTV7Q" alt="Anaconda macOS .pkg installer start" width="450">
6. Review the licensing terms, and then select "Continue". 
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-license.png?token=AA3SGJ7DVHSA33P7VI7RGTDAZTX2C" alt="Anaconda macOS installer license" width="450">
7. A dialog box will pop-up asking if you accept the terms of the license agreement. If you do, press "Agree".
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-license-agreement.png?token=AA3SGJYE6DCXCTS6NTCDTB3AZTYBC" alt="Anaconda macOS license agreement consent" width="450">
8. The installation window will now install Anaconda on your disk. Press "Install" to begin the installation process.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-location.png?token=AA3SGJZ42D353MG3NDS6XLLAZTYXW" alt="Anaconda macOS installation" width="450">
9. Finally the installation will prompt you to install PyCharm. Press "Continue" to finish the installation without installing PyCharm.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/mac-pycharm.png?token=AA3SGJZEVDPV5QP4Y2QOV2TAZTZHS" alt="Anaconda macOS PyCharm prompt" width="450">
10. Your installation will complete. To finish your installation press "Close" on the final installation window.

<a name="linux"/>

## Linux Installation Instructions

1. Download the [Linux Anaconda installer](https://repo.anaconda.com/archive/Anaconda3-2021.05-Linux-x86_64.sh). 
2. Navigate to the installer location using your preferred terminal emulator. If your default folder is `Downloads` then you can use the command `cd ~/Downloads`.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/linux-download.png?token=AA3SGJ4H3Q52XM74DRXF7NTAZUA4Q" alt="Linux installer path" width="650">
3. Run the installation shell script using the command `./Anaconda3-2021.05-Linux-x86_64.sh`. You will be prompted to review a license agreement, press <kbd>Enter</kbd> to continue. 
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/linux-install-start.png?token=AA3SGJ34PCLCALQTI66OZN3AZUCMG" alt="Linux installer start" width="650">
4. A license will be displayed in the terminal window. Review the license, and pan down using either <kbd>Enter</kbd> to move a line at a time, or <kbd>Page Down</kbd> to move a page at a time.
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/linux-license.png?token=aa3sgj25t2hqou2ytf5sbhtazucpk" alt="linux license review" width="650">
5. When you have reached the end of the license, type `yes` and press <kbd>Enter</kbd> if you agree with the terms of the license. 
   <br/>
   <br/>
   <img src="https://raw.githubusercontent.com/jhu-data-services/python-installation-instructions/main/images/linux-license-accept.png?token=AA3SGJYAWPQKWVZEKHYNYV3AZUCYQ" alt="Linux license agreement" width="650">
   

This documentation is licensed under CC0 1.0 Universal [![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)
