Bootstrap: docker
From: debian:buster

%labels
    AUTHOR icaoberg
    EMAIL icaoberg@alumni.cmu.edu
    WEBSITE http://linus.cbd.cs.cmu.edu
    VERSION 2.29.2

%post
    /usr/bin/apt-get update && apt-get install -y --no-install-recommends apt-utils
    /usr/bin/apt-get update --fix-missing
    /usr/bin/apt-get install -y wget

####################################################################################
%appinstall bedtools
    wget -nc https://github.com/arq5x/bedtools2/releases/download/v2.29.2/bedtools.static.binary
    mv -v bedtools.static.binary /bin/bedtools
    chmod +x /bin/bedtools

%apphelp bedtools
    bedtools --help    

%apprun bedtools
    bedtools "$@"
