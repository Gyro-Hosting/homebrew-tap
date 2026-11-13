# Gyro Hosting Homebrew tap

```sh
brew install gyro-hosting/tap/gyro
gyro --version
```

Works on macOS (Apple Silicon and Intel) and Linux (x86_64, arm64).

`Formula/gyro.rb` is regenerated automatically (hourly) from the latest
[gyro-cli release](https://github.com/Gyro-Hosting/gyro-cli/releases). Checksums are taken
only from the release `SHA256SUMS` file after its GPG signature is verified with the
Gyro Hosting release key (`E96B E963 5E77 A0D9 119A C8C3 A798 6589 A154 B990`).

Upgrade: `brew update && brew upgrade gyro`

Documentation: https://www.gyrohosting.com/developers/
