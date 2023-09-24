
1) Just install the latest jdk from oracle (for debian based distros install .deb): https://www.oracle.com/java/technologies/downloads/s

then install it with installer or: `sudo dpkg -i jdk-20_linux-x64_bin.deb`


2) To change the jdk to newer version (e.g. jdk21), change the alternatives: 

`sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-21/bin/java 1` 

`sudo update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk-21/bin/javac 1`