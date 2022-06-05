# MainRC
## Usage:
1. ```git clone https://github.com/BurnedCory7666/MainRC.git```
2. Add at the end of `.bashrc` or `.zshrc` following:
  ```bash
MAINRC_PATH=~/.userrc/;
CC_COMPILER="gcc";
if [[ -f "${MAINRC_PATH}/mainrc" ]];
then
	source "${MAINRC_PATH}/mainrc";
fi;
  ```
3. ```source ~/.zshrc``` or ```source ~/.bashrc```

## Variables to change:
1. `MAINRC_PATH` -> path to cloned directory with mainrc-file.
2. `CC_COMPILER` [optional] -> set variables to use this compiler. Possible values: `clang`. `gcc`.
