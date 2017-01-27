Dotfiles role
=========

Role to symlink dotfiles to ~/. By default it looks for folders and files that
follow the pattern `dot_*.symlink`.

For example:

```
| Source             | Symlinks to  |
|--------------------|--------------|
| dot_vimrc.symlink  | ~/.vimrc     |
| dot_vim.symlink    | ~/.vim       |
```
