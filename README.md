# PhioTX-M -- PhioTX Manager

PhioTX-M is a web based management interface for PhioTX.

## Usage

Here is an example to get you started running this container on a local
workstation.

### docker-cli

```
docker pull ghcr.io/quantumxc/phiotx-m:latest
docker run --rm --init \
    -p 127.0.0.1:8080:8080/tcp \
    -e PORT=8080 \
    -e ROOT_URL=http://127.0.0.1:8080 \
    ghcr.io/quantumxc/phiotx-m:latest
```

## Parameters

|   Parameter   |  Description                                  |
| ------------- | --------------------------------------------- |
| -p 8080       | Publish HTTP port to the host.                |
| -e PORT=      | Set HTTP listening port.                      |
| -e ROOT_URL=  | Set base URL used to access the application.  |
