# ICTPRG302 AT2 Project

- Author:     YOUR_NAME
- Started:    2025-03-28
- Finished:   ---

## Setting Up

Create Repos folder and clone the project:

```shell
cd ~
mkdir -p Source/Repos
cd Source/Repos
git clone https://github.com/AdyGCode/AJG-ICTPRG302-Project-2025-s1.git
```

Change into the new folder, add & activate Python virtual environment:

```shell
cd AJG-ICTPRG302-Project-2025-s1
python -m venv .venv
source .venv/Scripts/activate
```

> ### Note:
> Mac and Linus users will need to use `source .venv/bin/activate` instead 
> of the `Scripts` version for the PC.

## Running the Application

To execute the program on the command line use:

```shell
python PYTHON_FILENAME.py
```

> ### Students TODO
> 
> Replace the PYTHON_FILENAME with the name of your python
> then delete this TODO.


---

## JetBrains PyCharm Hints

- Use the .ignore plugin to help add commonly ignored files in version control
- Make the default folder a Source/Repos folder

### Installing the .ignore Plugin

- Open PyCharm
- Press <kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>S</kbd> (PC)<br> 
  or <kbd>CTRL</kbd>+<kbd>,</kbd> (MacOS) to open settings
- Click on Plugins option
- Click on Marketplace
- Locate .ignore in list, and click install
- Click OK to save the settings

You may have to restart the IDE at this point.

### Create a root .gitignore file

- Click on the project name in Pycharm
- Right mouse click the project name
- Select New...
- Select .ignore File (bottom of menu)
- Select & Click on .gitignore (top of menu)
- Tick the following options to add to the `.gitignore` file
  - [x] Backup
  - [x] Csharp
  - [x] Linux
  - [x] MicrosoftOffice
  - [x] OSX
  - [x] MacOS
  - [x] Python
  - [x] VirtualEnv
  - [x] VisualStudioCode
  - [x] Windows
- Tick "Generate without duplicates"
- Click Generate

### Allow Zoom of Editor

- Open PyCharm
- Press <kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>S</kbd> (PC)<br> 
  or <kbd>CTRL</kbd>+<kbd>,</kbd> (MacOS) to open settings
- Click on `>` next to Editor
- Click on General
- Tick "Change font size with CTRL+Mouse Wheel"
- Optionally select "All Editors"
- Click OK to save the settings

You will now be able to <kbd>CTRL</kbd>+Mouse Wheel to change editor font 
sizes.




