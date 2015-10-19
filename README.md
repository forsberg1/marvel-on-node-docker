# First build the image:
docker build -t [name] .
# Docker run example:
docker run -d -p 8080:8000 [name]

# Information about git support
The docker is cashing all the stuff so if you want updated source-code you need to modify the dockerfile with a new tag for the project, this will remove the cash support for git.


