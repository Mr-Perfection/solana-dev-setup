# solana-tutorial
https://docs.solana.com/getstarted


### Setup
```sh
# https://github.com/Mr-Perfection/MyDockerDevEnvironmentSetup
# Rust setup
sudo apt update && sudo apt install -y \
  libssl-dev libudev-dev pkg-config zlib1g-dev llvm clang make gcc
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
# refer the rest to building-solana-from-source.md

#Solana CLI: https://github.com/solana-labs/solana/releases/latest
# Build from the source since my docker env is aarch64 Linux.

# Setup a localhost blockchain cluster
# https://docs.solana.com/getstarted/local#setup-a-localhost-blockchain-cluster
solana-test-validator
solana config set --url localhost

```