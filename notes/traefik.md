# Traefik

Create password hash:

```sh
echo $(htpasswd -nbB USER "PASS") | sed -e s/\\$/\\$\\$/g
```

