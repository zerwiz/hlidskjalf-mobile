# Hlidskjalf — the sovereign's view in the hand

The mobile seat of Ymir: Odin's high seat carried in the hand. An Expo
(React Native) app that reads the same gate API the web control plane
serves (`apps/hlidskjalf/server`), so the fleet is visible from anywhere.

Part of the [Ymir](https://github.com/zerwiz/ymir) project.

## What it is

- **The fleet on the palm** — agents, tasks, and their states against the
  same control-plane the desktop hall shows.
- **One handshake** — set the API base with `EXPO_PUBLIC_API_URL`
  (default `http://127.0.0.1:3889`), or point it at Bifrost in production.

## Run

```bash
npm install
npx expo start --android    # or: npx expo start --ios
```

## Licence

Apache License, Version 2.0 — see `LICENSE` and `NOTICE`.