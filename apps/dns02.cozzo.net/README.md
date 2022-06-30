As of now, need to disable dns on the host container, and set custom resolv.conf file.

sudo systemctl disable systemd-resolved.service

sudo systemctl stop systemd-resolved

write to: /etc/systemd/resolved.conf

symlink /etc/systemd/resolved.conf > /etc/resolv.conf
