# CircleCI SSH

https://discuss.circleci.com/t/ssh-connection-from-circleci-build-server-to-remote-server-not-being-allowed/22964

## credentials and keys

Where to store secret data?

# Docker

1. [X] create a user on the Linux VPS
2. [X] assign SSH key authentication
3. [X] assign permission to run Docker commands
4. [ ] print out the running container in CircleCI (stop here for the first try)
5. [ ] run Docker Pull from the VPS to get the image
6. [ ] start a new instance  (skip for the first try)
7. [ ] Switch the DNS (skip for the first try)
8. [ ] run the new image


https://github.com/halfer/cd-demo-container/blob/master/.circleci/config.yml