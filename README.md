# dotfiles

## Omarchy Setup
### Monitors
```bash
env = GDK_SCALE,1.75
monitor=desc:ASUSTek COMPUTER INC XG27AQDMG S5LMRS002727,2560x1440@240,0x0,1.6
```
### Keybindings
```bash
unbind = SUPER CTRL, UP
binddel = SUPER CTRL, UP, Volume up, exec, omarchy-swayosd-client --output-volume raise

unbind = SUPER CTRL, DOWN
binddel = SUPER CTRL, DOWN, Volume down, exec, omarchy-swayosd-client --output-volume lower

unbind = SUPER SHIFT, A
bindd = SUPER SHIFT, A, Gemini, exec, omarchy-launch-webapp "https://gemini.google.com"

unbind = SUPER SHIFT, C
bindd = SUPER SHIFT, C, Calendar, exec, omarchy-launch-webapp "https://calendar.google.com"

unbind = SUPER SHIFT, E
bindd = SUPER SHIFT, E, Email, exec, omarchy-launch-webapp "https://mail.google.com"

unbind = SUPER SHIFT, N
bindd = SUPER SHIFT, N, Notes, exec, omarchy-launch-webapp "https://keep.google.com"

unbind = SUPER SHIFT, D
bindd = SUPER SHIFT, D, Drive, exec, omarchy-launch-webapp "https://drive.google.com"
```
