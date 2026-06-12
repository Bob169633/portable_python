# Portable Python
This repo includes a portable python install for people who don't have python installed or are less tech savvy

## Installing this
1. Click the green button, download zip
2. Extract zip to any folder (I recommend making a folder on the desktop because desktop is easy to find)
3. I recommend extracting all my projects to the same folder and make a sub-folder for that specific project

## Creating Executables with Packager.py
1. Copy the file path of the python file you want to create, and paste into a text document
2. Copy the file path of the packager.py file, and paste into a text document
3. Copy the file path of the python.exe file, and paste into a text document (If you have python already, I suggest running this from a directory with a local python environment)
4. Look at the file paths. Select the sections that are the same, cut them, then press "WIN+R" and type cmd then press run. A command line should open
5. In this command line, type "cd " then paste the file path you just copied and hit enter
6. Look back at the text document. You should have deleted the folders that are the same
7. Copy the python.exe path and paste into command line (middle click to paste) DO NOT HIT ENTER YET
8. Copy the packager.py path and paste into command line
9. Copy the python file path you want made into an executable
10. NOW YOU CAN HIT ENTER
11. Shortly, you should see a line that says something like "File was created at folder/folder/file_name.exe", with the folders and file_name being the actual paths

## Examples
### This is what the command line should show when you complete step 5
`C:\Users\dbtmu\OneDrive\Documents\Coding\Python\DBD_Slot_Machine_Repo>`

### This is an example of what should look like when you complete step 9
`..\portable_python\python.exe packager.py ..\DBD_Slot_Machine_Repo\spinthewheel.py`

### This is an example of the folder structure
```Python
--> DBD_Slot_Machine_Repo
--> --> spinthewheel.py (this is in the DBD_Slot_Machine_Repo folder)

--> portable_python
--> --> python.exe
--> --> packager.py```