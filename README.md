# astra-Spec-ED-Smol-1.5
FSTEC (Ministry of Defense) Common Software

# Repository Astra Linux Special Edition
# July 26, 2013design
Repository Astra Linux Special Edition
Repository

Our team maintains the repository for Astra Linux Special Edition versions 1.3, 1.4 and 1.5, which are useful packages that are not included in the distribution of Linux Astra.

Repository Location: http://packages.lab50.net/ .

connection

Create a file /etc/apt/sources.list.d/lab50.list:

Astra Linux Special Edition version 1.3:
deb http://packages.lab50.net/se13/ smolensk main
deb-src http://packages.lab50.net/se13/ smolensk main
Astra Linux Special Edition version 1.4:
deb http://packages.lab50.net/se14/ smolensk main
deb-src http://packages.lab50.net/se14/ smolensk main
Astra Linux Special Edition version 1.5:
deb http://packages.lab50.net/se15/ smolensk main
deb-src http://packages.lab50.net/se15/ smolensk main
Next you need to add a digital signature key in the APT. There are two options:

Install the package lab50-archive-keyring from our repository:
aptitude -y install lab50-archive-keyring
Or add our key using the apt-key command:
wget -qO — packages.lab50.net/lab50.asc | sudo apt-key add —
What it is,

For version 1.4 contains packages OpenJDK 7 & 8 (Java 7). At the moment in the repository have the following packages (for Astra Smolensk version 1.3).

ack-grep
ansible
apt-rdepends
armadillo
boost (BOOST components not included in the official distribution: chrono, graph, locale, math, mpi, random, timer, wave)
cowbuilder / cowdancer
cython
dh-python
eatmydata
haveged
htop
geographiclib
geos
gdal
librdmacm
mercurial
mod-wsgi
netcdf
pbuilder / quemubuilder
pyflakes
python-amqplib
python-anyjson
python-crypto
python-keyring
python-ldap
python-memcache
python-netaddr
python-netifaces
python-parsec
python-pyasn1
python-pyparsing
python-requests
python-six
python-yaml
tgt
vlan
ZeroMQ
and others
