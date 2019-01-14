# linux-kernel-rt

Go through the following steps to be able to install the new kernel 

```bash
#necessary for apt-get to support https 
sudo apt-get install apt-transport-https
```

Modify sources

```bash
sudo /bin/bash -c "echo 'deb https://raw.githubusercontent.com/ifollow-robotics/linux-kernel-rt/master xenial main' >> /etc/apt/sources.list"
```

Update! Ignore the errors you face

```bash
sudo apt-get update
```

Install the kernel

```bash
sudo apt-get install linux-image-4.16.18-rt12 linux-headers-4.16.18-rt12 
```
