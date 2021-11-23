# Docker Registry Static as standalone example

The interface will be accessible with <http://localhost>.
Your docker registry will be accessible with <https://localhost>.

registry will be configured with port 443
registry is mapped as volume from local /var/lib/registry
certs also are mapped as volume from local /etc/certs

The simplest way is with `simple.yml` docker-compose file.

```sh
docker-compose -f simple.yml up -d
```
