# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:free5gc-amf_1.1.1_amd64.rock docker-daemon:free5gc-amf:1.1.1
docker run free5gc-amf:1.1.1
```
