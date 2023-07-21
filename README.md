# ansible_pull_jrd_workstation
Ansible pull files for homelab workstation(s) 

currently Pop!_OS

## local.yml

 - connects as `localhost`
 - pre_tasks uses `apt` to update the repositories
 - tasks uses include to pull in individual `.yml` runing specific tasks

## tasks (directory)

### tweaks.yml



### packages.yml



### packages_pip.yml



### software_flatpak.yml



### files.yml

used to copy files into various locations
  - updates wallpaper images from the pictures directory already on the machine 
  - copies bash files into place.