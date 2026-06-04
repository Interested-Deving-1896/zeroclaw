[update-readmes]   Mode: rewrite — migrating to template structure...
# zeroclaw

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/zeroclaw)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/zeroclaw.git
cd zeroclaw
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration


Minimal `~/.zeroclaw/config.toml`:

```toml
default_provider = "anthropic"
api_key = "sk-ant-..."
```

Full configuration reference: [docs/reference/api/config-reference.md](docs/reference/api/config-reference.md).

### Channel configuration

**Telegram:**
```toml
[channels.telegram]
bot_token = "123456:ABC-DEF..."
```

**Discord:**
```toml
[channels.discord]
token = "your-bot-token"
```

**Slack:**
```toml
[channels.slack]
bot_token = "xoxb-..."
app_token = "xapp-..."
```

**WhatsApp:**
```toml
[channels.whatsapp]
enabled = true
```

**Matrix:**
```toml
[channels.matrix]
homeserver_url = "https://matrix.org"
username = "@bot:matrix.org"
password = "..."
```

**Signal:**
```toml
[channels.signal]
phone_number = "+1234567890"
```

### Tunnel configuration

```toml
[tunnel]
kind = "cloudflare"  # or "tailscale", "ngrok", "openvpn", "custom", "none"
```

Details: [Channel reference](docs/reference/api/channels-reference.md) · [Config reference](docs/reference/api/config-reference.md)

### Runtime support (current)

- **`native`** (default) — direct process execution, fastest path, ideal for trusted environments.
- **`docker`** — full container isolation, enforced security policies, requires Docker.

Set `runtime.kind = "docker"` for strict sandboxing or network isolation.

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/zeroclaw`](https://github.com/Interested-Deving-1896/zeroclaw) and mirrored through:

```
Interested-Deving-1896/zeroclaw  ──►  OpenOS-Project-OSP/zeroclaw  ──►  OpenOS-Project-Ecosystem-OOC/zeroclaw
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[Apache-2.0](https://github.com/Interested-Deving-1896/zeroclaw/blob/master/LICENSE-APACHE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
