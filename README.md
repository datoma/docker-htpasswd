# htpasswd

## Usage

To generate a password file:

```shell
docker run --rm -ti datoma/htpasswd <username> <password> > htpasswd
```

This will use bcrypt encryption.

cloned from https://github.com/xmartlabs/docker-htpasswd
