---
layout: page
title: Dundee Software Carpentry Workshop
subtitle: Specific details for the Dundee configuration
minutes: 15
---
# Specific notes about the Dundee setup

Every IT installation is different and Dundee is no exception. We are using a Windows based computer with Git-bash installed. 
Read the following notes carefully in order to get it all to behave.

## Your home directory
All users in Dundee have a home directory which is mounted as drive `H:\`. No matter which computer you log in to, 
this drive will always be mounted there. In many of the tutorials there will be references to a home directory 
being `/Users/fredbloggs`, (Mac) `C:\Users\fredbloggs` (Windows), or `/usr/fredbloggs` (Linux) where __*fredbloggs*__ 
is the users username. On the Dundee computers it is `H:\`. If you are using your own computer then it may be one 
of the other options, or something completely different. A helper can advise you.

## Finding and starting Git-Bash
**Git-Bash** has only just been deployed to the desktop and may not appear in the Windows menu.

* **Easy Route**

    Click on the Windows button, then select `All Programs`, `School Software`, `Life Sciences`, `General` and a *Git-Bash* icon should be there.

* **Alternative Route to install Git-Bash**

1  Click on the Windows button, select 'Documents' from the list on the right side of the popup to open a file explorer window.
1  Click in the file explorer location bar and set the location to **_\\dundee\media\apps\Other\Git\GitforWindows\Installer_**
1  Click `Install`. This will (after a short while) run a terminal window which takes some time to complete. It is a good job to do this as soon as you log in the first time.
1 Click on the Windows button, then `All Programs` and `Update Shortcuts`. 
1 Follow the **Easy Route** above.


## Editors
We do not have any editors installed except **vi** which is arcane, powerful, very cranky and not novice friendly. So we'll ignore that 
though you may see an instructor using it to do a quick edit. Instead we will be using **Notepad++**. This can be found by clicking on the Windows button, then `All Programs`, `Utilities and Accessories`. You will then find the `Notepad++` icon.

### Configuring Git to use Notepad++
At a Git-Bash prompt type
```git config --global core.editor "'C:\Program Files (x86)\Notepad++\notepad++.exe' -multiInst -notabbar -nosession -noPlugin"```
This will now launch Notepad++ whenever Git requires an editor.
\`Dundee edition\`
