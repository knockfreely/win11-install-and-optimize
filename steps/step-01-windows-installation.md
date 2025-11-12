## 1. Backing up your data
Before reinstalling the operating system, back up your hard drive data to at least two external storage devices.

## 2. Download Windows 11 ISO
Open the [Windows 11 ISO download link](https://www.microsoft.com/en-us/software-download/windows11) in a new tab, and select **English (United States)** as the product language. This version is recommended because it has the fastest bug fixes and the most stable performance, as many developers and the Microsoft headquarters are in the U.S.  
Then, choose the CPU architecture that matches your system: **x64** or **ARM**.

After downloading, verify the ISO hash to ensure the integrity of the file.  
Press **Win + R** to open the Run dialog, type `cmd`, and press **Enter** to open the Command Prompt.  
Then enter the following command (you can copy the path of the ISO file using **Ctrl + Shift + C**):
```cmd
certutil -hashfile "C:\path\to\your\Windows11.iso" sha256
```


## 3. 
