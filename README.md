# 👌LITify👌
## What is LITify?

👉 Masterpiece

👉 Script that makes you cool

👉 Script that changes substrings for emojis

## How to install?

Depends on your distro.

### Archlinux

`yaourt -S litify-git`

### Other distros

[Detailed guide](https://wiki.archlinux.org/index.php/Installation_guide)

## How to use?

For example:
```
$ echo 'dudoslav@zebra:/home/dudoslav ->' | litify
😂@🦓:/🏠/😂 👉
```

### Using in PS1

If your bashrc is setup like this:
```
export PS1="\[\033[38;5;11m\]\u\[$(tput sgr0)\]\[\033[38;5;15m\]@\h:\[$(tput sgr0)\]\[\033[38;5;6m\][\w]:\[$(tput sgr0)\]\[\033[38;5;15m\] \[$(tput sgr0)\]"
```

Modify it as follows to use it with litify:
```
export PS1='$(echo "\[\033[38;5;11m\]\u\[$(tput sgr0)\]\[\033[38;5;15m\]@\h:\[$(tput sgr0)\]\[\033[38;5;6m\][\w]:\[$(tput sgr0)\]\[\033[38;5;15m\] \[$(tput sgr0)\]" | litify)'
```
**Please note using apostrophes instead of double quotes is important!**


Btw, I use Arch.
