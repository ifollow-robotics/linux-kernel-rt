# linux-kernel-rt
Go through the following steps to be able to install the new kernel 
 <pre><code>
#necessary for apt-get to support https 
sudo apt-get install apt-transport-https

# modify sources
cat << EOF >> /etc/apt/sources.list
deb https://raw.githubusercontent.com/ifollow-robotics/linux-kernel-rt/master xenial main
EOF

# Update! Ignore the errors you face
sudo apt-get update
# Install the kernel
sudo apt-get install linux-image-4.16.18-rt12 linux-headers-4.16.18-rt12 
</code></pre> 
