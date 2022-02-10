# arch-iso

My own custom Arch Linux ISO image builder.

## Usage

Make sure `mkarchiso` is installed first

```shell
# pacman -S archiso
```

Build the ISO file with `mkarchiso`

```shell
# mkarchiso -v -w /tmp/archiso-tmp -o ~/ISOs .
```

_NOTE:_ The commands above should be ran as root.

Check out [the wiki](https://wiki.archlinux.org/title/Archiso) for more information.
