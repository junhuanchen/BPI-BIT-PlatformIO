# BPI-BIT-PlatformIO

We need to prepare a text editor in advance (VSC or Atom)

## Prepare in advance:
   > In our experience, PlatformIO IDE for VSCode offers better system performance, and users have found it easier to get started


 [Visual Studio Code(VSCode)](https://code.visualstudio.com/)

 [Atom](https://atom.io/)

## Platform IO:
[PlatformIO IDE Web Site](https://platformio.org/)

![Step 1](/docs/pio-1.png)

[Install PlatformIO IDE for VSCode](/PIO_for_VSCode.md)

+ ### Install PlatformIO IDE for Atom
    - ##### Installation Instruction:
        
        > [PlatformIO official documentation(PlatformIO IDE for Atom)](https://docs.platformio.org/en/latest/ide/atom.html#ide-atom)

        ![Step 3](/docs/pio-3.png)
         
         1. Open Atom Package Manager 
            - Mac OS X `Menu: Atom > Preferences > Install`
            - Windows `Menu: File > Settings > Install`
            - Linux `Menu: Edit > Preferences > Install`
         2. Search for official platformio-ide package
         3. Install PlatformIO IDE.

    - ##### Clang for Intelligent Code Completion:

        PlatformIO IDE uses Clang for the Intelligent Code Completion. To check that clang is available in your system, please open Terminal and run `clang --version`. If `clang` is not installed, then install it and restart Atom:

        + **Mac OS X**: [Install the latest Xcode](https://developer.apple.com/xcode/download/) along with the latest Command Line Tools (they are installed automatically when you run `clang` in Terminal for the first time, or manually by running `xcode-select --install`

        + **Windows**: Download [Clang 3.9.1 for Windows](http://releases.llvm.org/download.html). Please select “Add LLVM to the system PATH” option on the installation step.

            - [Clang 3.9.1 for Windows (32-bit)](http://releases.llvm.org/3.9.1/LLVM-3.9.1-win32.exe)
            - [Clang 3.9.1 for Windows (64-bit)](http://releases.llvm.org/3.9.1/LLVM-3.9.1-win64.exe)

            ![Step 4](/docs/pio-4.png)

            > ***PLEASE DO NOT INSTALL CLANG 4.0. TEMPORARY, WE SUPPORT ONLY CLANG 3.9.x***
            
            >If you see Failed to find MSBuild toolsets directory error in the installation console, please ignore it and press any key to close this window. PlatformIO IDE uses only Clang completion engine that should work after it without any problems.
        
        + **Linux**: Using package managers: `apt-get install clang` or `yum install clang`.

        + **Other Systems**: Download the latest Clang for the other systems.