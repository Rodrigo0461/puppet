# puppet

# Install Puppet 3.8.7 on Debian GNU/Linux 7 (wheezy)

```
wget --no-check-certificate -c https://apt.puppetlabs.com/puppetlabs-release-wheezy.deb -O /tmp/puppet.deb`

dpkg -i /tmp/puppet.deb

apt-get update```

`apt-get install puppet ruby1.9.1 ruby1.9.1-dev rubygems1.9.1 irb1.9.1 ri1.9.1 rdoc1.9.1 build-essential libopenssl-ruby1.9.1 libssl-dev zlib1g-dev build-essential libxslt1-dev libxml2-dev zlib1g-dev`

`apt-get install puppet puppet-common puppetdb puppetdb-terminus puppetlabs-release puppetserver`

# Install r10k 

gem install r10k
