Version 1.0.3

Release date
  - 31st March 2017

Release notes
 - Dashboard section on BCON1 tab
 - Change Attenuation setting on ADSB tab
 - Sensors tab to select GPS, Altimeter source
 - Upgrade firmware option
 - Tools to support upgrade operation
 - lib-usb drivers
 - Minor enhancements bug fixes
 
 Usage
 - Read BCON1 userguide available on www.skysense.io
 
 Installation
 - Download Installer-ver-1.0.3.zip
 - Create new directory c:\bcon1
 - Extract the contents of compressed file to c:\bcon1 (Contents listed in next section)
 
 - Install BCON1 GUI client 1.0.3
 -- Uninstall old or any existing version
 -- Go to directory c:\bcon1
 -- Locate and execute Run setup.exe
 -- When the installation is complete GUI opens itself.
 
 - Install lib-usb (This library install DFU drivers for BCON1 and enables BCON1 GUI to upgrade the new firmware on BCON1 over USB)
 -- Connect the BCON1 to the PC via standard USB cable
 -- On the BCON1 Press & Hold down the DFU Switch and perform power cycle, BCON1 now should only gave solid RED LED.
 -- Extract the content of libusb-win32-bin-1.2.6.0.zip to a temp directory
 -- Goto ..\libusb-win32-bin-1.2.6.0\bin and run the inf-wizard
 -- Select the DFU ATXMEGA128A4U from the list and press Next. 
 -- Press Next on the Device Configuration window 
 -- Save the driver files (*.inf) on local disk and press the Install Now..
 -- Click on Done button when installer has finished the installation.
 -- Open Device Manager and verify that drivers for DFU ATXMEGA128A4U has been installed.
 
 - For using the client see the BCON1 user guide.
 
c:\bcon1 Files
     <DIR>          Application Files
                    BCON1-DFU.application
                    dfu-programmer.exe
                    IS_DFU.bat
                    libusb-win32-bin-1.2.6.0.zip
                    PROG.bat
                    setup.exe
        