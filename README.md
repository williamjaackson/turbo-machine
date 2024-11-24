# turbo-machine
⚡️ A blazingly fast, headless, cellmachine engine.

# Usage
## Flags
| Flag | Description |
| - | - |
| `-i`,`--input` | filepath of a plaintext levelstring. (default: use arg-1 as the string) |
| `-o`,`--output` | filepath of the output levelstring. (default: exports to command line) |
| `-v`,`--version` | the export version of the levelstring. (enum: v1,v2,v3) (default: v3) |
| `-t`,`--ticks` | how many ticks to simulate the level for before exporting. (default: 1) |

## Command Line Examples
```sh
# run a level for 1 tick.
turbo-machine --input ./level.txt

# convert v1 to v3.
turbo-machine --input ./level.txt --output ./level.txt --version v3
```

# Source
Built on top of [Quell Machine](https://github.com/blaumeise20/quell-machine), The 'fastest ever made remake'.
