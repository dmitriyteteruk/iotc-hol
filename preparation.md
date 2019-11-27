# Technical pre-requirements
### Prepare your laptop
* [install Python](#install-python)
* install IOTC client
* install Visual Studio Code
* prepapre VS Code for work with Python

(#install-python)### Install Python on your laptop:
* Download Python 3.8.0 (32-bit version) using this link https://www.python.org/ftp/python/3.8.0/python-3.8.0.exe
* Save File

![](media/Save-Run.png)

* Run downloaded file and check boxes like on image below:
  - [x] Install launcher for all users (recommended)
  - [x] Add Python 3.8 to PATH

![](media/run-tick.png)

* Click on text **Disable path length limit** on Setup was successful message

![](media/disable-260-limit.png)

* Agree with User Account Control request - click Yes

![](media/UAC-yes.png)

* Click Close button.

![](media/close.png)

### Check Python version
Open **Command Prompt** (Win+R -> Enter), type `python --version` text and push Enter 
You should see **Python 3.8.0** is everythin done correct.

![](media/check-python-version.png)

### Install IOTC libriary (iot central python client)
In Command Promt type  `pip install iotc` and push Enter. You should see downloading progress bars and final message should look like this `Successfully installed httplib2-0.14.0, iotc-0.3.5 paho-mqtt-1.5.0`. Please note, that versions of libriaris/packages may be different.

![](media/install-iotc.png)

### Install VS Code 
(not mandatory, but it is much easier for eyes to work in VS code vs Python IDLE)
* Download VS Code using this link https://aka.ms/win32-x64-user-stable
* Save file on you PC and run it then.
* Agree with Terms and Conditions and click `Next` button

![](media/vscode/vscode1.PNG)

* Click `Next` button

![](media/vscode/vscode2.PNG)

* Click `Next` button

![](media/vscode/vscode3.PNG)

* [x] Check "Create a desktop icon"
* [x] Check "Open with Code" action to Windows Explorer file context menu"
* [x] Check "Open with Code" action to Windows Explorer directiry context menu"
* [x] Check "Add to PATH (requiers shell restart)"
- Then "Click `Next` button

![](media/vscode/vscode4.PNG)

* Click `Install` button

![](media/vscode/vscode5.PNG)

* [x] Check "Launch Visual Studio Code"
* Click `Finish` button

![](media/vscode/vscode6.PNG)

You should see VS Code start window like on image below.

![](media/vscode/vscode7.PNG)

Now you need to install two extentions that will help VS Code to understand and run Python Apps.
1. Install Python extentision from Microsoft. To do this:
  - Go to Extension Menu and put in search window text `@id:ms-python.python`, then click `Install`
 
 ![](media/vscode/vscode12.PNG)
 
   - Then Click on `Terminal` and `New Terminal` on VS Code main window
 
 ![](media/vscode/vscode13.PNG)  
   
   - Put text `& python -m pip install -U pylint --user` in Teminal window and push `Enter`
   
 ![](media/vscode/vscode14.PNG)

***Congratulation! Now your PC ready for HOL!***
