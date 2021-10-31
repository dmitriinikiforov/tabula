### Change root password from recovery mode root shell

    mount -rw -o remount /
    ls /home
    passwd <username>

### List and choose java version

    sudo update-alternatives --config java

### Decompress .gz file

    gzip -dk file.gz
    gzip -d file.gz # .gz file will be removed
