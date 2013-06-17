puppet module for java
----------------------

This module will install and manage jdk

###Sample Usage

```
include java
```

Using with puppet apply (given module lives in /root/modules):

```
$puppet apply --modulepath=/root/modules -e "include java"
```