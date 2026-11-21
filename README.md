# Password-Cracking
Notes, commands, and lab exercises covering password cracking techniques and security testing.

## Installing John the Ripper GUI (Johnny) on Windows

**Johnny** is an open-source graphical user interface (GUI) frontend for John the Ripper that lets you manage sessions, load hashes, and run wordlist or incremental attacks visually. Johnny requires a **John the Ripper** binary to perform the actual cracking work.

### Step 1: Download John the Ripper Windows Binaries

1. Visit the official **Openwall John the Ripper** download page: [https://www.openwall.com/john/](https://www.openwall.com/john/)
2. Download the Windows binary archive (`.zip` or `.7z`).
3. Extract the archive to a folder on your PC (for example, `C:\Tools\john\`). Keep the `run` directory intact along with its DLL dependencies.

### Step 2: Download and Extract Johnny (GUI Frontend)

1. Go to the **Openwall Johnny** wiki page: [https://openwall.info/wiki/john/johnny](https://openwall.info/wiki/john/johnny) (or check the official `openwall/johnny` repository).
2. Download the Windows binary package (such as `johnny_2.2_win.zip`).
3. Extract the archive to a folder such as `C:\Tools\johnny\`.

### Step 3: Link Johnny to the John Executable

1. Launch `johnny.exe` from your extracted Johnny folder.
2. Open Johnny's **Settings / Preferences** menu.
3. Set the **John executable path** to `john.exe` inside your extracted John `run` folder (for example, `C:\Tools\john\run\john.exe`).
4. Load your hash file (such as a `$pdf$...` hash), choose your attack mode and wordlist, and start the session.
