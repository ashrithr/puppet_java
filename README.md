puppet module for java
----------------------

This module will install and manage jdk

###Sample Usage

```
include java
```

Using with puppet apply (given module lives in /root/modules):

```
$puppet apply --modulepath=/root/modules/ -e "include java"
```

Note: For puppet apply, modules should be located inside modules dir with name as include name:
      Ex: `mkdir -p /root/modules && mv puppet_java /root/modules/java`
