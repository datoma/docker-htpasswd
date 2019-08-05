# htpasswd

## Usage

To generate a password file:

```shell
docker run --rm -ti xmartlabs/htpasswd <username> <password> > htpasswd
```

This will use bcrypt encryption.

clones from https://github.com/xmartlabs/docker-htpasswd
