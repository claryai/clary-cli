# Clary CLI

The official command-line interface for Clary.

## Installation

### Quick Install (Recommended)

#### macOS/Linux
```bash
# Install latest stable version
curl -fsSL https://platform.getclary.com/cli | bash

# Install specific version
curl -fsSL https://platform.getclary.com/cli | bash -s -- --version v4.1.0

# Install latest beta version
curl -fsSL https://platform.getclary.com/cli | bash -s -- --beta

# Install specific beta version
curl -fsSL https://platform.getclary.com/cli | bash -s -- --version v4.1.0-beta
```

#### Windows (PowerShell)
```powershell
# Install latest stable version
irm https://platform.getclary.com/cli-windows | iex

# Install specific version
irm https://platform.getclary.com/cli-windows | iex -- --version v4.1.0

# Install latest beta version
irm https://platform.getclary.com/cli-windows | iex -- --beta

# Install specific beta version
irm https://platform.getclary.com/cli-windows | iex -- --version v4.1.0-beta
```
### Manual Installation

Download the latest release for your platform from the [releases page](https://github.com/claryai/clary-cli/releases).

**Note**: Beta releases are marked as prereleases on GitHub. To install a beta version, use the `--version` flag with the beta tag.

## Usage

```bash
clary --help
```

## Documentation

For full documentation, visit [docs.getclary.com](https://docs.getclary.com).

## License

Copyright © 2025 Clary Technologies, Inc. All rights reserved.

This software is proprietary and confidential. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited.

See [LICENSE](LICENSE) for full terms.