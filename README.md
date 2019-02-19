# Run Hugo in Docker with SSL

This repostiory allows you run anything hugo within docker, while having automatic SSL certificate renewal. It is very easy to use, and I will provide git hooks for pushing changes automatically on `git commit`. 

## Docker Compose

`git clone` this repostiory, and run `docker-compose up -d` within the directory. In order for SSL Encryption to work, you will need to have a valid domain. You can get one from any DNS registrar of your choice.

## Update Image on Hugo Update

```./update.sh 0.25```
