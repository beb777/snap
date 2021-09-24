# snap
## installation of snap 
> `sudo dnf install snapd`  ##fedora 
>
> `sudo apt install snapd`   ## debian and ubuntu
> 
>  > `yaourt -S snapd`  #arch based
>
>  > `sudo systemctl enable --now snapd.socket` # arch based
>  
> `sudo snap install snap-store`   


### Installing snaps

Once you found the snap you are looking for, you can install it with the below command:

> `sudo snap install <snap_name>`

List out installed snaps

You can use the below command to see the snaps you have installed along with their versions and the developer:

### snap list

> `Update an installed snap app`

Snaps are updated periodically to their latest version. In case you are trying to do it manually, type in the below command in the terminal:

> `sudo snap refresh <snap_name>`

### Uninstall a snap package

To remove a snap

> `sudo snap remove <snap_name>`






