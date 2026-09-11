# glavakartela: whyred-alarm Pacman Repository

Repository of Arch Linux packages for Xiaomi, whyred.

## Installation

Add the following code snippet to your `/etc/pacman.conf`:

```conf
[whyred-alarm]
SigLevel = Optional
Server = https://glavakartela.github.io/whyred-alarm/repo/
```

Then, run `sudo pacman -Sy` to update repo.
