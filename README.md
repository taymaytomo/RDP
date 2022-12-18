INSTALL of RDP Wrapper and Autoupdater
--------------------------------------

1. Download [RDPWrap-v1.6.2.zip](https://github.com/taymaytomo/RDP/releases) and extract all files to the _"%ProgramFiles%\RDP Wrapper"_ directory

    DO NOT use other directories to install/extract the RDP Wrapper files.
    USE ONLY the _"%ProgramFiles%\RDP Wrapper"_ directory (normally _C:\Program Files\RDP Wrapper_)


2. Download [autoupdate.zip](https://github.com/taymaytomo/RDP/raw/main/autoupdate.zip) and extract all files to the _"%ProgramFiles%\RDP Wrapper"_ directory


3. To enable autorun of autoupdate.bat on system startup, run the following helper batch file as administrator:

    _"%ProgramFiles%\RDP Wrapper\helper\autoupdate__enable_autorun_on_startup.bat"_


4. Set in your Antivirus or Windows Defender an exclusion on the folder _"%ProgramFiles%\RDP Wrapper"_ to prevent the deletion of RDP Wrapper files


5. Now you can use the autoupdate batch file to install and update the RDP Wrapper. Please run _autoupdate.bat as administrator_:

  _"%ProgramFiles%\RDP Wrapper\autoupdate.bat"_

<img src="https://raw.githubusercontent.com/taymaytomo/RDP/main/Win7ST.png">
