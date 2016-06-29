# go-linux-install-package1.6.2
tar -C /usr/local -xzf go1.6.2.linux-amd64.tar.gz
(Typically these commands must be run as root or through sudo.)

Add /usr/local/go/bin to the PATH environment variable. You can do this by adding this line to your /etc/profile (for a system-wide installation) or $HOME/.profile:

export PATH=$PATH:/usr/local/go/bin
