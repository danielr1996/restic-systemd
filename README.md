# restic-systemd
systemd files to schedule a restic backup

## usage
```
sudo ./copy.sh
sudo systemctl daemon-reload
sudo systemctl start restic-backup@$(systemd-escape --path /home/ubuntu/restic-systemd/env)
```
