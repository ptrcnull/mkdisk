# mkdisk

generate alpine ext4 images

### usage

```
$ cat disk
version=3.15.1
arch=x86_64
pkgs="openrc busybox-initscripts openssh-server"

setup() {
	rc-update add sshd
}

$ mkdisk disk disk.ext4
```
