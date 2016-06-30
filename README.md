# go-linux-install-package1.6.2

    tar -C /usr/local -xzf go1.6.2.linux-amd64.tar.gz
    (Typically these commands must be run as root or through sudo.)

    Add /usr/local/go/bin to the PATH environment variable. You can do this by adding this line to your /etc/profile (for a system-wide installation) or $HOME/.profile:

    export PATH=$PATH:/usr/local/go/bin

#Installing to a custom location

    The Go binary distributions assume they will be installed in /usr/local/go (or c:\Go under Windows), but it is possible to install the Go tools to a different location. In this case you must set the GOROOT environment variable to point to the directory in which it was installed.

    For example, if you installed Go to your home directory you should add the following commands to $HOME/.profile:

    export GOROOT=$HOME/go
    export PATH=$PATH:$GOROOT/bin
    Note: GOROOT must be set only when installing to a custom location.
