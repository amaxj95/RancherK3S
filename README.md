# Rancher


[K3S install](https://github.com/k3s-io/k3s)

## Create Service 
[Unit]
Description=My test service
After=multi-user.target
[Service]
Type=simple
Restart=always
ExecStart=/usr/bin/python3 /home/<username>/test.py
[Install]
WantedBy=multi-user.target