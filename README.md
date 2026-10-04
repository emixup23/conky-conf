# conky-conf
A simple conky config file

A single-file Conky system monitor: CPU, RAM, swap, disk, network,
top CPU/MEM processes, battery. Auto-detects the default-route
interface so it works on Wi-Fi *and* Ethernet.

<img width="336" height="998" alt="Screenshot_20261004_082244-1" src="https://github.com/user-attachments/assets/2d7fae55-c483-4750-8c05-e0ae38f2150a" />
<img width="336" height="998" alt="Screenshot_20261004_082159-1" src="https://github.com/user-attachments/assets/b6307276-d69b-4482-a671-f6b5cec921c1" />
<img width="336" height="998" alt="Screenshot_20261004_082133-1" src="https://github.com/user-attachments/assets/ae3973bd-df36-4d5d-a141-c4c3b4d7e56f" />


## Requirements
- conky (with Lua support), `iproute2`

## Install
    mkdir -p ~/.config/conky
    cp conky.conf ~/.config/conky/conky.conf
    conky -c ~/.config/conky/conky.conf

## Autostart (optional)
Add to your DE's autostart, or drop a `conky.desktop` in
`~/.config/autostart/` pointing at the command above.
EOF

git add README.md
git commit -m "Add README"
git push
