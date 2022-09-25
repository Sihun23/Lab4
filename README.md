# Lecture Note 4 (Summary of Shell commands)
## 2022.09.26

**pwd** : shows the current path
```sh
$ pwd
/owner/sihun
```
**cd** : change directory

---
**ls** : list files and directories
- / : root
- . : current directory
- .. : upper-level directory
- ~ : home of current user
- ㅣ : show detatiled information  
```sh
$ cd ..
$ ls -l
```
---
**cp** : copy files and directories
- cp file1 file2 : copies the contents of *file1* into *file2*
- cp file1 dir1 : Copt the contents of *file1* inside of directory *dir1*.  
```sh
$ cp modhule.py backup_module.py
$ cp -r ../neuralintlab .
```
---
**mv** : move files and directories or rename them
- mv file1 file2 : (If *file2* exists), its contents replaced with the content of *file1*.
- mv dir1 dir2 : 
  1. dir2 doesn't exist : *dir1* is renamed *dir2*.
  2. dir2 exists : *dir1* is moved within directory *dir2*.  
```sh
$ mv new_module.py ../neuralintlab
$ mv neuralintlab nil
```
---
**rm** : delete files and directories ***permantely and irreversevely!***  
- rm file1 file2 : Delete *file1* and *file2*.
- rm -r dir1 dir2 : Directories *dir1* and *dir2* are deleted aling with all of their contents.
```sh
$ rm new_module.py
```

**mkdir** : make a new directory. 
---

\[tip]
1. Autocompletion : Press tab key.
2. Past commands : Press up arrow key.
3. Clear : 
```sh
$ clear
```
 
 \[Help command] 
 - **help**
 ```sh
 $ help cd
 ```
 - **man**
 ```sh
 $ man cp
 ```
 - **exit**
 ```sh
 $ exit
 ```
 
