!!! important
    This tool **MUST** be executed anytime you want to work on {{ project.name }} project

***

### **Information**

**{{ project.name }} Launcher** is the tool that update {{ project.name }} Tools and configure them each time you open Maya. It replaces
Maya shortcut and does the following steps each time you execute it:

* Creates a **console** that shows the initialization status.
* Updates **Artella Python Paths** to make sure Artella functionality is working on Maya startup.
* Launches **Artella App** automatically.
* Checks if **{{ project.name }} Tools** are already in system and if not:
    * Allows user to select a **custom installation folder** for the tools.
    **Downloads** and **installs** {{ project.name }} Toos in selected folder.
* **Updates** {{ project.name }} Tools to the latest available version.
* Updates **Maya Python Paths** to make sure {{ project.name }} Tools functionality is working on Maya startup.

Thanks to this tool you can:

* Make sure Artella App is executed.
* Install {{ project.name }} Tools in any folder in your PC (even in external hard drives)
* Make sure you have the latest {{ project.name }} Tools version available.
* Make sure that default Maya installation is not modified by {{ project.name }} Tools (so, using this tool you won't have 
conflits problems with other plugins used in other projects/productions).

***

### **Supported Platforms**

<center>

|    |      OS      |   Status    |
| -------- |:-------------:| :---------:|
| ![Windows icon](../../img/windows_icon.png?style=centerme) | Windows 10 (64-bit) |  **Fully** supported & Tested |
| ![MacOS icon](../../img/macos_icon.png?style=centerme) | Mac OS X 10.11 El Capitan (64-bit) |  **Fully** supported & Not Tested |

</center>
