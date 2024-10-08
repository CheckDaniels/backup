# backup
my setup commands

### restoring data from 1st SSD
`sudo rsync -aAXv --filter='merge /home/daniel/backup/filter.txt' --delete /run/media/daniel/Databackup/hp_linux/home/daniel/ /home/daniel/`
### restoring data from 2nd SSD
`sudo rsync -aAXv --filter='merge /home/daniel/backup/filter.txt' --delete /run/media/daniel/hp_linux/home/daniel/ /home/daniel/`
