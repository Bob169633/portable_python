# Portable Python
This repo includes a portable python install for people who don't have python installed or are less tech savvy

## Installing this
1. Click the green button, download zip
2. Extract zip to any folder (I recommend making a folder on the desktop because desktop is easy to find)
3. I recommend extracting all my projects to the same folder and make a sub-folder for that specific project

## Creating Executables with Packager.py
1. Press "WIN+R" and type cmd then press run. A command line should open
2. In this command line, type "cd " then paste the file path where you want the executable to end up (I recommend the highest folder you extracted my projects to)
3. Copy the python.exe path and paste into command line (middle click to paste) DO NOT HIT ENTER YET
4. Copy the packager.py path and paste into command line
5. Copy the python file path you want made into an executable
6. NOW YOU CAN HIT ENTER
7. Shortly, you should see a line that says something like "File was created at folder/folder/file_name.exe", with the folders and file_name being the actual paths

## Examples
### This is what the command line could show when you complete step 2
`C:\Users\<user>\OneDrive\Documents\Coding\Python\DBD_Slot_Machine_Repo>`

### This is an example of what the command line should look like when you complete step 5 (pretend this is all one line)
`C:\Users\<user>\OneDrive\Documents\Coding\Python>`
`C:\Users\<user>\OneDrive\Documents\Coding\Python\portable_python\python.exe`
`C:\Users\<user>\OneDrive\Documents\Coding\Python\packager.py`
`C:\Users\<user>\OneDrive\Documents\Coding\Python\DBD_Slot_Machine_Repo\spinthewheel.py`


### This is an example of the folder structure
```Python
Python
--> DBD_Slot_Machine_Repo
--> --> spinthewheel.py (this is in the DBD_Slot_Machine_Repo folder)

--> portable_python
--> --> python.exe
--> --> packager.py