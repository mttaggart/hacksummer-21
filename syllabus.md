# Syllabus

## Session 0: The Linux Operating System

### Background

* Operating systems
* Linux history
* UNIX
* Bell Labs
* Open source
* Linux today
* Distributions
* We'll use Ubuntu
* Installing on VirtualBox

## Session 1: The Command Line

### Navigating the filesystem

* Don't be afraid
* The "shell"
* Command syntax
* Options flags
* `pwd`
* `whoami`
* `ls`
* `cat`
* `man`
* Important linux files/folders
* Everything is a file

### Files and Permissions

* Users
* `id`
* /etc/passwd
* Owners and groups
* The root user
* `sudo`
* rwx/bit mode
* `chmod`/`chown`
* Hidden files

### Piping and Output Redirection

* `|`
* `>` and `>>`
* File descriptors
* `find` and `grep`
* File hashes (`sha256sum` and `md5sum`)

### Installing Packages

* `apt`
* `snap`
* `dpkg`
* `sl`
* `cowsay`
* Updating

## Session 2: Vim

* Yes, it's hard
* Worth it
* Opening Vim
* Modes
* Navigating
    * `hjkl`
    * `gg`/`G`
    * `e/b`
    * `$`/`^`
    * `#gg`
    * `{}`
* Insert Mode
* Saving/Opening/Quitting
    * `:w`
    * `:wq`
    * `:x`
    * `:e`
    * `u/C-r` 
* Entering commands
    * `set nu`
    * `:`
    * `:h`
* Getting help
* Copy/Cut/Paste
    * `y`/`yy`
    * `d`/`dd`
    * `x`/`#x`
* Visual Mode
    * Visual Block Mode
    * Commands inside block mode   
* Searching
    * `/`
    * `%s`
    * `V :s`
* Regular Expressions primer
* Shell piping
* Tabs/Windows
    * `:tabnew`
    * `:tabclose`
    * `C-w-v/s` 
* Vimrc
* Vim Plugins
    * VimPlug
    * VimAwesome

## Session 3: Networking

### IP Basics

* IP Addresses
* `ip`
* Routes
* Subnets
* Gateways
* `ping`

### Clients and Servers

* The client/server model
* `nc`
* Setting up a basic web server
* `nginx`
* Ports

## Session 4: Scripting

### Bash Scripts

* Common shell interpreter
* Automating basic tasks
* Syntax overview

## Session 5: Containers

* Force multiplier for your server
* Container runtime options
* Deploy applications with sandboxing
