# golang_containers
Writing a container in a few lines of Go code.

You need root permissions for this version to work. Or you can adapt it to be a rootless container by as shown in these slides.

Note that the Go code uses some syscall definitions that are only available when building with GOOS=linux.
