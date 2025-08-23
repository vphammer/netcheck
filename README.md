# netcheck

A networking command-line tool created using Bash to simplify network diagnostics.

## Installation
Currently, the best way to install netcheck is to install to a directory on path. Below is a one-liner that will install netcheck for the user and add it to path (in case user does not have sudo access).
```
mkdir -p ~/.local/bin && curl https://raw.githubusercontent.com/vphammer/netcheck/main/netcheck -o ~/.local/bin/netcheck && chmod +x ~/.local/bin/netcheck && echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc && source ~/.bashrc
```

## Usage
```
netcheck <host-or-ip>
```
