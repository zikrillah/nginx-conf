# nginx-conf
This configuration of my personal LAB environment
## Backup first
You can use this configuration on your own environtment with clone this repository and backup you default **nginx.conf**(at **/etc/nginx**) and **default.conf**(at **/etc/nginx/conf.d**) files.
You can backup the files by adding `*.bak` at the end of the file name, using linux command: `$ sudo mv <file>.conf <file>.conf.bak`
## Copy the files
Simply copy the file `nginx.conf` and all files inside `conf.d` directory to your nginx directory **/etc/nginx/conf.d**, to accomplish this use the `cp` command on linux: `$ sudo cp <file> <destination-folder>`
