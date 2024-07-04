# ngrokConf
contents of file: `ngrok.yml`
```
version: 2
authtoken: auth token here
tunnels:
  ssh:
    proto: tcp
    addr: 127.0.0.1:22
  minecraft:
    proto: tcp
    addr: 127.0.0.1:25565

```

# commands
```
ngrok start --all
```
