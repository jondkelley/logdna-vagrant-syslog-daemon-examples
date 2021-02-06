# logdna-vagrant-syslog-daemon-examples

In this repository you can find common examples for configuring your servers for various syslog daemons/agents in LogDNA.

You will need

* [vagrant](https://www.vagrantup.com/docs/installation) installed
* Oracle Virtualbox

On Mac OS with homebrew, you'd run something like:

```
brew cask install virtualbox
brew cask install vagrant
```

## Repository Layout

To use this repo, CD into one of the directories below and simply run `vagrant up` for your Linux distribution of choice. LogDNA configurations might vary slightlyu because the root package maintainers (sometimes) use slightly different base configs.

```
./rsyslog-ng-examples/rsyslog-ng-ubuntu-20.04-vagrantbox    - Debian/Ubuntu      syslog-ng example
./rsyslog-ng-examples/rsyslog-ng-centos8-stream-vagrantbox  - Redhat/CentOS/RHEL syslog-ng example (based on Centos 7.1 box)
./rsyslog-examples/rsyslog-ubuntu-20.04-vagrantbox          - Debian/Ubuntu      rsyslog example
./rsyslog-examples/rsyslog-centos8-stream-vagrantbox        - Redhat/CentOS/RHEL rsyslog example (based on Centos 7.1 box)
```
