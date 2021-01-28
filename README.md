installed tmux with Homebrew and I added the tmux plugin to my zshrc file, but I get

zsh tmux plugin: tmux not found. Please install tmux before using this plugin.
which tmux returns

/usr/local/bin/tmux
Anything else I should check?

@mcornella emp3r0r

export LDFLAGS="-L/opt/openssl/lib"
export CPPFLAGS="-I/opt/openssl/include"
export PKG_CONFIG_PATH="/opt/openssl/lib/pkgconfig"
