# Jumpy
An Atom plugin that creates dynamic hot keys to jump around files and across visible panes.

## How to jump
1. Hit <kbd>shift</kbd> + <kbd>enter</kbd>
2. Choose from your presented labels:
3. Enter two characters.
4. Keep coding!

[ ![Jumpy in Action! - (gif made with recordit.co)][1]](https://raw.githubusercontent.com/DavidLGoldberg/jumpy/master/_images/jumpy.gif)

[1]: https://raw.githubusercontent.com/DavidLGoldberg/jumpy/master/_images/jumpy.gif

## Install
On command line:
```
apm install jumpy
```

## Notes
* Works great with or without [vim-mode](https://github.com/atom/vim-mode "vim-mode's Homepage")!
    * Modes supported:
        * command mode
        * insert mode
        * visual mode (sorry cancels select at the moment)
* Recommended custom [slightly pulsing green cursor](https://gist.github.com/DavidLGoldberg/166646fce043710ef920 "green cursor gist") (does not need Jumpy installed!)

## Key Bindings
### Defaults
* Enter jump mode
    * <kbd>shift</kbd> + <kbd>enter</kbd>
* Reset first character entered
    * <kbd>backspace</kbd>
* Cancel/exit jump mode (any)
    * <kbd>shift</kbd> + <kbd>enter</kbd>
    * <kbd>enter</kbd>
    * <kbd>esc</kbd>
    * <kbd>space</kbd>

## Settings
In your Jumpy preferences there is an option for font size.
You must set this to a decimal value less than 1.

![Jumpy settings](https://raw.githubusercontent.com/DavidLGoldberg/jumpy/master/_images/jumpy-settings.png)

Note: Styles can be overridden in "Atom" -> "Open Your Stylesheets"
(see examples below)
```less
.jumpy {
    &.label {
    }
    &.jump {
    }
}
```
[Example](https://gist.github.com/DavidLGoldberg/58b96b80902724ba3c5a "Example orange labels") (orange labels)

## TODO
* Remove unreachable highlights after first character hit (to reduce noise).
* Reset first character entered: <kbd>backspace</kbd> and repaint all
  labels to the screen.
* Better highlighting in visual mode.

## Keywords
(A little SEO juice since "apm search" only searches package name at the moment)

* Hot keys
* Key bindings
* Shortcuts
* Navigation
* Productivity
* Mouseless
