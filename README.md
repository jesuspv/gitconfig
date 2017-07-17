# gitconfig
git configuration

Write to global `~/.gitconfig` with (replace `--global` with `--local` to write to the repository `.git/config` file instead):

```
# with curl
bash <(curl --location https://raw.githubusercontent.com/jesuspv/gitconfig/master/gitconfig) --global
# with wget
bash <(wget --output-document=- https://raw.githubusercontent.com/jesuspv/gitconfig/master/gitconfig) --global
```
