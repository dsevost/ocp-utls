# OpenShift ansible inventory automation

## Prepare ENV variables
```
$ cp env.sh{.template,}
$ vi env.sh
$ source env.sh
```

## Generate 'hosts' file iventory 
```
$ bin/ocp-inventory-assest.sh
$ # results are in ./assets or $ASSETS_PREFIX
```
