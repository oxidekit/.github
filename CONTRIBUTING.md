# Contributing to OxidePM

Thank you for your interest in contributing to OxidePM!

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/oxidepm.git`
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
git clone https://github.com/oxidekit/oxidepm.git
cd oxidepm

# Build
cargo build --workspace

# Run tests
cargo test --workspace

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

Feel free to open an [issue](https://github.com/oxidekit/oxidepm/issues) for questions or ideas.
