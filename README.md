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
