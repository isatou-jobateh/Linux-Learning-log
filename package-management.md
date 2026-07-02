Linux Learning Log Summary
Topic: Package Management (apt)
What I Learned
* A package is software that can be installed on Linux.
* Ubuntu uses the APT (Advanced Package Tool) package manager.
* APT allows me to update package information, upgrade installed software, install new packages, remove packages, and search for available software.

Commands Learned

Command	                            Purpose
sudo apt update	                    Refresh the package list
sudo apt upgrade	                  Upgrade installed software
sudo apt install package-name	      Install a package
sudo apt remove package-name	      Remove a package
apt search package-name	            Search for a package
apt list --installed	              List installed packages
apt list --installed | grep package-name	  Check if a specific package is installed

Key Concepts

* Package: Software that can be installed on Linux.
* APT: Ubuntu’s package manager.
* Update: Refreshes the package list.
* Upgrade: Updates installed software to newer versions.
* Install: Adds new software.
* Remove: Uninstalls software.
* Search: Finds available software packages.

Challenges
* Remembering the difference between update and upgrade.
* Understanding that update refreshes the package list, while upgrade installs newer versions of software.
Result
* I can update and upgrade a Linux system.
* I can install, search for, verify, and remove software packages using APT.
