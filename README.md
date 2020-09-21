# Get info
`sudo modinfo ./hello-1.ko`

# Load/Unload kernel
```
sudo insmod hello-5.ko
sudo rmmod hello-5.ko
```

# Kernel ring buffer
`dmesg | tail -1`
