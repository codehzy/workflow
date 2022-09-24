# tmux + neovim + fish WorkFlow


## 1. neovim

```shell
$ cd ~/Desktop && git clone https://github.com/codehzy/workflow.git
$ mv ~/Desktop/workflow/nvim ~/.config/
```

## 2. tmux

```shell
$ cd
$ mv ~/Desktop/workflow/.tmux .
$ ln -s -f .tmux/.tmux.conf
$ cp .tmux/.tmux.conf.local ~
```

