# Local Squid Cache
A local squid cache useful for local development to cache packages such as `apt`, `yum` and `npm`.

## Requirements
- [Docker](https://docs.docker.com/get-docker)

## Export proxy
Don't forget to export your proxy. Please update the IP to point to your machine's IP address.
```
export ftp_proxy=http://192.168.254.119:3128
export http_proxy=http://192.168.254.119:3128
export https_proxy=http://192.168.254.119:3128
```
