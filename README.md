# WAW Fake Backend

This repository hosts the source files for our mock API we'll use for the initial development of our frontend applications:

- [Vue.js](https://github.com/futureleadersupc/waw-frontend-vue)
- [Angular](https://github.com/futureleadersupc/waw-frontend-angular)

All of this is powered by [My JSON Server](https://my-json-server.typicode.com/), a free service by Typicode (also the creators of `json-server`) to provide mock APIs backed by Git repositories. This repository is available in [this endpoint](https://my-json-server.typicode.com/futureleadersupc/waw-backend-json).

This will be eventually replaced with proper backend applications, written in [C#](https://github.com/futureleadersupc/waw-backend-cs) and [Java](https://github.com/futureleadersupc/waw-backend-java) respectively.

This repository is automatically synced with our frontend application repositories, which also host a copy of our mock API source in the `server/` folder for local development with [`json-server`](https://www.npmjs.com/package/json-server). See the [workflow files](.github/workflows/sync.yml) for more information on this (also synced across repositories).

The synchronization is powered by this [GitHub Action](https://github.com/BetaHuhn/repo-file-sync-action), which automatically creates pull requests on each repository with the changes available. All the commits and pull requests are done and managed by the bot account @dalbitresb12-bot, which manages multiple repositories for @dalbitresb12.

## License

[MIT](LICENSE)
