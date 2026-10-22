# obsidian-open

Turns an https link into an `obsidian://` link, so notes open in Obsidian from apps that only allow https links.

`https://vincegarcia25.github.io/obsidian-open/#file=Notes%2FLife%2FLife`

- `file`: vault-relative path without `.md`, URL-encoded.
- `vault`: optional, defaults to `Obsidian`.

The path sits after `#`, which browsers never send to a server.
