jellyfin:
	sudo cp -d /etc/containers/systemd jellyfin/*
	sudo /usr/lib/systemd/system-generators/podman-system-generator
	sudo systemctl daemon-reload
	sudo systemctl start jellyfin
