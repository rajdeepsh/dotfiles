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

unbind = SUPER SHIFT, S
bindd = SUPER SHIFT, S, Screenshot, exec, omarchy-capture-screenshot

unbind = SUPER SHIFT ALT, S
bindd = SUPER SHIFT ALT, S, Screenrecord, exec, omarchy-capture-screenrecording

unbind = SUPER SHIFT, A
bindd = SUPER SHIFT, A, Gemini, exec, omarchy-launch-webapp "https://gemini.google.com"

unbind = SUPER SHIFT ALT, A
bindd = SUPER SHIFT ALT, A, ChatGPT, exec, omarchy-launch-webapp "https://chatgpt.com"

unbind = SUPER SHIFT, C
bindd = SUPER SHIFT, C, Calendar, exec, omarchy-launch-or-focus-webapp "Calendar" "https://calendar.google.com"

unbind = SUPER SHIFT, E
bindd = SUPER SHIFT, E, Email, exec, omarchy-launch-or-focus-webapp "Email" "https://mail.google.com"

unbind = SUPER SHIFT, N
bindd = SUPER SHIFT, N, Notes, exec, omarchy-launch-or-focus-webapp "Notes" "https://keep.google.com"

unbind = SUPER SHIFT, D
bindd = SUPER SHIFT, D, Drive, exec, omarchy-launch-or-focus-webapp "Drive" "https://drive.google.com"

unbind = SUPER SHIFT, G
bindd = SUPER SHIFT, G, Telegram, exec, omarchy-launch-or-focus-webapp "Telegram" "https://web.telegram.org"

unbind = SUPER SHIFT ALT, G
bindd = SUPER SHIFT ALT, G, Slack, exec, omarchy-launch-or-focus-webapp "Slack" "https://nus-test.slack.com"

unbind = SUPER SHIFT, O
bindd = SUPER SHIFT, O, Monkeytype, exec, omarchy-launch-or-focus-webapp "Monkeytype" "https://monkeytype.com"

unbind = SUPER SHIFT, Z
bindd = SUPER SHIFT, Z, Zoom, exec, omarchy-launch-or-focus-webapp "Zoom" "https://app.zoom.us/wc/home"
```
