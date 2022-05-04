# rust-discord-homebrew

Learning Rust by... making a Discord "client" on an Old 3DS XL...

This repo contains two sub-repos:

1. discord-homebrew-app
2. discord-homebrew-proxy

`discord-homebrew-app` contains the "app" that the 3DS runs. It connects to the proxy through a TCP stream to communicate indirectly with Discord.
`discord-homebrew-proxy` contains a proxy that needs to be run on a separate computer. It uses a bot and a webhook to act as a bridge.

Each sub-repo will have more information about it.
