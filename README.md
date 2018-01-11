# Docker as a Free Disk

- Brief: the utitlity to wrap Docker Hub as a free web storage to store large blob data.

--------------------------------------------------------

*Dependencies on Ubuntu*:

-	sudo apt install curl coreutils

--------------------------------------------------------

### Usage Example:

```sh
# Upload a local blob file to Docker Hub Storage:

./dockerdisk put './dockerdisk'

# Download a remote blob file from Docker Hub Storage:

./dockerdisk get '0019ad07bed81abf1f3bec2286b9478e6b95aeeb0129aea462b26332963eef56:dockerdisk'

```
