# Installing Ruby

To learn Ruby, you'll need access to a working Ruby interpreter.

## No-install method

Fortunately for you, you can try Ruby without installing anything on your computer!

From the website [Repl.it](https://repl.it/): 

> [Repl.it] is an online environment for interactively exploring programming languages.

Visit [`https://repl.it/languages/ruby`](https://repl.it/languages/ruby) to start an interactive Ruby environment, right from the comfort of your own web browser. If you create an account and sign in, you can even save your "sessions" to your account.

## Install Ruby on your own computer

Ruby runs on most operating systems. We highly recommend installing Ruby on your own computer. By doing this, you can run your code offline. Additionally, you won't need internet access to try out examples or complete your assignments!

[The official "Installing Ruby" page from `ruby-lang.org`](https://www.ruby-lang.org/en/documentation/installation/) has an extensive list of Ruby installation methods and tools. The following sections provide brief instructions for installing Ruby on some common platforms.

### GNU/Linux

All worthwhile GNU/Linux distributions have an official package for Ruby. Detailed install steps:

 1. Open a terminal.
 2. Use the appropriate package manager that corresponds to your distribution.

  For Arch Linux:
  ```sh-session
  $ sudo pacman -S ruby
  ```

  For Debian / Ubuntu:
  ```sh-session
  $ sudo apt-get install ruby
  ```

  For Red Hat / Fedora / CentOS:
  ```sh-session
  $ sudo dnf install ruby
  ```

### Mac OS

You don't need to do anything special if you're on a Mac. Mac OS X ships with Ruby right out-of-the-box. If you want to use a different version of Ruby than the pre-installed one, we recommend using a third-party tool like [Homebrew](http://brew.sh/).

#### How to install a different Ruby using Homebrew (Optional)

1. Open spotlight by pressing <kbd>Command+Space</kbd>. You can also click the magnifying glass icon in the upper-right corner of the menu bar.
  ![](images/mac-osx/yosemite-search_button.png)

2. In the search field, type the word "Terminal" and press <kbd>Return</kbd>.
3. On http://brew.sh/ , under the "Install Homebrew" section, paste the provided command into the terminal window you opened in step 2. Press <kbd>Return</kbd>.
4. Follow any installation instructions.
5. Once Homebrew has been fully installed, use the following command to install Ruby:

  ```sh-session
  $ brew install ruby
  ```

### Windows

[RubyInstaller](http://rubyinstaller.org/) will get you up and running if you're trying to use Ruby on the Windows operating system. After downloading the installer program, follow these instructions to get Ruby fully set up and working on your PC.

1. The installer program does not have a digital signature, so click "Run" at the security warning dialog.

  ![](images/ruby-installer-windows/01.png)
  
2. Select your preferred language.

  ![](images/ruby-installer-windows/02.png)

3. Accept the RubyInstaller license agreement.

  ![](images/ruby-installer-windows/03.png)

4. Set install folder and options. Be sure to check both the "Add Ruby executables to your PATH" and "Associate .rb and .rbw files with this Ruby installation" checkboxes.

  ![](images/ruby-installer-windows/04.png)

5. Click the "Finish" button.

  ![](images/ruby-installer-windows/05.png)