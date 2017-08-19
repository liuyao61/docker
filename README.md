# Docker Notes

This is a dumping place for all my docker related notes.

# How to move docker images to another host?

docker commit [container id]
docker save [image] > image.tar
scp image.tar user@otherhost:/path/to/image
/path/to/image/docker load image.tar
