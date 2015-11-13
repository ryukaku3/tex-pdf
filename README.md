# tex-pdf > master

### HOW TO USE repository

#### Install nii-tex-pdf.repo
    $ vi /etc/yum.repos.d/tex-pdf.repo
  
    [tex-pdf-git]
    name=CentOS-$releasever - tex-pdf
    baseurl=https://ryukaku3.github.io/tex-pdf/centos/$releasever/
    enabled=0
    gpgcheck=0
    #gpgcheck=1
    #gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-CentOS-$releasever

