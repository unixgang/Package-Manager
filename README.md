![BeFunky-snapshot(1)(1)](https://user-images.githubusercontent.com/68412503/120606015-59f9fe80-c46c-11eb-86de-5591ea754b8a.png)


- Fascinating aren't they , code written to collect code
- This is a manual written to know more about you Package Manager


## DEBIAN / BASED
### apt - Advanced Package Tool 
```
  FLAGS :-
   
       install - install a package
       remove - remove a package
       search - search for a package
       update - sync system with repos
       upgrade - upgrade system
       dist-upgrade - upgrade distro as whole
       autoclean - remove obsolete info
       clean - clean all local caches
       autoremove - remove dependencies of a removed package
``` 

-----


## ARCH / ARCH BASED
### pacman - Package Manager / Yay - yet another yogurt
```
  FLAGS :-
   
       -S - install a package
       -Rs - remove a package
       -Ss - search for a package
       -Sy - sync system with repos
       -Syu - upgrade system
       -Sc - clean all local caches
       pacman -Qdtq | pacman -Rs - = remove dependencies of a removed package
       
       [ You can use downgrade from the AUR to downgrade packages that gets broken in an update ]
       
``` 

-----

## GENTOO / GENTOO BASED 
### emerge - Portage
```
  FLAGS :-
   
       [-a]  : install a package
       [-a]C : remove a package
       -S    : search for a package
       -sync : sync system with repos
       -avuDN --with-bdeps y --keep-going world : upgrade whole system
       etc-update : updating system config
``` 

-----

## FEDORA - SILVER BLUE INCLUDED3 
### dnf - stand for nothing
```
  FLAGS :-                                                           SILVERBLUE :-
   
       install - install a package                               |  ostree remote list : list configured remotes
       remove - remove a package                                 |  ostree remote add <REMOTE> <URL> : add remote
       search - search for a package                             |  ostree remote delete <REMOTE> : remove remote
       update - sync system with repos                           |  ostree remote refs <REMOTE> : list remote contents
       reinstall - reinstall package                             |  rpm-ostree install <PACKAGE> : install package as a layer
       upgrade - upgrade system                                  |  rpm-ostree uninstall <PACKAGE> : remove a layered package
       distro-syn - upgrade distro as whole                      |  rpm-ostree status : system status
       clean-all - remove obsolete info                          |  rpm-ostree upgrade : upgrade to latest snapshot
       autoremove - remove dependencies of a removed package     |  rpm-ostree upgrade --check : check for available updates
                                                                 |  rpm-ostree rebase <REMOTE>:<BRANCH> : switch to a different OS branch
                                                                 |  rpm-ostree rollback : rollback to the previous deployment
                                                                 |  rpm-ostree cleanup --rollback : remove previous deployment


``` 
