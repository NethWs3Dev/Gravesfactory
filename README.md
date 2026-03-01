## Command for GSI

```
fastboot erase product && fastboot erase system && fastboot erase system_ext && fastboot delete-logical-partition product_a && fastboot delete-logical-partition product_b && fastboot delete-logical-partition product_a-cow && fastboot delete-logical-partition product_b-cow && fastboot delete-logical-partition system_ext_a && fastboot delete-logical-partition system_ext_b && fastboot delete-logical-partition system_ext_a-cow && fastboot delete-logical-partition system_ext_b-cow
```

## then

```
fastboot flash system [your gsi.img]
```
