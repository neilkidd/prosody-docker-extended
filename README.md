![License MIT](https://img.shields.io/badge/license-MIT-blue.svg)

# prosody-goos
Docker image specifically configured to work for local development on GOOS.  
The accounts are hard coded in entrypoint.sh !

See the original repo for further info : https://github.com/unclev/prosody-docker-extended

## Running

```
docker build --rm -t ourxmpp .
docker run -p 5222:5222 ourxmpp
```
