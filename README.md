# dummy-monorepo

EV218 用です。`apps/web` がフロント、`apps/api` が API です。

- リポジトリ直下の `index.html` は `REPO-ROOT` です。これが配信されたら、直下をルートにしてしまっています。
- `apps/web` は `WEB-ROOT-OK` を返します。
- `apps/api` の `GET /` は `API-ROOT-OK` を返します。
