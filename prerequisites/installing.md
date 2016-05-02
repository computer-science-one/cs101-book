# Installing Ruby

To learn Ruby, you'll need access to a working Ruby interpreter.

## No-install method

Fortunately for you, you can try Ruby without installing anything on your computer!

[Repl.it](https://repl.it/languages/ruby) is a website that gives you an interactive Ruby environment, right from the comfort of your own web browser. If you create an account and sign in, you can even save your "sessions" to your account.

## Install Ruby on your own computer

Ruby runs on most operating systems. We highly recommend installing Ruby on your own computer. By doing this, you can save your work offline. Additionally, you won't need internet access to try out examples or complete your assignments!

[The official "Installing Ruby" page from `ruby-lang.org`](https://www.ruby-lang.org/en/documentation/installation/) has an extensive list of Ruby installation methods and tools.

### GNU/Linux

All worthwhile distributions of the GNU/Linux operating system have an official package for Ruby. You'll need to know what distribution you're on, and what the corresponding "package manager" tool is. For example, if you're on Arch Linux, you would use the `pacman` package manager like so:

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


### Mac

You don't need to do anything special if you're on a Mac. Mac OS X ships with Ruby right out-of-the-box. If you want access to a newer Ruby than the pre-installed version, you can use a third-party tool like [Homebrew](http://brew.sh/) or [RVM](https://rvm.io/).

Once you've installed Homebrew, you can install Ruby by running

```sh-session
$ brew install ruby
```

### Windows

[RubyInstaller](http://rubyinstaller.org/) will get you up and running if you're trying to use Ruby on the Windows operating system.