---
name: Application bug report
about: Report a bug related to the Gtk theme to help us improve Yaru
title: ''
labels: ''
assignees: ''

---

<!--
Thank you for contributing to **Yaru**, the Ubuntu's default Theme made by the Community.

If you found a bug please consider to fill below information, this will help us to understand the problem and we don't bother you with other questions :)

Thanks a lot!

(NOTE: you can remove all the text outside the "ISSUE TEMPLATE" message, thanks!)

------ ISSUE TEMPLATE starts HERE ------>

**Expected Behavior**

(What you were trying to do)

**Actual Behavior**

(What happened instead)

**Screenshots**

(Insert here some screenshots to help explain your problem)

**Steps to Reproduce the Problem**

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See problem

**Software that presents the issue**

- Name: [e.g. Nautilus]
- Version: (generally run `$ appname --version`) [e.g. 3.36.3]
- OS version: (run `$ lsb_release -a`) [e.g. Ubuntu 20.04.1]

**Yaru version**

Please report the Yaru version in your system using one of the following commands

* If you just use the default Ubuntu session (since Ubuntu 18.10)

    `$ apt show yaru-theme-gtk`

* If you installed Yaru via Snap (for Ubuntu 18.04)

    `$ snap info communitheme`

* I you installed from the sources, go the Yaru folder and copy the output of the following terminal command instead

    `$ git describe`

**Upstream check**

Please also check if the problem also occurs with the Adwaita upstream theme. Change the Gtk theme by running the following command:

    `$ gsettings set org.gnome.desktop.interface gtk-theme Adwaita`

Then check if the problem is still there.