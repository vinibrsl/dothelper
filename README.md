# dothelper
dothelper is a easy-to-use tool to backup your dotfiles to a git repository.

## Usage
1. Fork this repository (this is where your settings will be saved)
2. Clone this repository
3. Run `./dothelper setup git@github.com:yourusername/yourfork.git`
4. Run `./dothelper add ~/.vimrc ~/.bashrc ~/.gitconfig` to keep track of the
   files you want to backup
5. Run `./dothelper backup` and your dotfiles should be in your remote repository

If you need to update your dotfiles, just run `./dothelper backup` to push them
to your remote repository.
