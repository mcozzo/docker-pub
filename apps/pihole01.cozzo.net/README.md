As of now, need to disable dns on the host container, and set custom resolv.conf file.

sudo systemctl disable systemd-resolved.service

sudo systemctl stop systemd-resolved

resolv.conf -> ../run/systemd/resolve/stub-resolv.conf

