+++
title = 'Shortcuts All'
#date = 2024-01-14T07:07:07+01:00
draft = false
type = 'page'
slug = 'shortcutsall'
+++

# Linux and Developer Tools Keyboard Shortcuts Guide

## Table of Contents
- [Essential Ubuntu (Gnome) Keyboard Shortcuts](#essential-ubuntu-gnome-keyboard-shortcuts)
- [Zellij](#zellij-keyboard-shortcuts)
- [Vim Mode in Fish Shell](#vim-mode-in-fish-shell)
- [Default Mode in Fish Shell](#default-mode-in-fish-shell)
- [Browsers](#browser-keyboard-shortcuts)
- [Vimium Browser Extension Shortcuts](#vimium-browser-extension-shortcuts)
- [VS Code](#vs-code-keyboard-shortcuts)
- [NeoVim](#neovim-keyboard-shortcuts)
- [LazyVim](#lazyvim-keyboard-shortcuts)
- [Fish Shell](#fish-shell-fzffish-shortcuts)
- [VSCode Neovim Extension](#vscode-neovim-integration)

## Essential Ubuntu (Gnome) Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Super` | Opens Activities search |
| `Super+A` | Show application menu (9 dots grid) |
| `Ctrl+Alt+T` | Open terminal window |
| `Ctrl+Q` or `Ctrl+W` or `Alt+F4` | Close application window |
| `Super+Left/Right/Up/Down` | Snap window left/right/maximize/unmaximize |
| `Alt+Tab` (Alt+Shift+Tab) | Switch application window |
| `Super+Tab` (Super+Shift+Tab) | Switch application group|
| `Ctrl+Alt+Tab` | Switch between windows in all Workspaces (unsure about this one todo) |
| `Ctrl+Alt+Up/Down/Left/Right` | Switch workspace |
| `Alt+F6` | Quick switch windows of the same application |
| Ctrl+Alt+D` | Show desktop (press again to restore windows) |
| `Super+M` | Toggle notification tray |
| `Ctrl+Alt+L` | Lock screen |
| `Ctrl+Alt+Del` | Log out |
| `Alt+F2` | Run console (command prompt) |
| `Ctrl+Alt+Up/Down/Left/Right` | Switch workspace |
| `Shift+Ctrl+Alt+Up/Down/Left/Right` | Move window to workspace |
| `PrtScr` | Take screenshot |
| `Alt+PrtScr` | Take screenshot of window |
| `Shift+PrtScr` | Take screenshot of area |

> 📋 Note: Capital letters in shortcuts don't mean you press the Shift key. For example, T means 't' key only, not Shift+t.

### Custom Keyboard Shortcuts
Create your own shortcuts by going to:
Settings → Devices → Keyboard → Custom Shortcuts

Sources:
- https://itsfoss.com/ubuntu-shortcuts/

## Zellij Keyboard Shortcuts

### Locked Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl g` | Switch to Normal mode |

### Normal Mode
Normal mode is the default mode in Zellij.

### Resize Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl n` | Switch to Normal mode |
| `h` / `←` | Increase size left |
| `j` / `↓` | Increase size down |
| `k` / `↑` | Increase size up |
| `l` / `→` | Increase size right |
| `H` | Decrease size left |
| `J` | Decrease size down |
| `K` | Decrease size up |
| `L` | Decrease size right |
| `=` / `+` | Increase size |
| `-` | Decrease size |

### Pane Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl p` | Switch to Normal mode |
| `h` / `←` | Move focus left |
| `l` / `→` | Move focus right |
| `j` / `↓` | Move focus down |
| `k` / `↑` | Move focus up |
| `p` | Switch focus |
| `n` | New pane and switch to Normal mode |
| `d` | New pane downward and switch to Normal mode |
| `r` | New pane rightward and switch to Normal mode |
| `x` | Close focused pane and switch to Normal mode |
| `f` | Toggle fullscreen for focused pane and switch to Normal mode |
| `z` | Toggle pane frames and switch to Normal mode |
| `w` | Toggle floating panes and switch to Normal mode |
| `e` | Toggle pane embed/floating and switch to Normal mode |
| `c` | Switch to RenamePane mode with pane name input |
| `i` | Toggle pane pinned and switch to Normal mode |

### Move Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl h` | Switch to Normal mode |
| `n` / `Tab` | Move pane |
| `p` | Move pane backwards |
| `h` / `←` | Move pane left |
| `j` / `↓` | Move pane down |
| `k` / `↑` | Move pane up |
| `l` / `→` | Move pane right |

### Tab Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl t` | Switch to Normal mode |
| `r` | Switch to RenameTab mode with tab name input |
| `h` / `←` / `↑` / `k` | Go to previous tab |
| `l` / `→` / `↓` / `j` | Go to next tab |
| `n` | New tab and switch to Normal mode |
| `x` | Close tab and switch to Normal mode |
| `s` | Toggle active sync tab and switch to Normal mode |
| `b` | Break pane and switch to Normal mode |
| `]` | Break pane right and switch to Normal mode |
| `[` | Break pane left and switch to Normal mode |
| `1`-`9` | Go to tab 1-9 and switch to Normal mode |
| `Tab` | Toggle tab |

### Scroll Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl s` | Switch to Normal mode |
| `e` | Edit scrollback and switch to Normal mode |
| `s` | Switch to EnterSearch mode with search input |
| `Ctrl c` | Scroll to bottom and switch to Normal mode |
| `j` / `↓` | Scroll down |
| `k` / `↑` | Scroll up |
| `Ctrl f` / `PageDown` / `→` / `l` | Page scroll down |
| `Ctrl b` / `PageUp` / `←` / `h` | Page scroll up |
| `d` | Half page scroll down |
| `u` | Half page scroll up |

### Search Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl s` | Switch to Normal mode |
| `Ctrl c` | Scroll to bottom and switch to Normal mode |
| `j` / `↓` | Scroll down |
| `k` / `↑` | Scroll up |
| `Ctrl f` / `PageDown` / `→` / `l` | Page scroll down |
| `Ctrl b` / `PageUp` / `←` / `h` | Page scroll up |
| `d` | Half page scroll down |
| `u` | Half page scroll up |
| `n` | Search downward |
| `p` | Search upward |
| `c` | Toggle case sensitivity option |
| `w` | Toggle wrap option |
| `o` | Toggle whole word option |

### EnterSearch Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl c` / `Esc` | Switch to Scroll mode |
| `Enter` | Switch to Search mode |

### RenameTab Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl c` | Switch to Normal mode |
| `Esc` | Undo rename tab and switch to Tab mode |

### RenamePane Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl c` | Switch to Normal mode |
| `Esc` | Undo rename pane and switch to Pane mode |

### Session Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl o` | Switch to Normal mode |
| `Ctrl s` | Switch to Scroll mode |
| `d` | Detach |
| `w` | Launch or focus session manager plugin and switch to Normal mode |
| `c` | Launch or focus configuration plugin and switch to Normal mode |
| `p` | Launch or focus plugin manager and switch to Normal mode |
| `a` | Launch or focus about plugin and switch to Normal mode |

### Tmux Mode
| Shortcut | Action |
|----------|--------|
| `[` | Switch to Scroll mode |
| `Ctrl b` | Write 2 and switch to Normal mode |
| `"` | New pane downward and switch to Normal mode |
| `%` | New pane rightward and switch to Normal mode |
| `z` | Toggle fullscreen focus and switch to Normal mode |
| `c` | New tab and switch to Normal mode |
| `,` | Switch to RenameTab mode |
| `p` | Go to previous tab and switch to Normal mode |
| `n` | Go to next tab and switch to Normal mode |
| `Left` / `h` | Move focus left and switch to Normal mode |
| `Right` / `l` | Move focus right and switch to Normal mode |
| `Down` / `j` | Move focus down and switch to Normal mode |
| `Up` / `k` | Move focus up and switch to Normal mode |
| `o` | Focus next pane |
| `d` | Detach |
| `Space` | Next swap layout |
| `x` | Close focus and switch to Normal mode |

### Shared Shortcuts
| Shortcut | Action | Available In |
|----------|--------|-------------|
| `Ctrl g` | Switch to Locked mode | All except Locked |
| `Ctrl q` | Quit | All except Locked |
| `Alt f` | Toggle floating panes | All except Locked |
| `Alt n` | New pane | All except Locked |
| `Alt i` | Move tab left | All except Locked |
| `Alt o` | Move tab right | All except Locked |
| `Alt h` / `Alt ←` | Move focus or tab left | All except Locked |
| `Alt l` / `Alt →` | Move focus or tab right | All except Locked |
| `Alt j` / `Alt ↓` | Move focus down | All except Locked |
| `Alt k` / `Alt ↑` | Move focus up | All except Locked |
| `Alt =` / `Alt +` | Increase size | All except Locked |
| `Alt -` | Decrease size | All except Locked |
| `Alt [` | Previous swap layout | All except Locked |
| `Alt ]` | Next swap layout | All except Locked |
| `Enter` / `Esc` | Switch to Normal mode | All except Normal and Locked |

### Mode Switching Shortcuts
| Shortcut | Action | Available In |
|----------|--------|-------------|
| `Ctrl p` | Switch to Pane mode | All except Pane and Locked |
| `Ctrl n` | Switch to Resize mode | All except Resize and Locked |
| `Ctrl s` | Switch to Scroll mode | All except Scroll and Locked |
| `Ctrl o` | Switch to Session mode | All except Session and Locked |
| `Ctrl t` | Switch to Tab mode | All except Tab and Locked |
| `Ctrl h` | Switch to Move mode | All except Move and Locked |
| `Ctrl b` | Switch to Tmux mode | All except Tmux and Locked |

Source:
- https://github.com/zellij-org/zellij/blob/main/zellij-utils/assets/config/default.kdl

## Vim Mode in Fish Shell

### Essential Shortcuts
| Shortcut | Action |
|----------|--------|
| `Escape` | Switch to normal (command) mode |
| `i` | Enter insert mode |
| `a` | Enter insert mode after cursor |
| `A` | Enter insert mode at end of line |
| `hjkl` | Navigate left/down/up/right |
| `0` | Move to beginning of line |
| `$` | Move to end of line |
| `w` | Move forward one word |
| `b` | Move backward one word |
| `dd` | Delete entire line |
| `dw` | Delete word |
| `d$` | Delete to end of line |
| `u` | Undo |
| `/` | Search forward |
| `n` | Next search result |
| `N` | Previous search result |
| `v` | Enter visual mode for selection |
| `y` | Yank (copy) selected text |
| `p` | Paste |

Source:
- Fish shell documentation (fish_vi_key_bindings)

## Default Mode in Fish Shell

### Navigation & History
| Shortcut | Action |
|----------|--------|
| `Ctrl+A` | Move to beginning of line |
| `Ctrl+E` | Move to end of line |
| `Alt+F` | Move forward one word |
| `Alt+B` | Move backward one word |
| `Ctrl+P` or `↑` | Previous command in history |
| `Ctrl+N` or `↓` | Next command in history |
| `Ctrl+R` | Reverse search through history |
| `Alt+.` | Insert last argument of previous command |

### Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl+U` | Delete from cursor to beginning of line |
| `Ctrl+K` | Delete from cursor to end of line |
| `Ctrl+W` | Delete previous word |
| `Alt+D` | Delete word forward |
| `Ctrl+T` | Swap two characters |
| `Alt+T` | Swap two words |
| `Ctrl+L` | Clear screen |

### Command Control
| Shortcut | Action |
|----------|--------|
| `Ctrl+C` | Cancel current command |
| `Ctrl+Z` | Suspend process |
| `Tab` | Auto-complete |
| `Alt+E` | Edit command in external editor |
| `Alt+L` | List directory contents |

Source:
- Fish shell documentation (default key bindings)

## Browser Keyboard Shortcuts

### Navigation
| Shortcut | Action |
|----------|--------|
| `Ctrl+L` or `F6` | Focus on address bar |
| `Ctrl+T` | Open new tab |
| `Ctrl+N` | Open new window |
| `Ctrl+W` | Close current tab |
| `Ctrl+Shift+T` | Reopen closed tab |
| `Ctrl+Tab` | Switch to next tab |
| `Ctrl+Shift+Tab` | Switch to previous tab |
| `Ctrl+1` to `Ctrl+8` | Switch to specific tab (1st through 8th) |
| `Ctrl+9` | Switch to the last tab |
| `Alt+Home` | Go to homepage |
| `Alt+←` or `Backspace` | Go back |
| `Alt+→` or `Shift+Backspace` | Go forward |
| `F5` | Reload page |
| `Ctrl+F5` or `Shift+F5` | Reload page (bypass cache) |
| `Esc` | Stop loading page |

### Viewing and Reading
| Shortcut | Action |
|----------|--------|
| `F11` | Toggle full screen |
| `Ctrl+F` | Find on page |
| `F3` or `Ctrl+G` | Find next match |
| `Shift+F3` or `Ctrl+Shift+G` | Find previous match |
| `Ctrl++` (plus) | Zoom in |
| `Ctrl+-` (minus) | Zoom out |
| `Ctrl+0` | Reset zoom to 100% |
| `Ctrl+U` | View page source |
| `Space` | Scroll down |
| `Shift+Space` | Scroll up |
| `Home` | Go to top of page |
| `End` | Go to bottom of page |
| `Ctrl+D` | Bookmark current page |
| `Ctrl+Shift+D` | Bookmark all open tabs |
| `Ctrl+H` | View history |
| `Ctrl+J` | View downloads |

### Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl+C` | Copy selected text |
| `Ctrl+X` | Cut selected text |
| `Ctrl+V` | Paste text |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` or `Ctrl+Shift+Z` | Redo |
| `Ctrl+A` | Select all |

### Miscellaneous
| Shortcut | Action |
|----------|--------|
| `Alt+F` or `F10` | Open browser menu |
| `Ctrl+K` or `Ctrl+E` | Search from address bar |
| `Ctrl+Enter` | Add www. and .com to text in address bar |
| `Shift+Enter` | Add www. and .net to text in address bar |
| `Ctrl+Shift+Enter` | Add www. and .org to text in address bar |
| `Ctrl+Shift+Delete` | Open clear browsing data options |
| `Ctrl+Shift+B` | Toggle bookmarks bar |
| `Ctrl+Shift+N` | New incognito/private window |
| `Ctrl+P` | Print page |
| `Ctrl+S` | Save page |

### Developer Tools
| Shortcut | Action |
|----------|--------|
| `Ctrl+Shift+I` or `F12` | Open developer tools |
| `Ctrl+Shift+J` | Open developer tools console |
| `Ctrl+Shift+C` | Inspect element tool (element selector) |
| `Ctrl+Shift+M` | Toggle device emulation (responsive design mode) |
| `F8` or `Ctrl+\` | Pause/resume script execution |
| `F10` or `Ctrl+'` | Step over next function call |
| `F11` or `Ctrl+;` | Step into next function call |
| `Shift+F11` or `Ctrl+Shift+;` | Step out of current function |

Source:
- Common browser shortcuts (Chrome, Firefox, Edge)

## Vimium Browser Extension Shortcuts

### Basic Navigation
| Shortcut | Action |
|----------|--------|
| `?` | Show help (all commands) |
| `j` | Scroll down |
| `k` | Scroll up |
| `h` | Scroll left |
| `l` | Scroll right |
| `gg` | Scroll to the top of the page |
| `G` | Scroll to the bottom of the page |
| `d` | Scroll down half a page |
| `u` | Scroll up half a page |
| `f` | Open a link in the current tab |
| `F` | Open a link in a new tab |
| `r` | Reload the page |
| `gs` | View page source |
| `yy` | Copy the current URL to the clipboard |
| `p` | Open the clipboard's URL in the current tab |
| `P` | Open the clipboard's URL in a new tab |

### Tabs Management
| Shortcut | Action |
|----------|--------|
| `J` or `gT` | Go to the previous tab |
| `K` or `gt` | Go to the next tab |
| `g0` | Go to the first tab |
| `g# Linux and Developer Tools Keyboard Shortcuts Guide

## Table of Contents
- [Essential Ubuntu (Gnome) Keyboard Shortcuts](#essential-ubuntu-gnome-keyboard-shortcuts)
- [Zellij Keyboard Shortcuts](#zellij-keyboard-shortcuts)
- [Vim Mode in Fish Shell](#vim-mode-in-fish-shell)
- [Default Mode in Fish Shell](#default-mode-in-fish-shell)
- [Browser Keyboard Shortcuts](#browser-keyboard-shortcuts)
- [Vimium Browser Extension Shortcuts](#vimium-browser-extension-shortcuts)
- [VS Code Keyboard Shortcuts](#vs-code-keyboard-shortcuts)
- [NeoVim Keyboard Shortcuts](#neovim-keyboard-shortcuts)
- [LazyVim Keyboard Shortcuts](#lazyvim-keyboard-shortcuts)
- [Fish Shell fzf.fish Shortcuts](#fish-shell-fzffish-shortcuts)
- [VSCode Neovim Integration](#vscode-neovim-integration)

## Essential Ubuntu (Gnome) Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Super` | Opens Activities search |
| `Ctrl+Alt+T` | Open terminal window |
| `Super+L` or `Ctrl+Alt+L` | Lock screen |
| `Super+D` or `Ctrl+Alt+D` | Show desktop (press again to restore windows) |
| `Super+A` | Show application menu (9 dots grid) |
| `Super+Tab` or `Alt+Tab` | Switch between running applications |
| `Super+Shift+Tab` | Cycle in reverse order |
| `Super+` ` | Switch between multiple instances of the same application |
| `Ctrl+Alt+Tab` | Switch between windows in all Workspaces |
| `Super+←` | Snap window to left half of screen |
| `Super+→` | Snap window to right half of screen |
| `Super+↑` | Maximize window |
| `Super+↓` | Restore window to original size |
| `Super+M` or `Super+V` | Toggle notification tray |
| `Super+Space` | Change input keyboard |
| `Alt+F2` | Run console (command prompt) |
| `Ctrl+Q` or `Ctrl+W` or `Alt+F4` | Close application window |
| `Ctrl+Alt+↑/←/→/↓` | Move between workspaces |
| `Ctrl+Alt+Del` | Log out |

> 📋 Note: Capital letters in shortcuts don't mean you press the Shift key. For example, T means 't' key only, not Shift+t.

### Custom Keyboard Shortcuts
Create your own shortcuts by going to:
Settings → Devices → Keyboard → Custom Shortcuts

Sources:
- https://itsfoss.com/ubuntu-shortcuts/

## Zellij Keyboard Shortcuts

### Locked Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl g` | Switch to Normal mode |

### Normal Mode
Normal mode is the default mode in Zellij.

### Resize Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl n` | Switch to Normal mode |
| `h` / `←` | Increase size left |
| `j` / `↓` | Increase size down |
| `k` / `↑` | Increase size up |
| `l` / `→` | Increase size right |
| `H` | Decrease size left |
| `J` | Decrease size down |
| `K` | Decrease size up |
| `L` | Decrease size right |
| `=` / `+` | Increase size |
| `-` | Decrease size |

### Pane Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl p` | Switch to Normal mode |
| `h` / `←` | Move focus left |
| `l` / `→` | Move focus right |
| `j` / `↓` | Move focus down |
| `k` / `↑` | Move focus up |
| `p` | Switch focus |
| `n` | New pane and switch to Normal mode |
| `d` | New pane downward and switch to Normal mode |
| `r` | New pane rightward and switch to Normal mode |
| `x` | Close focused pane and switch to Normal mode |
| `f` | Toggle fullscreen for focused pane and switch to Normal mode |
| `z` | Toggle pane frames and switch to Normal mode |
| `w` | Toggle floating panes and switch to Normal mode |
| `e` | Toggle pane embed/floating and switch to Normal mode |
| `c` | Switch to RenamePane mode with pane name input |
| `i` | Toggle pane pinned and switch to Normal mode |

### Move Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl h` | Switch to Normal mode |
| `n` / `Tab` | Move pane |
| `p` | Move pane backwards |
| `h` / `←` | Move pane left |
| `j` / `↓` | Move pane down |
| `k` / `↑` | Move pane up |
| `l` / `→` | Move pane right |

### Tab Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl t` | Switch to Normal mode |
| `r` | Switch to RenameTab mode with tab name input |
| `h` / `←` / `↑` / `k` | Go to previous tab |
| `l` / `→` / `↓` / `j` | Go to next tab |
| `n` | New tab and switch to Normal mode |
| `x` | Close tab and switch to Normal mode |
| `s` | Toggle active sync tab and switch to Normal mode |
| `b` | Break pane and switch to Normal mode |
| `]` | Break pane right and switch to Normal mode |
| `[` | Break pane left and switch to Normal mode |
| `1`-`9` | Go to tab 1-9 and switch to Normal mode |
| `Tab` | Toggle tab |

### Scroll Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl s` | Switch to Normal mode |
| `e` | Edit scrollback and switch to Normal mode |
| `s` | Switch to EnterSearch mode with search input |
| `Ctrl c` | Scroll to bottom and switch to Normal mode |
| `j` / `↓` | Scroll down |
| `k` / `↑` | Scroll up |
| `Ctrl f` / `PageDown` / `→` / `l` | Page scroll down |
| `Ctrl b` / `PageUp` / `←` / `h` | Page scroll up |
| `d` | Half page scroll down |
| `u` | Half page scroll up |

### Search Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl s` | Switch to Normal mode |
| `Ctrl c` | Scroll to bottom and switch to Normal mode |
| `j` / `↓` | Scroll down |
| `k` / `↑` | Scroll up |
| `Ctrl f` / `PageDown` / `→` / `l` | Page scroll down |
| `Ctrl b` / `PageUp` / `←` / `h` | Page scroll up |
| `d` | Half page scroll down |
| `u` | Half page scroll up |
| `n` | Search downward |
| `p` | Search upward |
| `c` | Toggle case sensitivity option |
| `w` | Toggle wrap option |
| `o` | Toggle whole word option |

### EnterSearch Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl c` / `Esc` | Switch to Scroll mode |
| `Enter` | Switch to Search mode |

### RenameTab Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl c` | Switch to Normal mode |
| `Esc` | Undo rename tab and switch to Tab mode |

### RenamePane Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl c` | Switch to Normal mode |
| `Esc` | Undo rename pane and switch to Pane mode |

### Session Mode
| Shortcut | Action |
|----------|--------|
| `Ctrl o` | Switch to Normal mode |
| `Ctrl s` | Switch to Scroll mode |
| `d` | Detach |
| `w` | Launch or focus session manager plugin and switch to Normal mode |
| `c` | Launch or focus configuration plugin and switch to Normal mode |
| `p` | Launch or focus plugin manager and switch to Normal mode |
| `a` | Launch or focus about plugin and switch to Normal mode |

### Tmux Mode
| Shortcut | Action |
|----------|--------|
| `[` | Switch to Scroll mode |
| `Ctrl b` | Write 2 and switch to Normal mode |
| `"` | New pane downward and switch to Normal mode |
| `%` | New pane rightward and switch to Normal mode |
| `z` | Toggle fullscreen focus and switch to Normal mode |
| `c` | New tab and switch to Normal mode |
| `,` | Switch to RenameTab mode |
| `p` | Go to previous tab and switch to Normal mode |
| `n` | Go to next tab and switch to Normal mode |
| `Left` / `h` | Move focus left and switch to Normal mode |
| `Right` / `l` | Move focus right and switch to Normal mode |
| `Down` / `j` | Move focus down and switch to Normal mode |
| `Up` / `k` | Move focus up and switch to Normal mode |
| `o` | Focus next pane |
| `d` | Detach |
| `Space` | Next swap layout |
| `x` | Close focus and switch to Normal mode |

### Shared Shortcuts
| Shortcut | Action | Available In |
|----------|--------|-------------|
| `Ctrl g` | Switch to Locked mode | All except Locked |
| `Ctrl q` | Quit | All except Locked |
| `Alt f` | Toggle floating panes | All except Locked |
| `Alt n` | New pane | All except Locked |
| `Alt i` | Move tab left | All except Locked |
| `Alt o` | Move tab right | All except Locked |
| `Alt h` / `Alt ←` | Move focus or tab left | All except Locked |
| `Alt l` / `Alt →` | Move focus or tab right | All except Locked |
| `Alt j` / `Alt ↓` | Move focus down | All except Locked |
| `Alt k` / `Alt ↑` | Move focus up | All except Locked |
| `Alt =` / `Alt +` | Increase size | All except Locked |
| `Alt -` | Decrease size | All except Locked |
| `Alt [` | Previous swap layout | All except Locked |
| `Alt ]` | Next swap layout | All except Locked |
| `Enter` / `Esc` | Switch to Normal mode | All except Normal and Locked |

### Mode Switching Shortcuts
| Shortcut | Action | Available In |
|----------|--------|-------------|
| `Ctrl p` | Switch to Pane mode | All except Pane and Locked |
| `Ctrl n` | Switch to Resize mode | All except Resize and Locked |
| `Ctrl s` | Switch to Scroll mode | All except Scroll and Locked |
| `Ctrl o` | Switch to Session mode | All except Session and Locked |
| `Ctrl t` | Switch to Tab mode | All except Tab and Locked |
| `Ctrl h` | Switch to Move mode | All except Move and Locked |
| `Ctrl b` | Switch to Tmux mode | All except Tmux and Locked |

Source:
- https://github.com/zellij-org/zellij/blob/main/zellij-utils/assets/config/default.kdl

## Vim Mode in Fish Shell

### Essential Shortcuts
| Shortcut | Action |
|----------|--------|
| `Escape` | Switch to normal (command) mode |
| `i` | Enter insert mode |
| `a` | Enter insert mode after cursor |
| `A` | Enter insert mode at end of line |
| `hjkl` | Navigate left/down/up/right |
| `0` | Move to beginning of line |
| `$` | Move to end of line |
| `w` | Move forward one word |
| `b` | Move backward one word |
| `dd` | Delete entire line |
| `dw` | Delete word |
| `d$` | Delete to end of line |
| `u` | Undo |
| `/` | Search forward |
| `n` | Next search result |
| `N` | Previous search result |
| `v` | Enter visual mode for selection |
| `y` | Yank (copy) selected text |
| `p` | Paste |

Source:
- Fish shell documentation (fish_vi_key_bindings)

## Default Mode in Fish Shell

### Navigation & History
| Shortcut | Action |
|----------|--------|
| `Ctrl+A` | Move to beginning of line |
| `Ctrl+E` | Move to end of line |
| `Alt+F` | Move forward one word |
| `Alt+B` | Move backward one word |
| `Ctrl+P` or `↑` | Previous command in history |
| `Ctrl+N` or `↓` | Next command in history |
| `Ctrl+R` | Reverse search through history |
| `Alt+.` | Insert last argument of previous command |

### Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl+U` | Delete from cursor to beginning of line |
| `Ctrl+K` | Delete from cursor to end of line |
| `Ctrl+W` | Delete previous word |
| `Alt+D` | Delete word forward |
| `Ctrl+T` | Swap two characters |
| `Alt+T` | Swap two words |
| `Ctrl+L` | Clear screen |

### Command Control
| Shortcut | Action |
|----------|--------|
| `Ctrl+C` | Cancel current command |
| `Ctrl+Z` | Suspend process |
| `Tab` | Auto-complete |
| `Alt+E` | Edit command in external editor |
| `Alt+L` | List directory contents |

Source:
- Fish shell documentation (default key bindings)

## Browser Keyboard Shortcuts

### Navigation
| Shortcut | Action |
|----------|--------|
| `Ctrl+L` or `F6` | Focus on address bar |
| `Ctrl+T` | Open new tab |
| `Ctrl+N` | Open new window |
| `Ctrl+W` | Close current tab |
| `Ctrl+Shift+T` | Reopen closed tab |
| `Ctrl+Tab` | Switch to next tab |
| `Ctrl+Shift+Tab` | Switch to previous tab |
| `Ctrl+1` to `Ctrl+8` | Switch to specific tab (1st through 8th) |
| `Ctrl+9` | Switch to the last tab |
| `Alt+Home` | Go to homepage |
| `Alt+←` or `Backspace` | Go back |
| `Alt+→` or `Shift+Backspace` | Go forward |
| `F5` | Reload page |
| `Ctrl+F5` or `Shift+F5` | Reload page (bypass cache) |
| `Esc` | Stop loading page |

### Viewing and Reading
| Shortcut | Action |
|----------|--------|
| `F11` | Toggle full screen |
| `Ctrl+F` | Find on page |
| `F3` or `Ctrl+G` | Find next match |
| `Shift+F3` or `Ctrl+Shift+G` | Find previous match |
| `Ctrl++` (plus) | Zoom in |
| `Ctrl+-` (minus) | Zoom out |
| `Ctrl+0` | Reset zoom to 100% |
| `Ctrl+U` | View page source |
| `Space` | Scroll down |
| `Shift+Space` | Scroll up |
| `Home` | Go to top of page |
| `End` | Go to bottom of page |
| `Ctrl+D` | Bookmark current page |
| `Ctrl+Shift+D` | Bookmark all open tabs |
| `Ctrl+H` | View history |
| `Ctrl+J` | View downloads |

### Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl+C` | Copy selected text |
| `Ctrl+X` | Cut selected text |
| `Ctrl+V` | Paste text |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` or `Ctrl+Shift+Z` | Redo |
| `Ctrl+A` | Select all |

### Miscellaneous
| Shortcut | Action |
|----------|--------|
| `Alt+F` or `F10` | Open browser menu |
| `Ctrl+K` or `Ctrl+E` | Search from address bar |
| `Ctrl+Enter` | Add www. and .com to text in address bar |
| `Shift+Enter` | Add www. and .net to text in address bar |
| `Ctrl+Shift+Enter` | Add www. and .org to text in address bar |
| `Ctrl+Shift+Delete` | Open clear browsing data options |
| `Ctrl+Shift+B` | Toggle bookmarks bar |
| `Ctrl+Shift+N` | New incognito/private window |
| `Ctrl+P` | Print page |
| `Ctrl+S` | Save page |

### Developer Tools
| Shortcut | Action |
|----------|--------|
| `Ctrl+Shift+I` or `F12` | Open developer tools |
| `Ctrl+Shift+J` | Open developer tools console |
| `Ctrl+Shift+C` | Inspect element tool (element selector) |
| `Ctrl+Shift+M` | Toggle device emulation (responsive design mode) |
| `F8` or `Ctrl+\` | Pause/resume script execution |
| `F10` or `Ctrl+'` | Step over next function call |
| `F11` or `Ctrl+;` | Step into next function call |
| `Shift+F11` or `Ctrl+Shift+;` | Step out of current function |

Source:
- Common browser shortcuts (Chrome, Firefox, Edge)

 | Go to the last tab |
| `t` | Create new tab |
| `x` | Close current tab |
| `X` | Restore closed tab |
| `^` | Go to previously-visited tab |
| `T` | Search through your open tabs |

### History
| Shortcut | Action |
|----------|--------|
| `H` | Go back in history |
| `L` | Go forward in history |

### Marks
| Shortcut | Action |
|----------|--------|
| `ma` | Set local mark "a" |
| `mA` | Set global mark "A" |
| `'a` | Jump to local mark "a" |
| `'A` | Jump to global mark "A" |

### Advanced Navigation
| Shortcut | Action |
|----------|--------|
| `/` | Enter find mode |
| `n` | Cycle forward to the next find match |
| `N` | Cycle backward to the previous find match |
| `o` | Open URL, bookmark or history entry |
| `O` | Open URL, bookmark or history entry in a new tab |
| `b` or `Ctrl-b` | Search bookmarks |
| `B` | Search bookmarks (new tab) |
| `[[` | Follow the link labeled "previous" or "<" |
| `]]` | Follow the link labeled "next" or ">" |

### Visual Mode
| Shortcut | Action |
|----------|--------|
| `v` | Enter visual mode |
| `V` | Enter visual line mode |
| Once in visual mode: |
| `h`, `j`, `k`, `l` | Move the cursor |
| `y` | Copy selected text |
| `Esc` | Exit visual mode |

### Miscellaneous
| Shortcut | Action |
|----------|--------|
| `i` | Enter insert mode (disable Vimium) |
| `Esc` | Exit insert mode |
| `gi` | Focus the first text input on the page |
| `gf` | Cycle focus to the next frame |
| `zi` | Zoom page in |
| `zo` | Zoom page out |
| `zz` | Reset zoom to default |
| `yf` | Copy a link URL to the clipboard |

### Advanced Commands
| Shortcut | Action |
|----------|--------|
| `:` | Enter command mode |
| Some useful commands: |
| `:open example.com` | Open URL in current tab |
| `:tabnew example.com` | Open URL in new tab |
| `:duplicate` | Duplicate current tab |
| `:settings` | Open Vimium settings |

Source:
- Vimium browser extension documentation

## VS Code Keyboard Shortcuts

### Editor Basics
| Shortcut | Action |
|----------|--------|
| `Ctrl+X` | Cut line (empty selection) |
| `Ctrl+C` | Copy line (empty selection) |
| `Alt+↑` / `Alt+↓` | Move line up/down |
| `Shift+Alt+↑` / `Shift+Alt+↓` | Copy line up/down |
| `Ctrl+Shift+K` | Delete line |
| `Ctrl+Enter` | Insert line below |
| `Ctrl+Shift+Enter` | Insert line above |
| `Ctrl+]` / `Ctrl+[` | Indent/outdent line |
| `Home` / `End` | Go to beginning/end of line |
| `Ctrl+Home` / `Ctrl+End` | Go to beginning/end of file |
| `Ctrl+L` | Select current line |
| `Ctrl+F2` | Select all occurrences of current word |
| `Ctrl+Alt+↑` / `Ctrl+Alt+↓` | Insert cursor above/below |
| `Alt+Click` | Insert cursor at position |
| `Ctrl+Space` | Trigger suggestion |
| `Ctrl+Shift+Space` | Trigger parameter hints |
| `Tab` | Emmet expand abbreviation (in HTML/CSS files) |

### Multi-cursor and Selection
| Shortcut | Action |
|----------|--------|
| `Alt+Click` | Insert cursor |
| `Ctrl+Alt+↑` / `Ctrl+Alt+↓` | Insert cursor above/below |
| `Ctrl+U` | Undo last cursor operation |
| `Shift+Alt+I` | Insert cursor at end of each line selected |
| `Ctrl+L` | Select current line |
| `Ctrl+Shift+L` | Select all occurrences of current selection |
| `Shift+Alt+→` | Expand selection |
| `Shift+Alt+←` | Shrink selection |
| `Shift+Alt+(drag mouse)` | Column (box) selection |
| `Ctrl+Shift+Alt+(arrow key)` | Column (box) selection |

### Rich Language Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl+Space` | Trigger suggestion |
| `Ctrl+Shift+Space` | Trigger parameter hints |
| `Shift+Alt+F` | Format document |
| `Ctrl+K Ctrl+F` | Format selection |
| `F12` | Go to definition |
| `Alt+F12` | Peek definition |
| `Ctrl+K F12` | Open definition to the side |
| `Ctrl+.` | Quick fix |
| `F2` | Rename symbol |
| `Ctrl+Shift+.` / `Ctrl+Shift+,` | Replace with next/previous value |
| `Ctrl+K Ctrl+X` | Trim trailing whitespace |
| `Ctrl+K M` | Change file language |

### Navigation
| Shortcut | Action |
|----------|--------|
| `Ctrl+T` | Show all symbols |
| `Ctrl+G` | Go to line... |
| `Ctrl+P` | Go to file... |
| `Ctrl+Shift+O` | Go to symbol... |
| `Ctrl+Shift+M` | Show problems panel |
| `F8` / `Shift+F8` | Go to next/previous error or warning |
| `Alt+←` / `Alt+→` | Go back/forward |
| `Ctrl+M` | Toggle Tab moves focus |
| `Ctrl+F` | Find |
| `Ctrl+H` | Replace |
| `F3` / `Shift+F3` | Find next/previous |
| `Alt+Enter` | Select all occurrences of Find match |
| `Ctrl+D` | Add selection to next Find match |
| `Ctrl+K Ctrl+D` | Move last selection to next Find match |
| `Alt+C` / `Alt+R` / `Alt+W` | Toggle case sensitivity / regex / whole word |

### Editor Management
| Shortcut | Action |
|----------|--------|
| `Ctrl+F4` / `Ctrl+W` | Close editor |
| `Ctrl+K F` | Close folder |
| `Ctrl+\` | Split editor |
| `Ctrl+1` / `Ctrl+2` / `Ctrl+3` | Focus into 1st, 2nd, 3rd editor group |
| `Ctrl+K Ctrl+←` / `Ctrl+K Ctrl+→` | Focus into previous/next editor group |
| `Ctrl+Shift+PgUp` / `Ctrl+Shift+PgDn` | Move editor left/right |
| `Ctrl+K ←` / `Ctrl+K →` | Move active editor group |

### File Management
| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | New file |
| `Ctrl+O` | Open file... |
| `Ctrl+S` | Save |
| `Ctrl+Shift+S` | Save as... |
| `Ctrl+K S` | Save all |
| `Ctrl+F4` | Close |
| `Ctrl+K Ctrl+W` | Close all |
| `Ctrl+Shift+T` | Reopen closed editor |
| `Ctrl+K Enter` | Keep preview editor open |
| `Ctrl+Tab` | Open next |
| `Ctrl+Shift+Tab` | Open previous |
| `Ctrl+K P` | Copy path of active file |
| `Ctrl+K R` | Reveal active file in Explorer |
| `Ctrl+K O` | Show active file in new window/instance |

### Display
| Shortcut | Action |
|----------|--------|
| `F11` | Toggle full screen |
| `Shift+Alt+0` | Toggle editor layout (horizontal/vertical) |
| `Ctrl+=` / `Ctrl+-` | Zoom in/out |
| `Ctrl+B` | Toggle sidebar visibility |
| `Ctrl+Shift+E` | Show Explorer / Toggle focus |
| `Ctrl+Shift+F` | Show Search |
| `Ctrl+Shift+G` | Show Source Control |
| `Ctrl+Shift+D` | Show Debug |
| `Ctrl+Shift+X` | Show Extensions |
| `Ctrl+Shift+H` | Replace in files |
| `Ctrl+Shift+J` | Toggle Search details |
| `Ctrl+Shift+U` | Show Output panel |
| `Ctrl+Shift+V` | Open Markdown preview |
| `Ctrl+K V` | Open Markdown preview to the side |
| `Ctrl+K Z` | Zen Mode (Esc Esc to exit) |

### Debug
| Shortcut | Action |
|----------|--------|
| `F9` | Toggle breakpoint |
| `F5` | Start/Continue |
| `Shift+F5` | Stop |
| `F11` / `Shift+F11` | Step into/out |
| `F10` | Step over |
| `Ctrl+K Ctrl+I` | Show hover |

### Integrated Terminal
| Shortcut | Action |
|----------|--------|
| ``Ctrl+` `` | Show integrated terminal |
| ``Ctrl+Shift+` `` | Create new terminal |
| `Ctrl+Shift+C` | Copy selection |
| `Ctrl+Shift+V` | Paste into active terminal |
| `Ctrl+↑` / `Ctrl+↓` | Scroll up/down |
| `Shift+PgUp` / `Shift+PgDn` | Scroll page up/down |
| `Ctrl+Home` / `Ctrl+End` | Scroll to top/bottom |

Source:
- VS Code default keyboard shortcuts for Windows/Linux

## NeoVim Keyboard Shortcuts

### Changing Modes
| Shortcut | Action |
|----------|--------|
| `<ESC>` | Exit from other modes into NORMAL mode |
| `i` / `I` | Enter INSERT mode (before current character / first character in line) |
| `a` / `A` | Enter INSERT mode (after current character / end of line) |
| `o` / `O` | Create empty line below/above cursor and enter INSERT mode |
| `v` | Enter Visual mode (character selection) |
| `V` | Enter Visual mode (line selection) |
| `<CTRL>-v` | Enter Visual mode (block selection) |
| `:` | Enter COMMAND-LINE mode |

### Normal Mode Basics
| Shortcut | Action |
|----------|--------|
| `J` | Join line at cursor with line below it |
| `u` | Undo last edit |
| `U` | Undo all changes on last edited line |
| `<CTRL>-r` | Redo (reverse the preceding undo) |
| `p` | Put (paste) |
| `ZZ` | Write file and exit |
| `.` | Repeat last change |

### Operators
| Shortcut | Action |
|----------|--------|
| `y` | Copy (Yank) |
| `c` | Change (delete and enter INSERT mode) |
| `d` | Delete |

### Motions
| Shortcut | Action |
|----------|--------|
| `w` / `W` | Start of next word/WORD |
| `b` / `B` | Start of previous word/WORD |
| `e` / `E` | End of next word/WORD |
| `ge` / `gE` | End of previous word/WORD |
| `0` or `<HOME>` | First character of line |
| `^` | First non-blank character of line |
| `$` | End of line |
| `f{char}` / `F{char}` | Forward/backward to character |
| `t{char}` / `T{char}` | Forward/backward until character (stops before) |
| `%` | Matching pair (parenthesis, brackets) |

### Cursor Movements
| Shortcut | Action |
|----------|--------|
| `h` or `<LEFT>` | Move left |
| `j` or `<DOWN>` | Move down |
| `k` or `<UP>` | Move up |
| `l` or `<RIGHT>` | Move right |
| `H` | First line on screen (High) |
| `M` | Middle line on screen |
| `L` | Last line on screen (Low) |

### Scrolling
| Shortcut | Action |
|----------|--------|
| `<CTRL>-u` | Scroll half page up |
| `<CTRL>-d` | Scroll half page down |
| `<CTRL>-y` | Scroll up one line |
| `<CTRL>-e` | Scroll down one line |
| `<CTRL>-b` | Scroll up one screen (minus 2 lines) |
| `<CTRL>-f` | Scroll down one screen (minus 2 lines) |
| `zt` | Move cursor line to top of screen |
| `zz` | Move cursor line to middle of screen |
| `zb` | Move cursor line to bottom of screen |

### Selection Objects
| Prefix + Object | Action |
|----------|--------|
| `i` / `a` + `w` | Inner/a word |
| `i` / `a` + `W` | Inner/a WORD (includes punctuation) |
| `i` / `a` + `s` | Inner/a sentence |
| `i` / `a` + `p` | Inner/a paragraph |
| `i` / `a` + `[` or `]` | Inner/a [] block |
| `i` / `a` + `(` or `)` or `b` | Inner/a () block |
| `i` / `a` + `<` or `>` | Inner/a <> block |
| `i` / `a` + `{` or `}` | Inner/a {} block |

### Common Shortcuts
| Shortcut | Action |
|----------|--------|
| `s` | Change one character |
| `x` | Delete character under cursor |
| `X` | Delete character left of cursor |
| `r{char}` | Replace character under cursor |
| `C` | Change to end of line |
| `D` | Delete to end of line |
| `yy` | Copy whole line |
| `cc` or `S` | Change whole line |
| `dd` | Delete whole line |

### Window Management
| Shortcut | Action |
|----------|--------|
| `<CTRL>-w w` | Jump between windows |
| `<CTRL>-w t` | Move to top window |
| `<CTRL>-w b` | Move to bottom window |
| `<CTRL>-w +` | Increase window size |
| `<CTRL>-w -` | Decrease window size |
| `<CTRL>-w h/j/k/l` | Navigate to window (left/down/up/right) |
| `<CTRL>-w H/J/K/L` | Move window (left/down/up/right) |
| `<CTRL>-w o` | Keep only current window (close others) |

### Visual Block Mode
| Shortcut | Action |
|----------|--------|
| `o` | Change cursor to other end of selection |
| `O` | Change corner in block selection |
| `I{string}<Esc>` | Insert text at left of block on each line |
| `A{string}<Esc>` | Insert text at right of block on each line |
| `C{string}<Esc>` | Delete block and enter insert mode |

### Operator+Motion Action Combinations
| Shortcut | Action |
|----------|--------|
| `dw` | Delete to next word |
| `d$` or `D` | Delete to end of line |
| `d0` | Delete to beginning of line |
| `diw` | Delete inner word |
| `di(` | Delete text inside () |
| `di{` | Delete text inside {} |
| `di[` | Delete text inside [] |
| `di"` | Delete text inside "" |
| `dip` | Delete inner paragraph |
| `cw` | Change to next word |
| `c$` or `C` | Change to end of line |
| `c0` | Change to beginning of line |
| `ciw` | Change inner word |
| `ci(` | Change text inside () |
| `ci{` | Change text inside {} |
| `ci[` | Change text inside [] |
| `ci"` | Change text inside "" |
| `cip` | Change inner paragraph |
| `yiw` | Yank (copy) inner word |
| `yi(` | Yank text inside () |
| `yi{` | Yank text inside {} |
| `yi[` | Yank text inside [] |
| `yi"` | Yank text inside "" |
| `yip` | Yank inner paragraph |

### Marks
| Shortcut | Action |
|----------|--------|
| `m{char}` | Set mark at cursor position (a-z for file-local, A-Z for global) |
| `` `{char}`` | Jump to position of mark |
| `'{char}` | Jump to line of mark |
| `` `. `` | Jump to position of last edit |
| `'.` | Jump to line of last edit |
| `` `0 `` | Jump to position where you last exited Vim |
| `` `"`` | Jump to position when you last edited this file |
| `` `[ `` | Jump to start of last yanked text |
| `` `] `` | Jump to end of last yanked text |
| `:marks` | List all marks |

### Folding
| Shortcut | Action |
|----------|--------|
| `zo` | Open fold |
| `zc` | Close fold |
| `za` | Toggle fold |
| `zR` | Open all folds |
| `zM` | Close all folds |
| `zj` | Move to next fold |
| `zk` | Move to previous fold |

### Macros
| Shortcut | Action |
|----------|--------|
| `q{char}` | Start recording macro into register {char} |
| `q` | Stop recording macro |
| `@{char}` | Execute macro in register {char} |
| `@@` | Repeat last executed macro |
| `{count}@{char}` | Execute macro {count} times |

### Search and Replace
| Shortcut | Action |
|----------|--------|
| `/{pattern}` | Search forward |
| `?{pattern}` | Search backward |
| `n` / `N` | Next/previous occurrence |
| `*` | Search forward for word under cursor |
| `#` | Search backward for word under cursor |
| `:s/from/to/[flags]` | Find and replace |

### Command-Line Mode
| Command | Action |
|---------|--------|
| `:edit filename` | Edit new file or load existing |
| `:q` | Quit |
| `:q!` | Quit without saving changes |
| `:w` | Save file |
| `:saveas filename` | Save as new filename |
| `:file filename` | Change current filename |
| `:s/from/to/[flags]` | Find and replace |

### Window Commands
| Command | Action |
|---------|--------|
| `:new` | Open window on new empty file (above) |
| `:split` | Split window horizontally |
| `:vsplit` | Split window vertically |
| `:close` | Close current window |
| `:only` | Close all windows except current |

Source:
- https://cheatography.com/marconlsantos/cheat-sheets/neovim/

## LazyVim Keyboard Shortcuts

### Navigation & Windows
| Key | Description | Mode |
|-----|-------------|------|
| `<C-h>` | Go to left window | n |
| `<C-j>` | Go to lower window | n |
| `<C-k>` | Go to upper window | n |
| `<C-l>` | Go to right window | n |
| `<C-Up>` | Increase window height | n |
| `<C-Down>` | Decrease window height | n |
| `<C-Left>` | Decrease window width | n |
| `<C-Right>` | Increase window width | n |
| `<A-j>` | Move down | n, i, v |
| `<A-k>` | Move up | n, i, v |
| `<leader>-` | Split window below | n |
| `<leader>\|` | Split window right | n |
| `<leader>wd` | Delete window | n |
| `<leader>wm` / `<leader>uZ` | Toggle zoom mode | n |
| `<leader>uz` | Toggle zen mode | n |

### Buffer Management
| Key | Description | Mode |
|-----|-------------|------|
| `<S-h>` / `[b` | Previous buffer | n |
| `<S-l>` / `]b` | Next buffer | n |
| `<leader>bb` / <code><leader>\`</code> | Switch to other buffer | n |
| `<leader>bd` | Delete buffer | n |
| `<leader>bo` | Delete other buffers | n |
| `<leader>bD` | Delete buffer and window | n |
| `<leader>bl` | Delete buffers to the left | n |
| `<leader>br` | Delete buffers to the right | n |
| `<leader>bp` | Toggle pin | n |
| `<leader>bP` | Delete non-pinned buffers | n |
| `[B` | Move buffer prev | n |
| `]B` | Move buffer next | n |

### Tab Management
| Key | Description | Mode |
|-----|-------------|------|
| `<leader><tab>l` | Last tab | n |
| `<leader><tab>f` | First tab | n |
| `<leader><tab><tab>` | New tab | n |
| `<leader><tab>]` | Next tab | n |
| `<leader><tab>[` | Previous tab | n |
| `<leader><tab>d` | Close tab | n |
| `<leader><tab>o` | Close other tabs | n |

### Search & Find
| Key | Description | Mode |
|-----|-------------|------|
| `<esc>` | Escape and clear hlsearch | i, n, s |
| `<leader>ur` | Redraw / Clear hlsearch / Diff update | n |
| `n` | Next search result | n, x, o |
| `N` | Prev search result | n, x, o |
| `<leader>/` | Grep (root dir) | n |
| `<leader>sg` | Grep (root dir) | n |
| `<leader>sG` | Grep (cwd) | n |
| `<leader>sw` | Search word (root dir) | n, x |
| `<leader>sW` | Search word (cwd) | n, x |
| `<leader>ss` | Goto symbol (aerial) | n |
| `<leader>sr` | Search and replace | n, v |

### File Operations
| Key | Description | Mode |
|-----|-------------|------|
| `<C-s>` | Save file | i, x, n, s |
| `<leader>fn` | New file | n |
| `<leader><space>` | Find files (root dir) | n |
| `<leader>ff` | Find files (root dir) | n |
| `<leader>fF` | Find files (cwd) | n |
| `<leader>fg` | Find files (git-files) | n |
| `<leader>fr` | Recent files | n |
| `<leader>fR` | Recent files (cwd) | n |
| `<leader>fc` | Find config file | n |

### Code Navigation & LSP
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>cl` | LSP info | n |
| `gd` | Goto definition | n |
| `gr` | References | n |
| `gI` | Goto implementation | n |
| `gy` | Goto type definition | n |
| `gD` | Goto declaration | n |
| `K` | Hover | n |
| `gK` | Signature help | n |
| `<c-k>` | Signature help | i |
| `<leader>ca` | Code action | n, v |
| `<leader>cc` | Run codelens | n, v |
| `<leader>cr` | Rename | n |
| `<leader>cR` | Rename file | n |
| `<leader>cf` | Format | n, v |
| `<leader>cF` | Format injected langs | n, v |
| `<leader>cd` | Line diagnostics | n |
| `]d` | Next diagnostic | n |
| `[d` | Prev diagnostic | n |
| `]e` | Next error | n |
| `[e` | Prev error | n |
| `]w` | Next warning | n |
| `[w` | Prev warning | n |
| `<leader>cs` | Symbols (trouble) | n |
| `<leader>cS` | LSP references (trouble) | n |

### Diagnostics & Trouble
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>xx` | Diagnostics (trouble) | n |
| `<leader>xX` | Buffer diagnostics (trouble) | n |
| `<leader>xL` | Location list (trouble) | n |
| `<leader>xQ` | Quickfix list (trouble) | n |
| `<leader>xl` | Location list | n |
| `<leader>xq` | Quickfix list | n |
| `[q` | Previous quickfix | n |
| `]q` | Next quickfix | n |

### Terminal
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>ft` | Terminal (root dir) | n |
| `<leader>fT` | Terminal (cwd) | n |
| `<c-/>` | Terminal (root dir) / Hide terminal | n, t |
| `<c-_>` | which_key_ignore | n, t |

### Git
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>gb` | Git blame line | n |
| `<leader>gB` | Git browse (open) | n, x |
| `<leader>gY` | Git browse (copy) | n, x |
| `<leader>gs` | Git status | n |
| `<leader>gS` | Git stash | n |
| `<leader>gd` | Git diff (hunks) | n |

### UI Toggles
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>uf` | Toggle auto format (global) | n |
| `<leader>uF` | Toggle auto format (buffer) | n |
| `<leader>us` | Toggle spelling | n |
| `<leader>uw` | Toggle wrap | n |
| `<leader>uL` | Toggle relative number | n |
| `<leader>ud` | Toggle diagnostics | n |
| `<leader>ul` | Toggle line numbers | n |
| `<leader>uc` | Toggle conceal level | n |
| `<leader>uA` | Toggle tabline | n |
| `<leader>uT` | Toggle treesitter highlight | n |
| `<leader>ub` | Toggle dark background | n |
| `<leader>uC` | Colorschemes | n |
| `<leader>uh` | Toggle inlay hints | n |

### Comments
| Key | Description | Mode |
|-----|-------------|------|
| `gco` | Add comment below | n |
| `gcO` | Add comment above | n |

### Debug
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>dpp` | Toggle profiler | n |
| `<leader>dph` | Toggle profiler highlights | n |
| `<leader>ui` | Inspect pos | n |
| `<leader>uI` | Inspect tree | n |
| `<leader>da` | Run with args | n |
| `<leader>db` | Toggle breakpoint | n |
| `<leader>dB` | Breakpoint condition | n |
| `<leader>dc` | Run/continue | n |
| `<leader>dC` | Run to cursor | n |
| `<leader>di` | Step into | n |
| `<leader>do` | Step out | n |
| `<leader>dO` | Step over | n |
| `<leader>dt` | Terminate | n |
| `<leader>du` | Dap UI | n |
| `<leader>de` | Eval | n, v |

### Extra Plugins
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>l` | Lazy | n |
| `<leader>L` | LazyVim changelog | n |
| `<leader>cm` | Mason | n |
| `<leader>qq` | Quit all | n |
| `<leader>sn` | +noice | n |
| `<leader>sna` | Noice all | n |
| `<leader>snd` | Dismiss all | n |
| `<leader>snh` | Noice history | n |
| `<leader>snl` | Noice last message | n |
| `<leader>snt` | Noice picker | n |
| `<leader>e` / `<leader>fe` | Explorer (root dir) | n |
| `<leader>E` / `<leader>fE` | Explorer (cwd) | n |

### Testing
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>t` | +test | n |
| `<leader>tr` | Run nearest (neotest) | n |
| `<leader>tl` | Run last (neotest) | n |
| `<leader>tt` | Run file (neotest) | n |
| `<leader>tT` | Run all test files (neotest) | n |
| `<leader>ts` | Toggle summary (neotest) | n |
| `<leader>to` | Show output (neotest) | n |
| `<leader>tO` | Toggle output panel (neotest) | n |
| `<leader>tS` | Stop (neotest) | n |
| `<leader>tw` | Toggle watch (neotest) | n |
| `<leader>td` | Debug nearest | n |

### Session Management
| Key | Description | Mode |
|-----|-------------|------|
| `<leader>qd` | Don't save current session | n |
| `<leader>ql` | Restore last session | n |
| `<leader>qs` | Restore session | n |
| `<leader>qS` | Select session | n |

Source:
- Default LazyVim keybindings (Modes: n=normal, i=insert, v=visual, x=visual line, s=select)

## Fish Shell fzf.fish Shortcuts

### Core Commands
| Shortcut | Action | Preview |
|----------|--------|---------|
| `Ctrl+Alt+F` | Search Directory | File with syntax highlighting |
| `Ctrl+Alt+L` | Search Git Log | Commit message and diff |
| `Ctrl+Alt+S` | Search Git Status | Git diff of the file |
| `Ctrl+R` | Search History | Command with syntax highlighting |
| `Ctrl+Alt+P` | Search Processes | CPU/memory usage and process info |
| `Ctrl+V` | Search Variables | Variable's scope info and values |

### Search Directory Features
- Directories inserted with trailing `/` for easy navigation
- If cursor is on a directory path with trailing slash (e.g., `.config/`), that directory is searched
- Ignores files that are also ignored by git
- Tab to select multiple files

### Search Git Log Features
- Shows formatted git log with commit hashes
- Preview window shows full commit message and diff
- Can be customized with `fzf_git_log_format` variable

### Search Git Status Features
- Shows modified, staged, and untracked files
- Preview window shows git diff of the file
- Helpful for quickly adding specific files to commits

### Search History Features
- Shows timestamp for each command
- Timestamp format customizable via `fzf_history_time_format`
- Preserves Fish syntax highlighting in preview

### Common fzf Navigation
| Shortcut | Action |
|----------|--------|
| `↑` / `↓` or `Ctrl+P` / `Ctrl+N` | Navigate up/down in results |
| `Enter` | Select current item and exit |
| `Tab` | Select multiple items |
| `Shift+Tab` | Deselect item |
| `Ctrl+Space` | Toggle selection |
| `Alt+Enter` | Select all matches |
| `Esc` | Exit without selecting |
| `Alt+↑` / `Alt+↓` | Scroll preview window up/down |
| `Ctrl+/` | Toggle help menu |
| `Ctrl+R` | Toggle sort order |
| `Alt+W` | Toggle preview wrap |

### Configuration Options
To customize key bindings, use the `fzf_configure_bindings` function in your `config.fish`:
```fish
# Example: Disable history search and use different key for directory search
fzf_configure_bindings --history= --directory=\e\cf
```

Source:
- fzf.fish plugin documentation

## VSCode Neovim Integration

### Navigation and Editing
| Mode | Shortcut | Action |
|------|----------|--------|
| Normal | `hjkl` | Basic movement |
| Normal | `w` / `b` / `e` | Word navigation |
| Normal | `0` / `^` / `$` | Line navigation |
| Normal | `gg` / `G` | Document start/end |
| Normal | `{` / `}` | Paragraph navigation |
| Normal | `<C-u>` / `<C-d>` | Half page up/down |
| Normal | `<C-f>` / `<C-b>` | Full page up/down |
| Normal | `zz` / `zt` / `zb` | Center/top/bottom view |
| Insert | `<C-o>` | Run one normal mode command |
| Normal | `i` / `a` / `I` / `A` | Enter insert mode |
| Visual | `v` / `V` / `<C-v>` | Visual selections |

### Code Navigation
| Mode | Shortcut | Action |
|------|----------|--------|
| Normal | `gd` | Go to definition |
| Normal | `gD` | Peek definition |
| Normal | `gf` | Go to declaration |
| Normal | `gH` | Find all references |
| Normal | `gh` / `K` | Show hover |
| Normal | `<C-w>gd` | Open definition aside |
| Normal | `gO` | Go to symbol |
| Normal | `<C-n>` / `<C-p>` | Navigate suggestion lists |

### File/Buffer Management
| Mode | Shortcut | Action |
|------|----------|--------|
| Normal | `:e {file}` | Edit file |
| Normal | `:w` | Save file |
| Normal | `:q` | Close editor |
| Normal | `<leader>ff` | Find files |
| Normal | `<leader>fg` | Find in git files |
| Normal | `<leader>sg` | Search in files |
| Normal | `<C-w>s` / `:split` | Split horizontally |
| Normal | `<C-w>v` / `:vsplit` | Split vertically |
| Normal | `<C-w>h/j/k/l` | Navigate splits |
| Normal | `<C-w>o` / `:only` | Keep only current window |

### Window/Tab Management
| Mode | Shortcut | Action |
|------|----------|--------|
| Normal | `:tabnew` | New tab |
| Normal | `gt` / `gT` | Next/previous tab |
| Normal | `:tabc` | Close tab |
| Normal | `<C-w>+` / `<C-w>-` | Resize height |
| Normal | `<C-w>>` / `<C-w><` | Resize width |
| Normal | `<C-Up/Down/Left/Right>` | Resize panes |

### Multiple Cursors
| Mode | Shortcut | Action |
|------|----------|--------|
| Visual Line | `ma` / `mA` | Add cursor at end of each line |
| Visual Line | `mi` / `mI` | Add cursor at start of each line |
| Visual Block | `ma` | Add cursor after block |
| Visual Block | `mi` | Add cursor before block |
| Insert | `<C-v>` passthrough | Use VSCode multi-cursor |

### Code Actions and Formatting
| Mode | Shortcut | Action |
|------|----------|--------|
| Normal/Visual | `=` | Format selection |
| Normal | `==` | Format line |
| Normal | `<leader>ca` | Code actions |
| Normal | `<leader>cr` | Rename symbol |
| Normal | `<leader>cf` | Format file |

### Explorer Navigation
| Mode | Shortcut | Action |
|------|----------|--------|
| Normal | `j` / `k` | Move up/down |
| Normal | `h` / `l` | Collapse/expand |
| Normal | `Enter` | Open file |
| Normal | `o` | Toggle expand |
| Normal | `a` / `A` | New file/folder |
| Normal | `r` | Rename |
| Normal | `d` | Delete |
| Normal | `y` / `x` / `p` | Copy/cut/paste |

Source:
- VSCodeVim/Neovim extension documentation
