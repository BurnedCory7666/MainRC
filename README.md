# MainRC
## Usage:
1. ```git clone https://github.com/BurnedCory7666/MainRC.git ~/.userrc```
2. Add at the end of `.bashrc` or `.zshrc` following:
  ```bash
  CC_COMPILER="clang";
  if [[ -f ~/.userrc/mainrc ]];
  then
	  source ~/.userrc/mainrc;
  fi
  ```
3. ```source ~/.zshrc``` or ```source ~/.bashrc```
If you want you can change `CC_COMPILER` (`clang|gcc`).
