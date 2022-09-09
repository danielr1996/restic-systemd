# restic-systemd
systemd files to schedule a restic backup

## usage
```
sudo ./copy.sh
cp backup.env.sample /etc/restic/backup.env
sudo systemctl start restic-backup@backup
```
