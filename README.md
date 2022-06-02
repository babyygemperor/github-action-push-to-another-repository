# GitHub Action to push to another remote

Basic GitHub action to automatically push the current repository to another GitHub or TUM bitbucket repository.

**Note:** You need an ssh key pair for this in your secrets with the names `PUBLIC_KEY` and `PRIVATE_KEY` with their designated contents.
Don't forget to change the env variable `UPSTREAM` as your 2nd repository.
