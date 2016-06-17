centos-stunnel-systemd
===============================

CentOS 7 systemd (systemctl) file to use with stunnel

Save file to:

    /lib/systemd/system/stunnel.service

Use commands like:

    sudo systemctl start stunnel.service
    sudo systemctl enable stunnel.service

Status:

    ● stunnel.service - SSL tunnel for network daemons
       Loaded: loaded (/usr/lib/systemd/system/stunnel.service; enabled; vendor preset: disabled)
       Active: active (running) since Fri 2016-06-17 11:41:31 CST; 6min ago
       CGroup: /system.slice/stunnel.service
               ├─31868 /usr/bin/stunnel /etc/stunnel/stunnel.conf
               ├─31869 /usr/bin/stunnel /etc/stunnel/stunnel.conf
               ├─31870 /usr/bin/stunnel /etc/stunnel/stunnel.conf
               ├─31871 /usr/bin/stunnel /etc/stunnel/stunnel.conf
               ├─31872 /usr/bin/stunnel /etc/stunnel/stunnel.conf
               └─31873 /usr/bin/stunnel /etc/stunnel/stunnel.conf
  
