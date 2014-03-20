tcpflow classic
===============
tcpflow is one of my favourite tools when developing resful webservices, unfortunately the latest version available via homebrew has become bloated and complicated with unnecessary options and features, this is my attempt at going back to a simpler time. 

This package is based on tcpflow 0.21 plus some patches from the Debian/Ubuntu distribution.

i.e [tcpflow-0.21](https://launchpad.net/ubuntu/+archive/primary/+files/tcpflow_0.21.ds1.orig.tar.gz) + [patches](https://launchpad.net/ubuntu/+archive/primary/+files/tcpflow_0.21.ds1.orig.tar.gz) + a little bit of porting to osx = tcpflow-classic-0.22

In order to install from homebrew

```brew tap rikf/tcpflowclassic```

and then

```brew install tcpflow-classic```

**Note the binary that is installed is still called tcpflow, just like the old days**

Happy coding :)
