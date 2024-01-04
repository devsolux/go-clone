# Go-Clone

### Instructions

```bash
wget https://github.com/devsolux/go-clone/releases/download/v1.0.0/go-clone_mac_arm64
sudo mv go-clone_mac_arm64 /usr/local/bin/go-clone
chmod +x /usr/local/bin/go-clone
```

## Usage

```
Usage:
  go-clone <url> [flags]

Flags:
  -C, --cookie strings        Pre-set these cookies
  -h, --help                  help for go-clone
  -o, --open                  Automatically open project in default browser
  -p, --proxy_string string   Proxy connection string. Support http and socks5 https://pkg.go.dev/github.com/gocolly/colly#Collector.SetProxy
  -s, --serve                 Serve the generated files using Echo.
  -P, --servePort int         Serve port number. (default 5000)
  -u, --user_agent string     Custom User Agent
```