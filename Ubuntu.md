### Change root password from recovery mode root shell

    mount -rw -o remount /
    ls /home
    passwd <username>

### List and choose java version

    sudo update-alternatives --config java

### Decompress .gz file

    gzip -dk file.gz
    gzip -d file.gz # .gz file will be removed

### scp

    scp <local_file> <user>@<host>:<path>
    scp -r <user>@<host>:<dir_path> <local_dir_path>