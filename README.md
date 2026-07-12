# Schedule I Cheat

A simple money hack for Schedule I on Windows and Linux.

## IMPORTANT: BACKUP YOUR FILES!
Before you start, make a copy of your original GameAssembly.dll! Save the backup somewhere safe. You will need it if the game updates or if you want to remove the cheat.

## How to use
1. Automatic Money Hack: Simply make any purchase in the game. The item's price will be added to your balance instead of being deducted
2. Change your cash with the UI

## Download
Download the files you need from the Releases (or Actions) tab:
* The modified GameAssembly.dll
* Windows: cheatui.exe (plus required DLLs)
* Linux: cheatui

## Windows Setup

### 1. Requirements
To run cheatui.exe, your system needs the GTK3 Runtime Libraries. If you do not have them installed, the application will fail to start.
* Ensure you have the required DLLs (e.g., libgtk-3-0.dll, libglib-2.0-0.dll, and their dependencies) in the same folder as cheatui.exe.

### 2. Installation
1. Replace the DLL: Go to your game folder and replace the original GameAssembly.dll with the modified one you downloaded.
2. Setup the Tool: Put cheatui.exe and the required GTK-DLLs into a folder of your choice.
3. Permissions: Run cheatui.exe as Administrator. The tool needs elevated privileges to access the game's memory.
4. Play: Start the game first, then open cheatui.exe.

Note: If your antivirus flags the program, this is a common false positive for memory-editing tools. You may need to add an exception.

## Linux Setup
1. Replace the DLL: Go to your game's directory and replace the original GameAssembly.dll with the modified one.
2. Make Executable: Open a terminal in the folder where you downloaded cheatui and run:
```bash
chmod +x cheatui
```
3. Run Executable: Since the tool needs access to the game process, use:
```bash
sudo -E ./cheatui
```
