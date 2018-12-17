# Point of Care ICU Database V1.0.18.11.11
# POC ICU Database


## Introduction
This is a demo of English localization version, it's based on part of the Chinese version we use in clinical practice.  
  
Point of Care ICU Database contains APACHE II score, SOFA score and other common tools. You can collcet the data at a patient's bedside with iPhone or iPad which is conected to your LAN host, once you change data on your device, data can be automatically updated on the host, and vice versa.  

Any bugs or problems, please contact me, ningyile@qq.com



##### Home Page
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/UI01.jpg" width="90%" height="90%" />
</p>

#### Software Interface of PC
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/UI02.jpg" width="90%" height="90%" />
</p>

#### Data Visualization of Patients
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/UI03.jpg" width="90%" height="90%" />
</p>

#### Data Visualization of APACHE II
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/UI05.jpg" width="90%" height="90%" />
</p>

#### Data Visualization of SOFA
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/UI07.jpg" width="90%" height="90%" />
</p>

#### Software Interface of iPhone
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/UI08.jpg" width="45%" height="45%" />
</p>
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/UI09.jpg" width="45%" height="45%" />
</p>


>## How to use
Open "Point of Care ICU Database" on PC, MAC with FileMaker Pro 17 Advanced, or on iPhone, iPad with FileMaker Go 17. In particular, the software can be used on PC, MAC, iPhone or iPad stand alone or connected to a local area network(LAN) host. See instructions below or video tutorial of this app for more details.


>>### Account and initial password
You can log in the database with these default accounts and corresponding initial password.After logging in, you can change the password in setting.  

|Account    | Remark                      | Initial Password | Privilege |
|:---------:|:---------------------------:|:----------------:|:---------:|
| PI        | Primary Investigator        | 0                | PI        |
| CRA       | Clinical Research Associate | 0                | CRA       |
| Doctor A  | Sub Investigator            | 0                | Sub-I     |
| Doctor B  | Sub Investigator            | 0                | Sub-I     |
| Doctor C  | Sub Investigator            | 0                | Sub-I     |
| Doctor D  | Sub Investigator            | 0                | Sub-I     |
| DEC A     | Data Entry Clerk            | 0                | DEC       |
| DEC B     | Data Entry Clerk            | 0                | DEC       |
| DEC C     | Data Entry Clerk            | 0                | DEC       |
| DEC D     | Data Entry Clerk            | 0                | DEC       |
| Follow Up | Follow Up Clerk             | 0                | DEC       |  

>>### Detailed configuration for each account.  

|               | PI  | CRA | Sub-I  | DEC    |
|:-------------:|:---:|:---:|:------:|:------:|
| New Record    | YES | NO  | NO     | YES    |
| Delete        | YES | NO  | YES    | NO     |
| Print         | YES | YES | YES    | NO     |
| Import/Export | YES | NO  | YES    | NO     |
| SDV           | NO  | YES | NO     | NO     |
| Data Set      | ALL | ALL | Subset | Subset |



>>### How to use POC ICU Database on a standalone mobile device
1. Iphone or iPad connect PC, MAC via iTunes. Drag the app into FileMaker Go 17.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Standalone01.jpg" width="90%" height="90%" />
</p>
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Standalone02.jpg" width="90%" height="90%" />
</p>
2. Open FileMaker Go 17, tap "Device" button, then you will see the app in the list.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Standalone03.jpg" width="45%" height="45%" />
</p>

>>### How to use POC ICU Database on a device connected to the host
1. Make sure your devices and host are on the same LAN before connecting to the host. Open "Point of Care ICU Database" on your PC, MAC with FileMaker Pro 17 Advanced, click “Setting -> Sharing”.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Host01.jpg" width="90%" height="90%" />
</p>
2. Set the "Network Sharing" selector to "ON".
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Host02.jpg" width="40%" height="40%" />
</p>
3. Open FileMaker Go 17, tap “Hosts -> Hosts”.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Host03.jpg" width="45%" height="45%" />
</p>
4. You will see the local host in the list. The name depends on the name of your host. Then tap the host.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Host04.jpg" width="45%" height="45%" />
</p>
5. Please choose "Connect" or "Always Permit Connection".
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Host05.jpg" width="45%" height="45%" />
</p>
6. Then you will see the app in the list. 
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Host06.jpg" width="45%" height="45%" />
</p>
7. The connection of PC or MAC to the LAN host is similar to mobile device. Open FileMaker Pro 17 Advanced, click “My Apps -> Add App -> From Hosts”.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Host07.jpg" width="90%" height="90%" />
</p>



## QR Code Plugin
YEEPlugin is developed by [HeavenToNite(Gabriel)](https://github.com/OrcaData/YEEPlugin). With QR Code plugin, you can quickly navigate to a specific record with barcode sanner or build-in camera. Of course, other functionalities of this app are not affected without QR Code plugin. 

## Installation of QR Code Plugin 
1. • Yee.fmplugin　　　　 Mac  
   • YEEPlugin.fmx　　　　Win 32-bit Operating System  
   • YEEPlugin.fmx64　　　Win 64-bit Operating System  
   
2. Copy the plugin of the corresponding platform to the Extension folder. In this case, operating system is X64.
The file path is “X:\Program Files\FileMaker\FileMaker Pro 17 Advanced\Extensions”, “X” is your disk drive.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Plugin01.jpg" width="90%" height="90%" />
</p>
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Plugin02.jpg" width="90%" height="90%" />
</p>
3. Open FileMaker Pro 17 Advanced, click “Edit -> Preferences -> Plug-ins”, check the YeePlugin, click "OK".
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/Plugin03.jpg" width="90%" height="90%" />
</p>

## How to import dummy data
1. Open "Point of Care ICU Database" on your PC, MAC with FileMaker Pro 17 Advanced, click “Setting -> Import”.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/ImportData01.jpg" width="90%" height="90%" />
</p>
2. Choose the excel file you want to import, click "Open".
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/ImportData02.jpg" width="90%" height="90%" />
</p>
3. Ensure that the imported data is consistent with the target table, the “Source Fields” is consistent with the “Target Fields”. And do not import the first record.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/ImportData03.jpg" width="90%" height="90%" />
</p>
4. Check the single box of “Perform auto-enter options while......”.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/ImportData04.jpg" width="40%" height="40%" />
</p>
5. Import terminated successfully without warnings. Similarly, you can import data from your lower version of the database into a later updated version.
<p align="center">
  <img src="https://github.com/ningyile/Point-of-Care-ICU-Database/raw/master/IMG/ImportData05.jpg" width="40%" height="40%" />
</p>


## DISCLAIMER
All calculations must be confirmed before use. The author make no claims of the accuracy of the information. These information is not a substitute for clinical judgement. The author shall not be liable for any special, consequential, or exemplary damages resulting in whole or part from any user's use of or reliance upon this material.

