# Nix Shell Installation

Multi-user installation (recommended) on Linux:

```
$ sh <(curl -L https://nixos.org/nix/install) --daemon
```

Verify installation:

```
$ nix --version
nix (Nix) 2.22.0
```

First steps using Nix:

```
$ nix-shell -p cowsay lolcat

[nix-shell:~]$ cowsay Hello, Nix! | lolcat
 _____________
< Hello, Nix! >
 -------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

[nix-shell:~]$ exit

```
