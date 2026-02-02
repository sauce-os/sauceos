# Contributing to SauceOS

Thank you for your interest in contributing to SauceOS! 🍝

## Code of Conduct

Be respectful, inclusive, and professional. We're here to build great software together.

## How to Contribute

### 1. Report Bugs

Found a bug? Open an issue with:
- Clear description
- Steps to reproduce
- Expected vs actual behavior
- System info (OS, Rust version)

### 2. Suggest Features

Have an idea? Open an issue with:
- Use case description
- Proposed solution
- Why it matters

### 3. Submit Code

**Process:**
1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Make changes
4. Add tests
5. Run `cargo test`
6. Run `cargo clippy -- -D warnings`
7. Run `cargo fmt`
8. Commit (`git commit -m 'Add amazing feature'`)
9. Push (`git push origin feature/amazing-feature`)
10. Open Pull Request

**Requirements:**
- ✅ All tests pass
- ✅ No clippy warnings
- ✅ Formatted with rustfmt
- ✅ Documented (doc comments)
- ✅ Meaningful commit messages

### 4. Write Documentation

Documentation improvements are always welcome:
- Fix typos
- Add examples
- Clarify explanations
- Write tutorials

## Development Setup

```bash
# Clone repository
git clone https://github.com/sauce-os/sauceos.git
cd sauceos

# Build
cargo build

# Run tests
cargo test

# Check formatting
cargo fmt -- --check

# Lint
cargo clippy -- -D warnings
```

## Project Structure

```
sauceos/
├── sauce-kernel/     # Kernel implementation
├── sauce-compiler/   # The Sauce Maker compiler
├── sauce-cli/        # Command-line interface
├── components/       # Component catalog
└── docs/            # Documentation
```

## Good First Issues

Look for issues labeled `good first issue` — these are great for newcomers!

## Questions?

- Open a GitHub Discussion
- Join our Discord (coming soon)
- Email: hello@sauce-os.org

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
