# This extension is unmaintained

At first, after having seen the extension abandoned by its original author
and since I was still using it, I decided to try to maintain a fork. But
I quickly discovered a better maintained alternative and I suggest that
you switch to it:

* https://github.com/blackjackshellac/kitchenTimer
* https://extensions.gnome.org/extension/3955/kitchen-timer/

The gnome-shell-timer repository that you are looking at has some
supplementary work compared to
[olebowle](https://github.com/olebowle/gnome-shell-timer)'s repo and is
known to work with GNOME 3.38. But don't expect further changes to it.

# Timer extension for gnome-shell
- Provides a countdown timer in the gnome-shell top panel
- User adjustable timer presets for common tasks
- Manually adjustable timer

# Installation
## Archlinux
Get from [AUR](https://aur.archlinux.org/packages.php?ID=52047)

## Debian
Get from [Debian Packages](http://packages.debian.org/sid/gnome-shell-timer)

## Direct from source
- Get Source
    * for older versions see [releases](https://github.com/rhertzog/gnome-shell-timer/releases)
    * [master branch](https://github.com/rhertzog/gnome-shell-timer/zipball/master)

- use the provided [make.sh](https://github.com/rhertzog/gnome-shell-timer/blob/master/make.sh) script to (un)install the extension
- Enable the extension using gnome-tweaks or gnome-extensions-app
- Press *Alt + F2*, and *r* in command to restart gnome-shell

# Maintenance status

Since Ole Ernst (the original author) lost interest in gnome-shell-timer
and since pull requests were left unanswered, and since I was regularly
working on it as part of my Debian packaging work, I decided to step up to
maintain this extension.

I don't plan to add new features but I will at least process pull requests
to keep the extension working with the latest GNOME versions and I will
happily grant commit rights to other contributors that have shown some
ability and desire to maintain the extension.

 -- Raphaël Hertzog

# License
See [COPYING](https://github.com/rhertzog/gnome-shell-timer/blob/master/COPYING) for details.

# Thanks
- [Ole Ernst](https://github.com/olebowle) for the initial work on gnome-shell-timer
- Contributors: [gnome-shell-pomodoro](https://github.com/codito/gnome-shell-pomodoro/contributors) which was a nice starting point for this extension (code and documentation)
- Contributors: [gnome-shell-system-monitor-applet](https://github.com/paradoxxxzero/gnome-shell-system-monitor-applet/contributors) - pie diagram
- [Timer Applet](https://launchpad.net/timer-applet) - original idea
