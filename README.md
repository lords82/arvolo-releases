# Arvolo — releases

Prebuilt releases of **Arvolo**: end-to-end encrypted file transfer between
your devices and your contacts, through a relay that sees nothing.

Download from the [latest release](https://github.com/lords82/arvolo-releases/releases/latest):

| Platform | Download |
|---|---|
| **macOS** | the `.dmg` (one universal app, signed and notarized) |
| **Windows** | the `.msi` |
| **Linux** | the `.AppImage` for the desktop app; `.deb` / `.rpm` for the command line |

Command line only (Linux and macOS):

```sh
curl -fsSL https://github.com/lords82/arvolo-releases/releases/latest/download/install.sh | sh
```

Relay (self-hosted):

```sh
docker run -d --name arvolo-relay -p 6282:6282 -v arvolo-data:/data \
  ghcr.io/lords82/arvolo-relay:latest
```

Security reports: **info@termox.it**, or GitHub's private vulnerability
reporting on this repository.
