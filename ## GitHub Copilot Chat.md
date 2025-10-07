## GitHub Copilot Chat

- Extension Version: 0.31.5 (prod)
- VS Code: vscode/1.104.3
- OS: Linux
- Remote Name: codespaces

## Network

User Settings:
```json
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 140.82.114.5 (1 ms)
- DNS ipv6 Lookup: Error (17 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (41 ms)
- Electron fetch: Unavailable
- Node.js https: HTTP 200 (237 ms)
- Node.js fetch (configured): HTTP 200 (118 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.112.21 (11 ms)
- DNS ipv6 Lookup: Error (2 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (43 ms)
- Electron fetch: Unavailable
- Node.js https: HTTP 200 (232 ms)
- Node.js fetch (configured): HTTP 200 (280 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).