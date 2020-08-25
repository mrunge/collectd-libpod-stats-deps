# collectd-libpod-stats-deps


    dnf -y install /usr/bin/rpmbuild
    dnf -y install /usr/bin/spectool
    
    mkdir -p ~rpmbuild/SOURCES
   
    cd ~rpmbuild
    
    git clone (this repo) SPECS
    cd SOURCES
    
    spectool -g ../SPECS/<specfile-name>
    cd ../SPECS
    rpmbuild -ba <specfile-name>
