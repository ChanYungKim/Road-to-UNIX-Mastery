# Road-to-UNIX-Mastery

## common commands

__pwd__

__clear__

__ls__

__cd__

__echo__

__cat__

__grep__

__sort__

__|, pipe__

__cp [-i, -n, -u, -R, -v]__

__mv [-i, -u, -v]__

__mkdir {folder1, folder2, ...} [-p folder1/folder2/...]__ ***

__rmdir [-p parent_directory/child_directory, -pv ***]__

__rm [-r, -rv]__

## user permissions
![](./resource/IMG_2954.jpeg)
 - chmod [g, u, o, a, +, =, -, r/w/x]
    - chmod [g, u, o, a][+/=/-][r/w/x] [file_name/directory_name]
 - chown [user_name/user_name __:__ group_name (both)]
 - chgrp [group_name]

 ## installation from linux repos
 
 - ```
 sudo yum update
 sudo yum install package-name
 ``` : REHL based

 - `sudo apt-get install package-name` : Debian based

 - `sudo dnf install package-name` : Fedora based

 
__su / su (your username)__ 

__sudo__