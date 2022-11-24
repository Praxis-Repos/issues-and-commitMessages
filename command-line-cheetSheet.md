#### Ubuntu
``$ sudo``
Stands for "**s**uper **u**ser, **do**". Grants super user rights for the duration of the current command and often results in a system password entry request.

``$ sudo apt update``
Re-downloads the current package update list.

``$ sudo apt install (search term)``
Shows a list of all packages that match the search term.

``$ sudo apt install (software name)``
Installs the package with the corresponding software name.

``$ sudo apt remove (software name)``
Removes the main data of the corresponding software package without removing the configuration data. When reinstalling the same software, it will again receive the same configuration data.

``$ sudo apt autoremove``
Removes dependency packages that are not used anymore by any installed software packages.

``$ sudo pkill (process name)``
Stops and closes running process with the corresponding name.