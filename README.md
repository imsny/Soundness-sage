soundness-cli send --proof-file="gpJy7r_1GdddG4B-AxtjQvR7xOnH00zTdMQ8Yto076s" --game="8queens" --key-name="" --proving-system="ligetron" --payload='{"program": "/root/ligero_internal/sdk/build/examples/8queen.wasm", "shader-path": "/root/ligero_internal/shader", "packing": 8192, "private-indices": [1, 2], "args": [{"str": "1111111111111111"}, {"str": "11111111111111111111111111111111"}, {"str": ""}, {"str": "bc44bd7d70e83c760cd2445e20797b1adae376758f2d872f45764db569386a7d"}]}'# COMMANDS:

```bash
sudo apt update && sudo apt upgrade -y
```

```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```
```bash
source ~/.bashrc
```
```bash
soundnessup install
```
```bash
soundnessup update
```
```bash
soundness-cli generate-key --name my-key
```
```bash
soundness-cli export-key --name my-key
```
