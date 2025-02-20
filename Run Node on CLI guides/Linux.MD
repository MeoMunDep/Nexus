Open Terminal and run these command:
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
rustup target add riscv32i-unknown-none-elf

sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
```