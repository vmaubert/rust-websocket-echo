# websocket

Simple echo websocket server.

## Usage

### server

```bash
cd examples/websocket
cargo run 
# Started http server: 127.0.0.1:8081
```

### test

```bash
wscat -c ws://localhost:8081/ws/
```

### new image

```bash
docker build -t registry.gitlab.com/code-troopers/chapito/chapito-monitor:echo .
docker push registry.gitlab.com/code-troopers/chapito/chapito-monitor:echo
```