# Solutions
These are some solutions to problems I have run into as a programmer. I found these after scouring the internet for hours, sometimes even days. So, I thought it would be helpful to put them all in one place for future reference. 

1. To change your working directory in Linux to a external drive: https://www.reddit.com/r/bashonubuntuonwindows/comments/j3wgsf/how_do_i_change_directory_to_an_usb_flash_drive/ or https://www.scivision.dev/mount-usb-drives-windows-subsystem-for-linux/
2. If a python package doesn't install on Windows, try updating python and pip. Python can be updated by installing the latest version from the official website and then checking the “Add Python 3.9 to PATH” box in the installer. To update pip, type `python -m pip install --upgrade pip` in the `cmd`. If nothing works, try installing the package in Ubuntu (installed on Windows through [WSL](https://docs.microsoft.com/en-us/windows/wsl/install)), but you would have to work on the files you needed the package for in the Linux environment from then on. 
    1. Some Python packages I have come across that don't work well with Windows are `pysam`, `iqtree`, `bedtools` etc. 

