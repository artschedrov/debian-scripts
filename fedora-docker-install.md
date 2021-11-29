# Install Docker for Fedora
## Install using the repository
### Set up the repository
Install the dnf-plugins-core package (which provides the commands to manage your DNF repositories) and set up the stable repository.

`sudo dnf -y install dnf-plugins-core`

`sudo dnf config-manager \
    --add-repo \
    https://download.docker.com/linux/fedora/docker-ce.repo`
