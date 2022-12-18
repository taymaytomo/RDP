INSTALL of RDP Wrapper and Autoupdater
--------------------------------------

1. Download [RDPWrap-v1.6.2.zip](https://github.com/taymaytomo/RDP/releases) and extract all files to the "%ProgramFiles%\RDP Wrapper" directory

    DO NOT use other directories to install/extract the RDP Wrapper files.
    USE ONLY the "%ProgramFiles%\RDP Wrapper" directory (normally C:\Program Files\RDP Wrapper)


2. Download [autoupdate.zip](https://github.com/taymaytomo/RDP/raw/main/autoupdate.zip) and extract all files to the "%ProgramFiles%\RDP Wrapper" directory


3. To enable autorun of autoupdate.bat on system startup, run the following helper batch file as administrator:

    "%ProgramFiles%\RDP Wrapper\helper\autoupdate__enable_autorun_on_startup.bat"


4. Set in your Antivirus or Windows Defender an exclusion on the folder "%ProgramFiles%\RDP Wrapper" to prevent the deletion of RDP Wrapper files


5. Now you can use the autoupdate batch file to install and update the RDP Wrapper. Please run autoupdate.bat as administrator:

   "%ProgramFiles%\RDP Wrapper\autoupdate.bat"
