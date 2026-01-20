# OxideKit

**Build native desktop applications with Rust. No browser, no JavaScript, no bundlers.**

OxideKit is a Rust-native application platform that replaces Electron, Tauri, and traditional web stacks. GPU-accelerated rendering, state-preserving hot reload, and a permission system that enterprises can actually verify.

## Repositories

| Repository | Description |
|------------|-------------|
| [oxidekit-core](https://github.com/oxidekit/oxidekit-core) | Runtime, compiler, and CLI |
| [oxidekit-extensions](https://github.com/oxidekit/oxidekit-extensions) | Official plugins |
| [oxidekit-themes](https://github.com/oxidekit/oxidekit-themes) | Theme collection |
| [oxidekit-docs](https://github.com/oxidekit/oxidekit-docs) | Documentation site |
| [oxidekit-site](https://github.com/oxidekit/oxidekit-site) | oxidekit.com |
| [vscode-oxidekit](https://github.com/oxidekit/vscode-oxidekit) | VS Code extension |

## Quick Start

```bash
# Install
cargo install oxide-cli

# Create a new app
oxide new my-app --starter admin-panel

# Run with hot reload
oxide dev

# Build for production
oxide build --release
```

## Links

- [Documentation](https://docs.oxidekit.com)
- [Website](https://oxidekit.com)
