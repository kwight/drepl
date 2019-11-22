# drepl
A [Dart](https://dart.dev) REPL for local exploration, using Tmuxinator, filewatcher, and Vim.

To be clear, there's no magic here; you can use any filewatcher that calls the Dart compiler with your Dart code as the entry. If you believe in the Internet, you can also just go sign up for [Repl.it](https://repl.it) (but that's _suuuuper_ easy).

## Requirements
* [Dart SDK](https://dart.dev/tools/sdk)
* [filewatcher](https://github.com/filewatcher/filewatcher)
* [tmux](https://github.com/tmux/tmux)
* [Tmuxinator](https://github.com/tmuxinator/tmuxinator)

## Usage
* Create a symlink to `drepl.yml` in your Tmuxinator configuration directory, or copy it over.
* Run `tmuxinator start drepl`.