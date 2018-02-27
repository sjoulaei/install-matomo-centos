# install-matomo-centos
A script that will install latest Matomo with all pre-requisite packages.

It installs:
- httpd24-httpd (from scl package)
- php71-php (from scl package)
- MariaDB

and all required extra packages.

It also puts SELinux in permissive mode.

Creates the user and database required for the installation.

Configures the apache server for ssl support.

Note: You need to have your certificate and private key files to be copied on your system.



