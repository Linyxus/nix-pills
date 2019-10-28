# Nix Pills (epub version)

This reposity can build the epub version of [Nix Pills](https://nixos.org/nixos/nix-pills/), based on the instructions in this [issue](https://github.com/NixOS/nix-pills/issues/31).

## Build

```shell
nix-build release.nix
cd result/share/doc/nix-pills
zip -r -X ~/nix-pills.epub mimetype META-INF OEBPS
```