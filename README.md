
# bash-fzf

### Enhance GNU Bash with FZF Matching

This is an eloborated [GNU Bash](https://www.gnu.org/software/bash/)
run-command script which enhances interactive shell sessions with the following features,
all based on the excellent [FZF](https://github.com/junegunn/fzf/) searching utility:

- improved command history searching with overwritten FZF-based `CTRL+r` functionality,
  based on the built-in `history` command and its underlying `$HOME/.bash_history` file.

- additional command bookmarking with new FZF-based `CTRL+b` (bookmark) functionality,
  based on a new `bookmark` command and its underlying `.bash_bookmark` files in current,
  parent and `$HOME` directories.

- additional directory changing with new FZF-based `CTRL+g` (goto) functionality,
  based on an overwritten `cd` command, a new `cdpaths` command and
  its underlying `.bash_cdpaths` files in current, parent and `$HOME`
  directories.

