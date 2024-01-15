# ndttt

n-dimensional tic-tac-toe.

I'm thinking - each side is `n+1` where `n` is the number of dims.

## deps

https://rustwasm.github.io/docs/wasm-pack/quickstart.html


[rustup](https://rustup.rs/)
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

[wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
```bash
curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
```

or, maybe not `wasm`, but a `rust` or `go` backend + [htmx](https://htmx.org/) and `javascript` for the frontend. 