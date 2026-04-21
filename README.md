# XPro Free Edition

XML processing toolchain from [BlueFunda](https://bluefunda.com) — CLI, batch processor, file-watcher, and test-data generator, packaged for Linux.

## Components

| Binary | Description |
|--------|-------------|
| `xpro` | Unified CLI for all operations |
| `processor` | XML batch processing engine |
| `file-watcher` | File monitoring daemon |
| `xmlgen` | XML test file generator |

An optional `xpro-free-temporal` package adds Temporal workflow orchestration.

## Installation

Download the latest package from the [releases page](https://github.com/bluefunda/xpro-free/releases/latest).

### RPM (RHEL / CentOS / Rocky 8+)

```bash
sudo dnf install ./xpro-free-*-1.x86_64.rpm
```

### DEB (Ubuntu 18.04+ / Debian 10+)

```bash
sudo dpkg -i ./xpro-free-*-1.amd64.deb
sudo apt-get install -f
```

### Verify checksums

```bash
sha256sum -c checksums.txt
```

## Getting Started

Once installed, the `xpro` CLI is available on your `$PATH`:

```bash
xpro --help
xpro --version
```

See `xpro <command> --help` for each subcommand.

## Releases

See [all releases](https://github.com/bluefunda/xpro-free/releases) for version history and changelogs. XPro follows a **Fall/Spring** seasonal release cadence.

## Support

- **Website** — [bluefunda.com](https://bluefunda.com)
- **Issues** — [file a bug](https://github.com/bluefunda/xpro-free/issues)

## License

See [LICENSE](./LICENSE).
