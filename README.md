# First project

This is just test repository *Git* and **Github**

## Learn
* Create
* Commit
* Add
* Merge

## Command
```bash
git init
git status
git add
git branch
git merge
git commit -m
```

# Systemd

Differens from initv parallels launch

## Utilities
```bash
systemctl
journalctl
```

## Unit file
Systemd can use yours custom unit file as a process, for example - python script

Classes:

* .service
* .target
* .timer


[Unit]
Description=Мой кастомный Python скрипт
After=network.target

[Service]
Type=simple
ExecStart=/usr/bin/python3 /home/zxc/Desktop/my_script.py
Restart=always
User=zxc

[Install]
WantedBy=multi-user.target


