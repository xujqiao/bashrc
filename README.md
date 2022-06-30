# my bash config


## main

0 **install/upgrade zsh**

1 **oh my zsh**

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

2 **mybash**

```bash
git clone https://github.com/xujqiao/bashrc.git ~/.bash
mv ~/.zshrc ~/.zshrc.backup
ln -s ~/.bash/zshrc ~/.zshrc
```


## plugin

1 **fzf-tab**

```bash
git clone https://github.com/Aloxaf/fzf-tab ~/.oh-my-zsh/plugins/fzf-tab
source ~/.zshrc
```

2 **fzf**

```bash
git clone --depth 1 https://github.com/junegunn/fzf.git
./fzf/install
source ~/.zshrc
```
