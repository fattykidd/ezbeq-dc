# ezbeq-docker-container

Creates and publishes an image for [ezbeq](https://github.com/3ll3d00d/ezbeq) to github packages

* Exposes port 8080 
* Expects a volume mapped to /config to allow user supplied ezbeq.yml
* This image does NOT include minidsp-rs
* I've linked my compose.yml and ezbeq.yml for anyone to read and see how to add different devices to be used. I struggled with this, hopefully it'll save someone a headache.
