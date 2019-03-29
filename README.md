# buildah-sandbox
Repo containing experiments with buildah

# Setup
Images were developed and built using an Ubuntu EC2 instance in AWS.

* Install [buildah](https://github.com/containers/buildah/blob/master/install.md) then
install [docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/).
* Ensure that the registries file (`/etc/containers/registries.conf`) contains the correct entries
for the repositories to search ([reference](https://github.com/containers/buildah/blob/master/install.md))
