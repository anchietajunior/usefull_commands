# Usefull Commands

Usefull commands is a simple repository to keep some quick configurations and tips.

  - Mount USB device with Windows on Mac
  

# Mount USB device with Windows on Mac

Discover and unmount the storage device.

```sh
$ disktutil list
$ disktutil unmountDisk /dev/your-disk-number
```

Extract ISO content to the selected device.

```sh
$ sudo dd if=/path-to-the-iso of=/dev/your-disk-number bs=1m
```

Wait some simutes until this ends, and eject the device.

```sh
$ diskutil eject /dev/your-disk-number
```