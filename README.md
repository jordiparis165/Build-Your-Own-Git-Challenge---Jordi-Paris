# README (Linux)
Les scripts de test sont dans `Test/`.
Prerequis: `bash`, `git`, `cargo`, `hexdump`, `pkg-config`, `libssl-dev`

Si besoin (Ubuntu/Debian):
```sh
sudo apt update && sudo apt install -y git util-linux pkg-config libssl-dev
```

Compiler + lancer tous les tests:
```sh
cd /path/to/codecrafters-git-rust
for t in Test/*.sh; do echo "### $t"; bash "$t"; done
```
