# Linux
Script, commands and tools
Syntax to mount DVD / CDROM in Linux
# mkdir -p /mnt/cdrom
mount -t iso9660 -o ro /dev/deviceName /path/to/mount/point
# mount -t iso9660 -o ro /dev/cdrom /mnt/cdrom or mount -t iso9660 -o ro /dev/sr0 /mnt/cdrom
