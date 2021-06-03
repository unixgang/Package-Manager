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
  FLAGS :-                                                           

       install - install a package              
       remove - remove a package                
       search - search for a package            
       update - sync system with repos          
       reinstall - reinstall package            
       upgrade - upgrade system                 
       distro-syn - upgrade distro as whole     
       clean-all - remove obsolete info         
       autoremove - remove unwanted packages    
                                                     
                                                     
  SILVERBLUE :- [O] - ostree , [R] - rpm-ostree
  
       [O] remote list : list configured remotes
       [O] remote add <REMOTE> <URL> : add remote
       [O] remote delete <REMOTE> : remove remote
       [O] remote refs <REMOTE> : list remote contents
       [R] install <PACKAGE> : install package as a layer
       [R] uninstall <PACKAGE> : remove a layered package
       [R] status : system status
       [R] upgrade : upgrade to latest snapshot
       [R] upgrade --check : check for available update
       [R] rebase <REMOTE>:<BRANCH> : switch branch
       [R] rollback : rollback to the previous deployment
       [R] cleanup --rollback : remove previous deployment
``` 
