puppet module for java
----------------------

This module will install and manage jdk

###Sample Usage

```
include java
```

Using with puppet apply (given module lives in /root/modules):

```
$cd ~ && mkdir modules
$cd ~/modules && git clone https://github.com/ashrithr/puppet_java.git java
$puppet apply --modulepath=/root/modules/ -e "include java"
```

Note: For puppet apply, modules should be located inside modules dir with name as include name:
      Ex: `mkdir -p /root/modules && mv puppet_java /root/modules/java`

To install puppet:

```
wget -qO - https://raw.github.com/ashrithr/scripts/master/install_puppet_standalone.sh | bash -i
```
