# dotfiles

Idea borrowed from Brandon Invergo's ["Using GNU Stow to manage your dotfiles"].

```console
~/dotfiles$ tree -a --noreport bash git
bash
└── .bashrc
git
└── .gitconfig
~/dotfiles$ stow -v bash git
LINK: .bashrc => dotfiles/bash/.bashrc
LINK: .gitconfig => dotfiles/git/.gitconfig
```

["Using GNU Stow to manage your dotfiles"]: http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html
