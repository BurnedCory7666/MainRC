# MainRC

## Usage:
1. Do cloning.
2. Add at the end of `.zshrc` or `.bashrc` following:
  ```bash
MAINRC_PATH=~/.userrc/
source "${MAINRC_PATH}/mainrc"
  ```
3. ```source ~/.zshrc``` or ```source ~/.bashrc``` or restart session.



## Config

| Name | Type/Values | Description |
|------|-------------|-------------|
| `MAINRC_CC_COMPILER` | `clang`/`gcc` | Configure variables to use specified compiler. |
| `MAINRC_RUN_PROGS_AS_ROOT` | `on`/`off` | If `on`, add or replace aliases to run some programs as root. |
| `MAINRC_SHUTDOWN_GUARD` | `on`/`off` | If `on`, disable `c-poweroff` alias for SSH connections. |
