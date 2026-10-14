# testeapp

## rea/

Cópia do repositório [morluto/rea](https://github.com/morluto/rea) (REA: Reverse Engineer Anything, licença MIT),
importada do commit `92a0edf1875f74528910db461ed03f782b7b59b3`.

As dependências de `rea/third_party/`, que no original são submódulos git, foram copiadas nas mesmas versões fixadas pelo REA:

| Pasta | Origem | Commit | Licença |
| --- | --- | --- | --- |
| `binwalk` | [ReFirmLabs/binwalk](https://github.com/ReFirmLabs/binwalk) | `4fdab3d` | MIT |
| `ghidra-nativeaot` | [Washi1337/ghidra-nativeaot](https://github.com/Washi1337/ghidra-nativeaot) | `effeb73` | MIT |
| `jadx-headless-mcp` | [1013503897/jadx-headless-mcp](https://github.com/1013503897/jadx-headless-mcp) | `5844800` | Apache-2.0 |
| `unblob` | [onekey-sec/unblob](https://github.com/onekey-sec/unblob) | `1fcc7a0` | MIT |
| `wakaru` | [pionxzh/wakaru](https://github.com/pionxzh/wakaru) | `8219bf5` | Apache-2.0 |

No `unblob`, os arquivos guardados com Git LFS no original (cerca de 2.500 arquivos de teste em `tests/` e `docs/demo.gif`, 223 MB) não foram incluídos; o código do unblob está completo.
