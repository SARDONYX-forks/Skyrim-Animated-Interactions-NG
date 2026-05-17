# Animated Interactions NG

[Nexus Mods](https://www.nexusmods.com/skyrimspecialedition/mods/143798)

## Requirements

- MSVC
- xmake: >= 3.0.6

## Build

```shell
git submodule update --init --recursive --depth=1 && xmake
```

- And then install(`./build/artifact/SKSE/Data/AnimatedInteractions.dll`)

```shell
xmake install -o ./build/artifact AnimatedInteractions
```

## Language server(For `clangd`)

```shell
xmake project -k compile_commands --lsp=clangd --outputdir=build
```

## Format

- NOTE: Need LLVM(clang-format.exe path)

```shell
xmake format
```
