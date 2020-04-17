---
title: Prep
nav: true
--- 


# Phase 1 - Preparation

## Data storage

{% capture alert %}First things first: find a place to put your research. Don't lose it. Keep it secure.{% endcapture %}
{% include alert.md text=alert color=primary %}

### 🔄 Online storage & sync

 - ⭐️ [Cloudstor](https://cloudstor.aarnet.edu.au) - AU University cloud storage - free, FAST!
 - [Google Drive](https://www.google.com/drive/)
 - [MS OneDrive](https://griffitheduau-my.sharepoint.com/) - use the O365 version

## Backup

{% capture alert %}Remember, sync is not the same as backup!{% endcapture %}
{% include alert.md text=alert %}

Just because you have OneDrive or Google Drive does not mean you have a backup. Run a backup tool in addition to these services. Your best, most secure option is to backup both to a physical hard drive and to an online service.

### 🛰 Online backup

 - ⭐️ [Griffith Research Storage](https://research-storage.griffith.edu.au) Research Drive (speedy) and Research Vault
 - ⭐️ [Arq Backup](www.arqbackup/com) - use Arq to back your computer up to your Cloudstor or to your OneDrive.
 - [Backblaze](https://www.backblaze.com) - popular, paid.
 - [RSync](https://rsync.samba.org) - Here's the nice technical option. RSync is a command-line tool for syncing local folders with an external hard drive or network drive.

### 💽 Hard-drive backup

 - ⭐️ Time Machine (Mac)
 - ⭐️ Windows Backup (Windows 10)
 - Drag-and-drop - why is this the worst option? Because (a) you will inevitably forget to do it at some point, and (b) each new copy replaces what was there before meaning you can't recover older versions of your work.

---

## Password security

{% capture alert %}The best way to keep your passwords /different and secure/ is to use a password manager. ⭐️ The best /password/ to use is a /passphrase/.{% endcapture %}
{% include alert.md text=alert color=tertiary %}

### 🔐 Password managers

Getting used to using a password manager is a great investment in your overall experience of using the Internet. Most password managers have browser plugins that can fill login forms automatically. 



{% include figure.html header="Why can't I just let my browser remember my passwords?" text=text %}

 - ⭐️ [LastPass](https://www.griffith.edu.au/passwords/lastpass) - Griffith-supported option
 - ⭐️ [Bitwarden](www.bitwarden.com) - free and open source, multiplatform, simple to use. Very modern and well-regarded.
 - [1Password](https://1password.com) - high quality commercial (paid) option. It's been around along time and has a good reputation.
 - [Dashlane](https://www.dashlane.com)

---

## Getting Organised

{% capture alert %}Organisational tools have come a long way since the humble to-do list. Although those are still there too.{% endcapture %}
{% include alert.md text=alert color=secondary %}

### 📒 Note taking

 - ⭐️ Notion (www.notion.so) - all in one workspace. Free for education (sign in with Google using Griffith ID)
 - ⭐️ Microsoft OneNote (https://www.onenote.com/hrd)
 - Airtable (www.airtable.com) - online relational database
 - Evernote (https://evernote.com)
 - Rocketbook (https://getrocketbook.com.au/)

### 🧠 Mind-mapping

Recommended
 - ⭐️ Diagrams.net (https://app.diagrams.net/) Fully free, integrates with OneDrive and Google Drive
 - MindMeister (https://www.mindmeister.com) - mind mapping tool. connect through O365 at Griffith
 - MindNode (https://mindnode.com)
 - Scapple (https://www.literatureandlatte.com/scapple/overview)
 - MindJet (https://www.mindjet.com)
 
 ### ✅ To-do apps
 
Recommended
 - Microsoft To-Do (http://to-do.office.com - formerly Wunderlist) - syncs with O365. Captures to-dos from flagged emails.
 - Trello (trello.com) - Kanban-style task management
Other options
 - Remember the Milk
 - Things app (Apple devices)
 - Asana
 
# Before we begin

We are going to have to get a few things in place before you join us for the workshop.

`First things first: find a place to put your research. Don't lose it. Keep it secure.`
### 🔄 Online storage & sync

 - ⭐️ Cloudstor (https://cloudstor.aarnet.edu.au) - AU University cloud storage - free, FAST!
 - Google Drive (https://www.google.com/drive/)
 - MS OneDrive (https://griffitheduau-my.sharepoint.com/) - use the O365 version


# Workshop Prep

To create your own materials using `workshop-template-b`, please create a free [GitHub account](https://github.com/join) if you do not have one already.
Basic familiarity with the GitHub web interface will be helpful.

For a quick introduction check out GitHub's [Hello World guide](https://guides.github.com/activities/hello-world/) and [Try Git](https://try.github.io/).

It is possible to create a website with this template using only GitHub's web interface--in fact, it works great!
However, for more advanced uses you will want Git, Ruby, and Jekyll installed on your computer to do local development.

{% capture text %}
1. Have a [GitHub](https://github.com) account.
2. Fork or import this [repository](https://github.com/evanwill/workshop-template-b).
3. Optional: have [Git](https://git-scm.com/), [Jekyll](https://jekyllrb.com/), and a nice [text editor](https://code.visualstudio.com/) installed.
{% endcapture %}
{% include card.md text=text header="Setup Overview" %}

# Local Jekyll Setup [optional]

## Install Git

[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html), [distributed](https://en.wikipedia.org/wiki/Distributed_version_control) version control system. [GitHub](https://github.com/) is a Git repository hosting service, a place to store and sync your work in the cloud--your Jekyll and GitHub Pages projects will be under Git version control, so you need the software on your machine. 

- Windows: install [Git for Windows](https://git-for-windows.github.io/) using the default options. This will give you Git, Git Bash, and Git GUI. Git Bash is a great terminal that lets you use UNIX style commands on Windows.
- Mac: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, download the official [Mac installer](https://git-scm.com/downloads).
- Linux: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, install from your distribution's software center or package manager (for Ubuntu `sudo apt install git`).

If you are interested in using a visual GUI application integrated with GitHub, Windows and Mac users should also install [GitHub Desktop](https://desktop.github.com/) using the default options.
You can install GitHub Desktop in addition to other versions of Git.

There are other [GUI apps available](https://git-scm.com/downloads/guis) for managing and visualizing Git repositories, including Linux options.

## Install Ruby

[Ruby](https://www.ruby-lang.org/en/) is a fairly young and developing programming language with some unique features. 
To use Jekyll, you do not need to know anything about Ruby, but if you are curious, check out [Ruby in 20 minutes](https://www.ruby-lang.org/en/documentation/quickstart/).
Frustratingly, different versions have many dependency and incompatibility problems.
Because of these issues, many use Ruby Managers, such as [RVM](http://rvm.io/), to switch between versions.
However, if you are just interested in working with Jekyll, using an installer for your OS should be sufficient.
Jekyll requires a Ruby version > 2.2.5.

- **Windows:** Use [RubyInstaller for Windows](https://rubyinstaller.org/). 
    - First, [download](https://rubyinstaller.org/downloads/) the suggested stable version "WITH DEVKIT" (as of this writing, Ruby+Devkit 2.4.X (x64)) and double click to install. Use the install defaults, but make sure "Add Ruby executables to your PATH" is checked. On the final step, ensure the box to start the MSYS2 DevKit is checked.
    - Second, the installer will open a terminal window with options to install MSYS2 DevKit components. Choose option 3, "MSYS2 and MINGW development toolchain", or simply press ENTER to install all the necessary dependencies. (This installer can be restarted by typing `ridk install` into a command prompt)
- **Mac:** OS X has a version of Ruby installed by default. Check the version with `ruby -v`. If it is > 2.2.5 you can use the system Ruby. However, a newer version can be installed using [Homebrew](https://brew.sh/), `brew install ruby`, or a manager such as [rbenv](https://github.com/rbenv/rbenv) or [RVM](http://rvm.io/). Check the official Jekyll [Mac install docs](https://jekyllrb.com/docs/installation/#macOS) for tips.
- **Linux:** Even though the version will not be the most up-to-date, the simplest method is to use your distro's repositories. For example on Ubuntu, `sudo apt install ruby-full`. Make sure the repository version is > 2.2.5. You will also need the build tools Make and GCC, on Ubuntu get them with `sudo apt install build-essential`. For a more up-to-date version, use a manager such as [RVM](http://rvm.io/).

## Install Jekyll

Jekyll is a Gem, a software package installed via Ruby's management system called RubyGems (similar to Python's Pip). 
Open a terminal and type:
`gem install jekyll bundler`

This will take a minute as Gem installs all the dependencies and builds extensions. 

{% capture alert %}*Note:* Jekyll does not officially support Windows, however it is cross platform (they just don’t officially write windows documentation or check for bugs).
There is a [Jekyll on Windows](https://jekyllrb.com/docs/windows/#installation) page, but it can be out of date and inaccurate.{% endcapture %}
{% include alert.md text=alert color="warning" %}

# Text Editor

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/), Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for managing Jekyll projects.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)
