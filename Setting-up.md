# Setting Up Your Computer

Before diving into the exciting software development world, it's important to set up your local machine or personal computer properly. This guide will walk you through the process to ensure your computer is ready for the journey ahead. We will cover the setup for both macOS and Windows.

<aside>
📍 Before we begin, ensure you have administrative access to your computer, as some installations may require it. Use this [article](https://oit.ncsu.edu/it-security/antivirus/how-to-tell-if-you-are-an-administrator/#osx) to confirm that you do.

</aside>

## Installing Visual Studio Code (VS Code)

Visual Studio Code is the code editor you'll use throughout the program. Follow these steps to install it:

- **For macOS:**
    1. Visit the official [VS Code website](https://code.visualstudio.com/).
    2. Download the macOS version.
    3. Open the downloaded file and drag the VS Code icon to the Applications folder.
- **For Windows:**
    1. Visit the official [VS Code website](https://code.visualstudio.com/).
    2. Download the Windows version.
    3. Run the installer and follow the on-screen instructions.

## Choosing a Terminal (iTerm or Hyper)

A terminal is a text-based interface for interacting with your computer. You can choose between iTerm and Hyper:

- **iTerm (macOS only):**
    1. Visit the [iTerm website](https://iterm2.com/).
    2. Download iTerm.
    3. Open the downloaded file and move iTerm to the **Applications** folder.
- **Hyper (macOS and Windows):**
    1. Visit the [Hyper website](https://hyper.is/).
    2. Download Hyper.
    3. Run the installer and follow the on-screen instructions.

## Installing Homebrew (macOS only)

Homebrew is a package manager that simplifies software installation on macOS. Follow these steps to install it:

1. **Install Xcode Command-Line Tools:** Open Terminal and enter this command to install the tools:
    
    ```bash
    xcode-select --install
    ```
    
    Follow the prompts and agree to the installation if required.
    
2. **Install Homebrew:** In Terminal, paste and run this command:
    
    ```bash
    /bin/bash -c "$(curl -fsSL <https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh>)"
    ```
    
3. **Verify Installation:** After the installation, check Homebrew's version by typing:
    
    ```bash
    brew --version
    ```
    
    If you see the version number, Homebrew is installed.
    

## Setting Up Git

Git is a version control system that helps you manage your code. Follow these steps to install Git:

- **For macOS using Homebrew:**
    1. Open Terminal (you can find it using Spotlight).
    2. Type the following command and press Enter to install Git using Homebrew:
        
        ```bash
        brew install git
        ```
        
    3. After the installation is complete, type `git --version` and press Enter to verify the installation.
- **For Windows:**
    1. Visit the official [Git website](https://git-scm.com/downloads).
    2. Download the Windows version.
    3. Run the installer and follow the on-screen instructions.

## Installing C and Build Essentials

C one of the programming languages you will learn. Here's how to install it:

- **For macOS:**
    1. Open Terminal.
    2. Type `xcode-select --install` and follow the prompts to install the command-line tools.
- **For Windows:**
    1. Visit the [MinGW-w64 website](https://sourceforge.net/projects/mingw-w64/) and go to the “Download” section.
    2. Run the installer and follow the on-screen instructions.
    3. During installation, make sure to select the necessary components, including GCC (C compiler) and related tools.
    
    You can read the following [article](https://www.scaler.com/topics/c/c-compiler-for-windows/) for more detailed information.
    

## Installing Python

Python is another programming language you will learn during the program. Now, ;et's get it installed:

- **For macOS:**
    1. Open Terminal.
    2. Type the following command and press Enter to install Python using Homebrew:
        
        ```bash
        brew install python
        ```
        
    3. Once the installation is complete, you're all set.
- **For Windows:**
    1. Visit the official [Python website](https://www.python.org/).
    2. Download the latest version of Python (make sure to choose the installer marked as ”executable installer”).
    3. Run the installer and check the ”Add Python to PATH” box before installing.

## Setting Up Flask

Flask is a web framework for Python. Let's set it up:

- **For macOS and Windows:**
    1. Open a terminal (iTerm or Hyper).
    2. Type `pip install Flask`, and press Enter.

## Installing SQLite

SQLite is a lightweight database engine. Install it like this:

- **For macOS and Windows:**
    1. Visit the [SQLite website](https://www.sqlite.org/index.html).
    2. Download the precompiled binaries for your operating system.
    3. Follow the installation instructions provided on the website.

## Installing Chrome Browser

Finally, we will install Google Chrome. Here's how to install it:

- **For macOS:**
    1. Open Safari or your preferred web browser.
    2. Go to the [official Google Chrome download page](https://www.google.com/chrome/).
    3. Click the "Download Chrome" button.
    4. Once the download is complete, open the file.
    5. Drag the Chrome icon to the "Applications" folder.
    6. You can now open Chrome from the "Applications" folder or your Dock.
- **For Windows:**
    1. Open your current web browser.
    2. Visit the [official Google Chrome download page](https://www.google.com/chrome/).
    3. Click the "Download Chrome" button.
    4. Run the downloaded installer.
    5. Follow the on-screen instructions to complete the installation.
    6. After installation, you can launch Chrome from the desktop or the Start menu.

## Conclusion

Congratulations! You've successfully set up your environment for the program. Now, you're ready to start learning. Remember, we're here to support you every step of the way. If you encounter any issues during setup or have questions, don't hesitate to ask for assistance from the program facilitators.

Happy learning! 🚀
