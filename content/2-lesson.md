---
title: Early Phases
nav: true
---

# Phase 1 - Preparation

## Data storage

`First things first: find a place to put your research. Don't lose it. Keep it secure.`

### 🔄 Online storage & sync

 - ⭐️ [Cloudstor](https://cloudstor.aarnet.edu.au) - AU University cloud storage - free, FAST!
 - [Google Drive](https://www.google.com/drive/)
 - [MS OneDrive](https://griffitheduau-my.sharepoint.com/) - use the O365 version

## Backup

`Remember, sync is not the same as backup!`

Just because you have OneDrive or Google Drive does not mean you have a backup. Run a backup tool in addition to these services. Your best, most secure option is to backup both to a physical hard drive and to an online service.

### 🛰 Online backup

 - ⭐️ [Griffith Research Storage](https://research-storage.griffith.edu.au) Research Drive (speedy) and Research Vault
 - ⭐️ [Arq Backup](www.arqbackup/com) - use Arq to back your computer up to your Cloudstor or to your OneDrive.
 - [Backblaze](https://www.backblaze.com) - popular, paid.
 - [RSync](https://rsync.samba.org) - Here's the nice technical option. RSync is a command-line tool for syncing local folders with an external hard drive or network drive.
 

### 💽 Hard-drive backup

 - ⭐️ Time Machine (Mac)
 - ⭐️ Windows Backup (Windows 10)
 - Drag-and-drop - why is this the worst option? Because (a) you will inevitably forget to do it, and (b) each new copy replaces what was there before meaning you can't recover older versions of your work.

## Password security

`The best way to keep your passwords /different and secure/ is to use a password manager. ⭐️ The best /password/ to use is a /passphrase/.`

### 🔐 Password managers

Getting used to using a password manager is a great investment in your overall experience of using the Internet. Most password managers have browser plugins that can fill login forms automatically. 

{% capture text %}
Your preferred browser may not be available on your mobile platform. That means saved passwords in your browser may not be available to you on mobile. Password managers sync data across your desktop and mobile devices so they're more readily available.
{% include card.md header="Why can't I just let my browser remember my passwords?" text=text %}

 - ⭐️ [LastPass](https://www.griffith.edu.au/passwords/lastpass) - Griffith-supported option
 - ⭐️ [Bitwarden](www.bitwarden.com) - free and open source, multiplatform, simple to use. Very modern and well-regarded.
 - [1Password](https://1password.com) - high quality commercial (paid) option. It's been around along time and has a good reputation.
 - [Dashlane](https://www.dashlane.com)

## Getting Organised

`Organisational tools have come a long way since the humble to-do list. Although those are still there too.`

### 📒 Note taking

 - ⭐️ Notion (www.notion.so) - all in one workspace. Free for education (sign up in with Google using Griffith ID)
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

The `workshop-template-b` [repository](https://github.com/evanwill/workshop-template-b) is a skeleton project. 
This [site](https://evanwill.github.io/workshop-template-b/) demonstrates the output on gh-pages, and the content pages serve as examples.

{% capture text %}
1. Fork or import the [repository](https://github.com/evanwill/workshop-template-b) on GitHub.
2. Clone to your local machine, or work on the GitHub web interface to edit files.
3. Edit the `_config.yml` with your info.
4. Edit the content pages in markdown.
5. Add images to the "images" folder.
5. Push to GitHub (or commit on the web interface).
6. In your repo's settings, activate gh-pages, using master branch.{% endcapture %}
{% include card.md header="Overview" text=text %}

## Config

Edit the `_config.yml` to get your workshop website set up.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
Pellentesque eu velit felis. 
Duis fermentum est nec mollis scelerisque. Vivamus interdum efficitur mauris, et dignissim velit egestas vitae. 
Cras dignissim sagittis varius. Pellentesque eu laoreet dui.

```
Praesent congue:
    eros = eget
    accumsan euismod
```

Praesent congue, eros eget accumsan euismod, lorem dui vulputate leo, tincidunt efficitur risus metus ut risus. 
Sed pharetra ipsum orci, eu cursus turpis semper egestas. 

> Pellentesque sodales, felis auctor auctor rutrum, velit quam interdum erat, sit amet placerat urna nisl at justo.

## Substep

Nam maximus eget orci id pretium. Pellentesque feugiat mauris eu nulla viverra consectetur. Nullam rutrum augue eget mauris accumsan, ac elementum tellus lacinia. Sed pretium aliquet tortor in ornare. Sed eget aliquet metus. Integer sed arcu turpis. Duis auctor sollicitudin semper. Cras posuere, neque nec varius cursus, massa libero sodales elit, sed tempor nibh ex sit amet nisi. Quisque consequat ante quis diam malesuada, in imperdiet tortor mattis. Aliquam erat volutpat. Morbi tortor elit, sagittis quis nibh ut, gravida cursus arcu.

{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Be sure to replace all the example values!" width="75%" %}

Ut dapibus lectus tristique efficitur dictum. Quisque efficitur ornare sagittis. Donec ex sem, volutpat quis scelerisque quis, scelerisque non neque. Vivamus convallis felis vel eros pulvinar faucibus. Aliquam finibus pretium odio a pharetra. Nullam ac commodo magna. Fusce et feugiat sem. Nunc vitae scelerisque metus. Aenean sodales placerat mi in aliquet. Curabitur pulvinar auctor mauris quis faucibus. Ut commodo imperdiet ante, at dignissim tellus ultricies ut. Donec at lacus ultrices sem vulputate semper. Donec commodo porta nunc, non tristique mi interdum quis. Phasellus rhoncus bibendum ipsum, ac malesuada augue pulvinar et. Etiam finibus lacus massa, sit amet faucibus lorem consequat sit amet. 
