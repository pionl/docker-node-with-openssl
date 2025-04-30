# Docker image based on official node with openssl installed

Without entrypoint - usable for gitlab CI

## Pre-installed packages:

- openssl

## Tags:
> Updated on 2025-04-30

- pionl/node-with-openssl:8
- pionl/node-with-openssl:9
- pionl/node-with-openssl:10
- pionl/node-with-openssl:18
- pionl/node-with-openssl:20
- pionl/node-with-openssl:22
- pionl/node-with-openssl:23
- pionl/node-with-openssl:24
- pionl/node-with-openssl:latest (node 24)
- pionl/node-with-openssl:8-alpine
- pionl/node-with-openssl:9-alpine
- pionl/node-with-openssl:10-alpine
- pionl/node-with-openssl:18-alpine
- pionl/node-with-openssl:20-alpine
- pionl/node-with-openssl:22-alpine
- pionl/node-with-openssl:23-alpine
- pionl/node-with-openssl:24-alpine
- pionl/node-with-openssl:alpine (node 24 alpine)

```docker
FROM pionl/node-with-openssl:8
```

## Contribution

1. Change the `Dockerfile.template`
2. Edit `build.sh` if new version is added
3. Run `build.sh` to build images
4. Run `build.sh deploy` to build and push images
