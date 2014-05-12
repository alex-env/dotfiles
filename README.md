# Dotfiles

These are my configuration files Vim, Git, Irb, Ack and more.

## Installation

Use the [homesick gem](https://github.com/alex-env) to install and symlink all files to their proper location:

    $ while read p; do brew $p; done < Brewfile
    $ gem install homesick
    $ homesick clone alex-env/dotfiles
    $ homeshick symlink alex-env/homeshick

