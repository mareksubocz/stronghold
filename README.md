# Fortify

People like their computers to be secure.

This script makes that easy.

Fortify is a step-by-step configuration tool to help secure MacOS Sierra and High Sierra.

[![asciicast demo](https://asciinema.org/a/MGEPQNTustyLj8m9pXKdUbPlM.png)](https://asciinema.org/a/MGEPQNTustyLj8m9pXKdUbPlM?autoplay=1)

**Warnings**
---

+ Ensure you have up-to-date backups. This script modifies system settings and there is a possibility that it damages your system.

**Configuration Options**
---

1. Connectivity

    + Enable Firewall?
        - Enable Logging?
        - Enable Stealth Mode?
        - Prevent Automatic Whitelisting?

    + Disable Captive Portal Assistant?

2. User Metadata Storage and Collection

    + Clear language modeling, spelling and suggestion data and disable data collection?
    + Clear QuickLook metadata and disable logging?
    + Clear and disable SiriAnalytics database?
        - WARNING: This kills Siri.
    + Clear Quarantine Data and disable data collection from downloaded files?

3. General Safety

    + Lock Mac as soon as screen saver starts?
    + Display all file extensions?
    + Disable saving to the cloud by default?
    + Show hidden files in Finder?


**Sources**
-----

+ https://github.com/drduh/macOS-Security-and-Privacy-Guide
+ http://newosxbook.com/files/moxii3/AppendixA.pdf

**How to Contribute**
---

1. Clone repo and create a new branch: `$ git checkout https://github.com/alichtman/fortify -b [name_for_new_branch]`.
2. Make changes and test
3. Submit Pull Request with comprehensive description of changes
