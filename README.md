# LLDB not Launching Fix - Windows
Guide on fixing a LLDB install on Windows.

Information on my OS and my LLVM install:
- OS: Windows 10
- LLVM version: 18.1.8

In order to launch lldb.exe, python 3.10 is required. Make sure to check **adding python to the system path** in the python installer.

Python 3.10 download link: https://www.python.org/downloads/release/python-31011/
- **Note**: Download the Windows installer (64-bit).

Open a new terminal and run the following command: 
```
lldb --version
```

Output:
```powershell
lldb version 18.1.8
```

If you receive a similar output, then the lldb.exe program works.

Reaource
- [Stack Overflow - visual studio lldb.exe liblldb.dll not found](https://stackoverflow.com/questions/76520754/visual-studio-lldb-exe-liblldb-dll-not-found)
- [Issue #61878: Running lldb.exe does nothing - llvm-project GitHub repository](https://github.com/llvm/llvm-project/issues/61878)