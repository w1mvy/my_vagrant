## Vagrant Example

The following things will be installed
- mysql
- nginx
- git
- zsh
- vim
- tmux
- rbenv

## HOW TO INSTALL

install [VirtualBox](https://www.virtualbox.org/)
install [vagrant](http://www.vagrantup.com/)
install rbenv & ruby

- [rbenv](https://github.com/sstephenson/rbenv)
- [ruby-build](https://github.com/sstephenson/ruby-build)

install vagrant plugin


```
$ vagrant plugin install vagrant-omnibus
$ vagrant plugin install vagrant-berkshelf
$ gem install berkshelf
```

start vagrant


```
$ vagrant up
$ vagrant provision
$ vagrant ssh
```
