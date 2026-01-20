# Contributing to OxideKit

Thank you for your interest in contributing to OxideKit!

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/oxidekit-core.git`
3. Create a branch: `git checkout -b feature/my-feature`
4. Make your changes
5. Run tests: `cargo test --workspace`
6. Commit your changes: `git commit -m "Add my feature"`
7. Push to your fork: `git push origin feature/my-feature`
8. Open a Pull Request

## Development Setup

```bash
# Install Rust (if not already installed)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# Clone the repository
git clone https://github.com/oxidekit/oxidekit-core.git
cd oxidekit-core

# Build
cargo build --workspace

# Run tests
cargo test --workspace

# Run a demo app
cd examples/hello-world
cargo run
```

## Code Style

- Follow Rust's standard formatting (`cargo fmt`)
- Run `cargo clippy` and address warnings
- Write tests for new functionality
- Keep commits focused and atomic
- Write clear commit messages

## Pull Request Guidelines

- Keep PRs focused on a single change
- Update documentation if needed
- Add tests for new features
- Ensure all tests pass
- Link related issues in the PR description

## Questions?

Feel free to open a [Discussion](https://github.com/oxidekit/oxidekit-core/discussions) for questions or ideas.
