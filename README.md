# Mark Sierra's Umbrel Community App Store

Apps for [umbrelOS](https://umbrel.com) that are not (yet) in the official Umbrel App Store.

## Add this store to your Umbrel

1. Open the **App Store** on your Umbrel.
2. Click **⋯** (top right) → **Community App Stores**.
3. Paste `https://github.com/MarkSierra/umbrel-community-app-store` and click **Add**.
4. Open **Mark Sierra's App Store** and install an app.

Updates appear in Umbrel like those of any other app.

## Apps

| App | What it does | Requires |
|---|---|---|
| [Monetary View](marksierra-bitcoinmonetaryview) | Read-only analysis of how much spam your Bitcoin node stores (per block, whole chain, UTXO set) and how much storage a Monetary Node would save. Source: [BitcoinMonetaryView](https://github.com/MarkSierra/BitcoinMonetaryView). | Bitcoin Node or Bitcoin Knots |

## For maintainers

Each app is one folder named after its app ID (`marksierra-<app>`) with an `umbrel-app.yml` and a
`docker-compose.yml`. Images are multi-arch (x86_64 and ARM64) and pinned by version tag and digest. Update
steps for Monetary View: [docs/umbrel.md](https://github.com/MarkSierra/BitcoinMonetaryView/blob/main/docs/umbrel.md).

The packaging files in this repository are licensed under AGPL-3.0, like the apps themselves.
