# dotfiles

## Omarchy Setup
### Monitors
#### Desktop
```bash
env = GDK_SCALE,1.75
monitor=desc:ASUSTek COMPUTER INC XG27AQDMG S5LMRS002727,2560x1440@240,0x0,1.6
```
#### Laptop
```bash
env = GDK_SCALE,2
monitor=desc:Samsung Display Corp. ATNA40CU05-0,2880x1800@120,0x0,auto
```
### Input
#### Laptop
```bash
kb_options = ctrl:nocaps,altwin:swap_alt_win
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

unbind = SUPER SHIFT ALT, E
bindd = SUPER SHIFT ALT, E, NUS Email, exec, omarchy-launch-or-focus-webapp "NUS Email" "https://outlook.office.com/mail"

unbind = SUPER SHIFT, N
bindd = SUPER SHIFT, N, Notes, exec, omarchy-launch-or-focus-webapp "Notes" "https://keep.google.com"

unbind = SUPER SHIFT, D
bindd = SUPER SHIFT, D, Drive, exec, omarchy-launch-or-focus-webapp "Drive" "https://drive.google.com"

unbind = SUPER SHIFT, T
bindd = SUPER SHIFT, T, Telegram, exec, omarchy-launch-or-focus-webapp "Telegram" "https://web.telegram.org"

unbind = SUPER SHIFT ALT, T
bindd = SUPER SHIFT ALT, T, Slack, exec, omarchy-launch-or-focus-webapp "Slack" "https://nus-test.slack.com"

unbind = SUPER SHIFT, X
bindd = SUPER SHIFT, X, Monkeytype, exec, omarchy-launch-or-focus-webapp "Monkeytype" "https://monkeytype.com"

unbind = SUPER SHIFT, Z
bindd = SUPER SHIFT, Z, Zoom, exec, omarchy-launch-or-focus-webapp "Zoom" "https://app.zoom.us/wc/home"

unbind = SUPER SHIFT, O
bindd = SUPER SHIFT, O, github, exec, omarchy-launch-webapp "https://github.com"

unbind = SUPER SHIFT ALT, O
bindd = SUPER SHIFT ALT, O, overleaf, exec, omarchy-launch-or-focus-webapp "Overleaf" "https://overleaf.com"
```
