# zinit-jenv

This work is heavely based on [zplugin-rbenv](https://github.com/htlsne/zplugin-rbenv)

`jenv init` with [zinit](https://github.com/zdharma/zinit). It makes zsh startup faster.

## Usage

```bash
# when jenv command in your path (e.g. installed with Homebrew)
zinit ice wait"0" lucid
zinit light anquegi/zinit-jenv
```

or

```bash
path=($HOME/.jenv/bin(N-/) $path) #path to jenv binary folder
if type jbenv > /dev/null 2>&1; then
    zinit ice wait"0" lucid
    zinit light anquegi/zinit-jenv
fi
```
