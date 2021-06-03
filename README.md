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
  FLAGS :-                                                           SILVERBLUE :- [O] - ostree , [R] - rpm-ostree
   
       install - install a package                            |  [O] remote list : list configured remotes
       remove - remove a package                              |  [O] remote add <REMOTE> <URL> : add remote
       search - search for a package                          |  [O] remote delete <REMOTE> : remove remote
       update - sync system with repos                        |  [O] remote refs <REMOTE> : list remote contents
       reinstall - reinstall package                          |  [R] install <PACKAGE> : install package as a layer
       upgrade - upgrade system                               |  [R] uninstall <PACKAGE> : remove a layered package
       distro-syn - upgrade distro as whole                   |  [R] status : system status
       clean-all - remove obsolete info                       |  [R] upgrade : upgrade to latest snapshot
       autoremove - remove dependencies of a removed package  |  [R] upgrade --check : check for available update
                                                              |  [R] rebase <REMOTE>:<BRANCH> : switch branch
                                                              |  [R] rollback : rollback to the previous deployment
                                                              |  [R] cleanup --rollback : remove previous deployment


``` 
