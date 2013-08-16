puppet module for java
----------------------

This module will install and manage jdk

###Sample Usage

```puppet
include java
```

Using with puppet apply (given module lives in /root/modules):

```bash
cd ~ && mkdir modules
cd ~/modules && git clone https://github.com/ashrithr/puppet_java.git java
puppet apply --modulepath=/root/modules/ -e "include java"
```

Note: For puppet apply, modules should be located inside modules dir

**To install puppet**:

```
wget -qO - https://raw.github.com/ashrithr/scripts/master/install_puppet_standalone.sh | bash
```

(or)

```
bash <(curl -s https://raw.github.com/ashrithr/scripts/master/install_puppet_standalone.sh)
```
