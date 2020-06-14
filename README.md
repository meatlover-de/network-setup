# network-setup
Bolt repository for the servers in my network

# Prepwork

On Debian Testing "bullseye" bolt cant install puppet-agent yet, so you have to download

wget http://apt.puppet.com/puppet-release-stretch.deb
dpkg -i puppet-release-stretch.deb
aptitude update
aptitude install puppet-agent

