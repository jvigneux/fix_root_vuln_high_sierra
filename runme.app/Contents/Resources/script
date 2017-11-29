#!/usr/bin/env bash

sudo find /etc/passwd -type f -exec sed -i '' 's/\/root:\/bin\/sh/\/root:\/sbin\/nologin/g' {} \;
sudo dscl . -delete /Users/root

