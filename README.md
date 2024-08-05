# LLDB not Launching Fix - Windows
Guide on fixing the LLDB install on Windows.

Information on my OS and LLVM install:
- OS: Windows 10
- LLVM version: 18.1.8

In order to launch lldb.exe, **python 3.10 is required**. 

## Steps to Fix LLDB Install

1. Download the python `Windows installer (64-bit)` at [Python 3.10.11 download link](https://www.python.org/downloads/release/python-31011/).

2. Make sure to check **Add python.exe to PATH** in the python installer.

![Add python.exe to PATH - python install window](./screenshots/add%20python%20exe%20to%20PATH%20-%20python_install_window.webp)

3. Proceed to install python 3.10

## Check LLDB Works
1. Open a new terminal and run the following command: 
```
lldb --version
```

Console output:

![LLDB version - console output](./screenshots/LLDB%20version%20-%20console%20output.webp)

2. If you receive a similar output, then the **lldb.exe** program works.

## Resources
- [Stack Overflow - visual studio lldb.exe liblldb.dll not found](https://stackoverflow.com/questions/76520754/visual-studio-lldb-exe-liblldb-dll-not-found)
- [Issue #61878: Running lldb.exe does nothing - llvm-project GitHub repository](https://github.com/llvm/llvm-project/issues/61878)