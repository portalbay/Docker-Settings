# Docker-Settings

```
cat /etc/docker/daemon.json
{
"data-root": "/path/to/docker-data",
  "default-address-pools":[
    {"base":"172.19.0.0/16","size":24}, {"base":"172.21.0.0/16","size":24}
  ]
}
```
