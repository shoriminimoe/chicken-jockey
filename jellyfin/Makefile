install:
	sudo cp -t /etc/containers/systemd jellyfin.*
	sudo /usr/lib/systemd/system-generators/podman-system-generator
	sudo systemctl daemon-reload

start:
	sudo systemctl start jellyfin

stop:
	sudo systemctl stop jellyfin

restart:
	sudo systemctl restart jellyfin
