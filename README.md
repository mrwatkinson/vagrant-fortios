# vagrant-vyos

[//]: # ([![Code Climate](https://codeclimate.com/github/higebu/vagrant-vyos/badges/gpa.svg)](https://codeclimate.com/github/higebu/vagrant-vyos))
[//]: # ([![Gem Version](https://badge.fury.io/rb/vagrant-vyos.svg)](https://badge.fury.io/rb/vagrant-vyos))
[//]: # ([![Downloads](http://ruby-gem-downloads-badge.herokuapp.com/vagrant-vyos?type=total&style=flat)](https://rubygems.org/gems/vagrant-vyos))

Vagrant-vyos is a [Vagrant](http://www.vagrantup.com) plugin that adds [FortiOS](https://www.fortinet.com/products/fortigate/fortios.html) support to Vagrant with the goal to be able to deploy basic network connectivity and safely start/stop FortiGate VMs 

It is a fork of [higebu's VyOS plugin](https://github.com/higebu/vagrant-vyos)

Currently this code is not  ready for release. 
This plugin aims to fix the following features.

* `vagrant halt`.
* `config.vm.hostname`.
* `config.vm.network`.
* `config.ssh.insert_key`.

## Installation

```
$ vagrant plugin install vagrant-fortios
```

## Usage
A custom FortiGate box was used to build the image. The process followed was that documented by [Marc Weisel on his binarynature blogspot](https://binarynature.blogspot.com/2018/12/fortigate-vagrant-box-for-vmware-fusion.html)


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
