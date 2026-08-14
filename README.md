# nodejs-sb

A Node.js service for managing proxy node subscriptions.

## Features

- Node subscription management
- Auto deployment of proxy services
- Environment variable based configuration
- Argo tunnel support
- Telegram node push notifications

## Requirements

- Node.js >= 14
- npm

## Quick Start

```bash
npm install
npm start
```

## Environment Variables

| Variable | Description |
|----------|-------------|
| `PORT` | Server port (default: 3000) |
| `UUID` | Client UUID |
| `ARGO_DOMAIN` | Argo tunnel domain |
| `ARGO_AUTH` | Argo tunnel auth token |
| `NEZHA_SERVER` | Nezha monitor server |

## License

MIT

## Contributing

Pull requests are welcome.
