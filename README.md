# rls project

```
git remote add github https://github.com/oli-obk/rls.git
git fetch github
git checkout github/praktikum
cargo build
```

# rls.sh

```sh
LD_LIBRARY_PATH=$HOME/.rustup/toolchains/nightly-x86_64-unknown-linux-gnu/lib path/to/rls/target/debug/rls
```

# settings.json (vscode settings)

```json
    "rust.rls": {
        "executable": "sh",
        "args": ["rls.sh"]
    },
```

# rls.toml

```toml
sysroot = "/home/oliver/.xargo"
cfg_test = false
```
