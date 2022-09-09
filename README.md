# restic-systemd
systemd files to schedule a restic backup

## usage
```
sudo ./copy.sh
sudo systemctl daemon-reload
cp backup.env.sample /etc/restic/backup.env
sudo systemctl start restic-backup@backup
```
