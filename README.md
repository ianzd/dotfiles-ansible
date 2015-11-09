# Ansible Playbook for dotfiles

*Run as:*
    ansible-playbook -i hosts top.yml

- Creates symlink for dotfiles to this working copy of the repo
- For vim, after installing Vundle and symlinking ~/.vimrc, will run Vundle
  PluginInstall

## Adding new dotfiles

- Create new dotfile in roles/dotfiles/files
- Add an entry to the dotfiles_base dict in roles/dotfiles/defaults/main.yml
