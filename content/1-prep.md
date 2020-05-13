---
title: Preparation
nav: true
--- 


# Phase 1 - Preparation

{% include figure.html img="ch-preparation.png" alt="A boy and his tiger look out to the distance" caption="Preparing to embark" width="75%" %}

## Data storage

{% capture ftf %}**First things first:** find a place to put your research. Don't lose it. Keep it secure.{% endcapture %}
{% include alert.md text=ftf color=primary %}

{% capture text %}
 - ⭐️ [Cloudstor](https://cloudstor.aarnet.edu.au) is powered by AARNet (The Australian Academic Research Network) and provides students and researchers with a Terabyte of free, ultra-fast storage. It's easy to set up and works just like Dropbox.
 
 <iframe width="560" height="315" src="https://www.youtube.com/embed/mGaqxrrxfgA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 - [Google Drive](https://www.google.com/drive/)
 - [MS OneDrive](https://griffitheduau-my.sharepoint.com/)

{% capture note %}**Note:** When signing in to OneDrive, be sure to use your Griffith credentials rather than a personal Microsoft account. {% endcapture %}
{% include alert.md text=note color="info" %}{% endcapture %}
{% include card.md header="🔄 Online storage & sync" text=text %}
 
## Backup

{% capture warning %}**Remember:** sync is not the same as backup!{% endcapture %}
{% include alert.md text=warning color="warning" %}

{% capture backupmodal %}
Because when you're syncing, if you delete something from your computer, it's also deleted from the remote copy. That's the **opposite** of a backup!{% endcapture %}
{% include modal.md button="Really? Why not?" color="info" title="Why is a sync not a backup?" text=backupmodal %}


You should run a backup tool *in addition* to the services above. Your best, most secure option is to backup both to a physical hard drive and to an online service.

{% capture text %}
 - ⭐️ [Griffith Research Storage](https://research-storage.griffith.edu.au) is built on the same technology as Cloudstor and is very fast. Research Vault is available for you to store data you are no longer actively using.
 - ⭐️ [Arq Backup](www.arqbackup/com) - use Arq to back your computer up to your Cloudstor or to your OneDrive. It's not free, but the $50 license is less than the cost of a hard drive and makes backing up completely automatic.
 - [Backblaze](https://www.backblaze.com) - popular, paid.
 - [RSync](https://rsync.samba.org) - Here's the nice technical option. RSync is a command-line tool for syncing local folders with an external hard drive or network drive.{% endcapture %}
{% include card.md header="🛰 Online backup" text=text %}

{% capture hdbackups %}
 - ⭐️ Time Machine (Mac)
 - ⭐️ Windows Backup (Windows 10)
 - Drag-and-drop (the worst option)

{% include card.md header="💽 Hard-drive backup" text=hdbackups %}

Why is drag-and-drop the worst way to back up?


{% capture why %}
Because (a) you will inevitably forget to do it at some point, and (b) each new copy replaces what was there before meaning you can't recover older versions of your work.{% endcapture %} 
{% include modal.md button="Why?" color="info" title="Why drag and drop is a bad idea" text=why %}{% endcapture %}

---

## Password security

{% capture text %}The best way to keep your passwords *different and secure* is to use a password manager. ⭐️ The best *password* to use is a *passphrase*.{% endcapture %}
{% include alert.md text=alert color="tertiary" %}

### 🔐 Password managers

Getting used to using a password manager is a great investment in your overall experience of using the Internet. Most password managers have browser plugins that can fill login forms automatically. 

{% capture text %}
You could, but you would be missing out on a few of the key benefits of password managers, like checking that your passwords aren't being reused across services, generating new passwords for you and syncing your passwords across mobile and desktop devices.
{% include figure.html img="ch-preparation.png" alt="A boy and his tiger look out to the distance" caption="Preparing to embark" width="75%" %}
{% endcapture %}
{% include modal.md button="Why can't I just let my browser remember my passwords?" color="info" title="Why not save in a browser" text=text %}


{% capture text %}
 - ⭐️ [LastPass](https://www.griffith.edu.au/passwords/lastpass) is Griffith's supported password manager. It is available to all staff. 
 - ⭐️ [Bitwarden](www.bitwarden.com) is free and open source, multiplatform, simple to use. Very modern and well-regarded.
 - [1Password](https://1password.com) - high quality commercial (paid) option. It's been around along time and has a good reputation.
 - [Dashlane](https://www.dashlane.com){% endcapture %}
{% include card.md header="Recommended password managers" text=text %}

---

## Getting Organised

{% capture text %}Organisational tools have come a long way since the humble to-do list. Although those are still there too.{% endcapture %}
{% include alert.md text=text color="secondary" %}

{% capture text %}
 - ⭐️ [Notion](www.notion.so) - all in one workspace. Free for education (sign in with Google using Griffith ID)
 - ⭐️ [Microsoft OneNote](https://www.onenote.com/hrd)
 - [Airtable](www.airtable.com) - online relational database
 - [Evernote](https://evernote.com)
 - [Rocketbook](https://getrocketbook.com.au/) is a new tool introduced by a previous attendee at this workshop. It captures your written notes in a paper book and converts it to digital text.{% endcapture %}
{% include card.md header="📒 Note taking" text=text %}

{% capture text %}
 - ⭐️ [Diagrams.net](https://app.diagrams.net/) Fully free, with web and desktop versions. A wide range of templates. Integrates with OneDrive and Google Drive.
 - [MindMeister](https://www.mindmeister.com) - mind mapping tool. connect through O365 at Griffith
 - [MindNode](https://mindnode.com) is a popular Mac and iOS option.
 - [Scapple](https://www.literatureandlatte.com/scapple/overview)
 - [MindJet](https://www.mindjet.com){% endcapture %}
{% include card.md header="🧠 Mind-mapping" text=text %}
 
{% capture text %}
**Recommended**
 - [Microsoft To-Do](http://to-do.office.com) - formerly Wunderlist. Syncs with O365. Captures to-dos from flagged emails.
 - [Trello](trello.com) - Kanban-style task management
 
**Other options**
 - [Remember the Milk](https://www.rememberthemilk.com)
 - Things app (Apple devices)
 - Asana{% endcapture %}
{% include card.md header="✅ To-do apps" text=text %}
 
 ---
 
{% capture text %}**All done here?** Head to the [next page](2-discovery.html) or [ask a question](https://griffithu.padlet.org/y_banens1/60je7s1g90b3f69h){:target="_blank"}. 
{% endcapture %}
{% include alert.md text=text color="success" %}
