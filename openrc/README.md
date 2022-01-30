# Installation

## Manual

```bash
sudo cp kbdrate.rc /etc/init.d/kbdrate
sudo cp kbdrate.confd /etc/conf.d/kbdrate
sudo rc-update add kbdrate boot
```

## Packages

- Linux
  - Gentoo linux: [app-admin/kbdrate-openrc::dinolay](https://ari-web.xyz/gentooatom/app-admin/kbdrate-openrc)

# Configuration

Like any OpenRC service everything is configured in `/etc/init.d/`, specifically
for this service it's `/etc/conf.d/kbdrate`
