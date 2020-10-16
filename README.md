dir: /lib/systemd/system-sleep/{name}
exe: chmod +x /lib/systemd/system-sleep/{name}
src: https://askubuntu.com/questions/1029250/ubuntu-18-04-ethernet-disconnected-after-suspend
verify: grep {name} /var/log/syslog
