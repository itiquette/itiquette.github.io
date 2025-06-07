+++
title = 'Shortcuts Workflow'
#date = 2024-01-14T07:07:07+01:00
draft = false
type = 'page'
slug = 'shortcutsworkflow'
hideDate = 'true'
+++

# Condensed Shortcut Reference

A condensed overview of the [more common shortcuts](shortcutsall.md) across Ubuntu, terminal multiplexers, shell environments, code editors, browsers, and development tools.
Under constant change:)

## Table of Contents

- [System Environment (Ubuntu/GNOME)](#system-environment-ubuntugnome)
- [Terminal Multiplexer (Zellij)](#terminal-multiplexer-zellij)
- [Fish Shell with Vim Mode](#fish-shell-with-vim-mode)
- [Fish Shell with fzf.fish](#fish-shell-with-fzffish)
- [Neovim/LazyVim](#neovimlazyvim)
- [VSCode with Neovim Extension](#vscode-with-neovim-extension)
- [Browser Navigation with Vimium](#browser-navigation-with-vimium)
- [Browser Developer Tools](#browser-developer-tools)

## System Environment (Ubuntu/GNOME)

### Window Management

| Shortcut | Action |
|----------|--------|
| `Super` | Activities overview |
| `Super+A` | Applications menu |
| `Ctrl+Alt+T` | Open terminal |
| `Alt+F4` or `Ctrl+Q` | Close window |
| `Super+Left/Right/Up/Down` | Snap window left/right/maximize/unmaximize |
| `Alt+Tab` (Alt+Shift+Tab) | Switch application window |
| `Super+Tab` (Super+Shift+Tab) | Switch application group|
| `Alt+F6` | Switch windows of the same application |
| Ctrl+Alt+D | Show desktop |
| `Super+M` | Toggle notification panel |
| `Super+L` | Lock screen |
| `Ctrl+Alt+Del` | Log out |

### Workspace Navigation

| Shortcut | Action |
|----------|--------|
| `Ctrl+Alt+Up/Down/Left/Right` | Switch workspace |
| `Shift+Ctrl+Alt+Up/Down/Left/Right` | Move window to workspace |

### Utility

| Shortcut | Action |
|----------|--------|
| `PrtScr` | Take screenshot of area |
| `Alt+PrtScr` | Take screenshot of window |
| `Shift+PrtScr` | Take screenshot of desktop |

## Terminal Multiplexer (Zellij)

### Shared Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+q` | Quit |
| `Alt+f` | Toggle floating panes |
| `Alt+n` | New pane |
| `Alt+h/j/k/l` | Move focus left/down/up/right |
| `Alt+=` or `Alt++` | Increase size |
| `Alt+-` | Decrease size |
| `Alt+[ or Alt+]` | Previous/next layout |
| `Alt+i/o` | Move tab left/right |
| `Shift` | Hold to bypass Zellij mouse override |

### Mode Switching

| Shortcut | Action |
|----------|--------|
| `Ctrl+g` | Switch to Locked mode (for using ctrl n p in FZF etc)|
| `Ctrl+p` | Switch to Pane mode |
| `Ctrl+t` | Switch to Tab mode |
| `Ctrl+n` | Switch to Resize mode |
| `Ctrl+s` | Switch to Scroll mode |
| `Ctrl+o` | Switch to Session mode |
| `Ctrl+h` | Switch to Move mode |
| `Ctrl+b` | Switch to Tmux mode |
| `Enter/Esc` | Return to Normal mode (from most modes) |

### Pane Management (Pane Mode - `Ctrl+p` first)

| Shortcut | Action |
|----------|--------|
| `h/j/k/l` or `Left/Down/Up/Right` | Move focus |
| `p` | Switch focus |
| `n` | New pane |
| `d` | New pane downward |
| `r` | New pane rightward |
| `x` | Close focused pane |
| `f` | Toggle fullscreen |
| `z` | Toggle pane frames |
| `w` | Toggle floating panes |
| `e` | Toggle pane embed/floating |
| `c` | Rename pane |
| `i` | Toggle pane pinned |

### Tab Management (Tab Mode - `Ctrl+t` first)

| Shortcut | Action |
|----------|--------|
| `h/l` or `Left/Right` | Previous/next tab |
| `n` | New tab |
| `x` | Close tab |
| `r` | Rename tab |
| `s` | Toggle sync |
| `1-9` | Go to tab 1-9 |
| `Tab` | Toggle tab |

### Resize Mode (`Ctrl+n` first)

| Shortcut | Action |
|----------|--------|
| `h/j/k/l` | Increase size left/down/up/right |
| `H/J/K/L` | Decrease size left/down/up/right |
| `=` or `+` | Increase size |
| `-` | Decrease size |

### Scrollback & Search (Scroll Mode - `Ctrl+s` first)

| Shortcut | Action |
|----------|--------|
| `j/k` or `Down/Up` | Scroll down/up |
| `Ctrl+f`/`Ctrl+b` or `Page Down/Up` | Page scroll down/up |
| `d/u` | Half page scroll down/up |
| `e` | Edit scrollback (the way of copy a listing in zellij) |
| `s` | Enter search mode |
| `n/p` | Search next/previous |
| `c` | Toggle case sensitivity |
| `w` | Toggle wrap |
| `o` | Toggle whole word |

## Fish Shell with Vim Mode

### Mode Switching

| Shortcut | Action |
|----------|--------|
| `Escape` | Enter normal mode |
| `i` | Enter insert mode |
| `a` | Enter insert mode (after cursor) |
| `A` | Enter insert mode (end of line) |

### Navigation in Normal Mode

| Shortcut | Action |
|----------|--------|
| `h/j/k/l` | Move cursor left/down/up/right |
| `0/^` | Move to start of line/first non-blank |
| `$` | Move to end of line |
| `w/b` | Move forward/backward one word |
| `e/ge` | Move to end of word/previous end of word |
| `fx/Fx` | Move to next/previous occurrence of x |
| `tx/Tx` | Move to before next/previous occurrence of x |

### Editing in Normal Mode

| Shortcut | Action |
|----------|--------|
| `dd` | Delete entire line |
| `dw` | Delete word |
| `d$` | Delete to end of line |
| `cc` | Change entire line |
| `cw` | Change word |
| `c$` | Change to end of line |
| `yy` | Yank (copy) line |
| `yw` | Yank word |
| `p/P` | Paste after/before cursor |
| `u` | Undo |
| `r` | Replace character |
| `x` | Delete character |
| `~` | Change case |

### Command History (Default Mode)

| Shortcut | Action |
|----------|--------|
| `k` | Previous command |
| `j` | Next command |
| `Ctrl+r` | Reverse search through history |

### Line Editing (Emacs Mode)

| Shortcut | Action |
|----------|--------|
| `Ctrl+a` | Move to beginning of line |
| `Ctrl+e` | Move to end of line |
| `Alt+f` | Move forward one word |
| `Alt+b` | Move backward one word |
| `Ctrl+u` | Delete from cursor to beginning of line |
| `Ctrl+k` | Delete from cursor to end of line |
| `Ctrl+w` | Delete previous word |
| `Alt+d` | Delete next word |
| `Alt+t` | Swap two words |
| `Ctrl+l` | Clear screen |
| `Ctrl+c` | Cancel command |
| `Ctrl+z` | Suspend process |

## Fish Shell with fzf.fish

### Core Commands

| Shortcut | Action | Description |
|----------|--------|-------------|
| `Ctrl+Alt+f/F` | Search Directory | Find files in current directory |
| `Ctrl+Alt+l` | Search Git Log | Browse and insert commit hashes |
| `Ctrl+Alt+s` | Search Git Status | Find modified/staged/untracked files |
| `Ctrl+s` | Search History | Find commands in shell history |
| `Ctrl+Alt+p` | Search Processes | Find and insert process IDs |
| `Ctrl+v` | Search Variables | Find and insert shell variables |

### fzf Navigation

| Shortcut | Action |
|----------|--------|
| `Ctrl+k/j` | Navigate up/down |
| `Enter` | Select item |
| `Tab` | Select multiple items |
| `Shift+Tab` | Deselect item |
| `Esc` or `Ctrl+g` | Cancel |

## Neovim/LazyVim

### Basic Movement

| Shortcut | Action |
|----------|--------|
| `h/j/k/l` | Move cursor left/down/up/right |
| `w/W` | Move to next word/WORD start |
| `e/E` | Move to next word/WORD end |
| `b/B` | Move to previous word/WORD start |
| `ge/gE` | Move to previous word/WORD end |
| `0/$` | Move to start/end of line |
| `^` | Move to first non-blank character |
| `gg/G` | Move to first/last line |
| `{/}` | Move to previous/next paragraph |
| `Ctrl+u/d` | Scroll half-page up/down |
| `Ctrl+b/f` | Scroll page up/down |
| `Ctrl+y/e` | Scroll one line up/down |
| `zz/zt/zb` | Center/top/bottom current line |
| `H/M/L` | Move to top/middle/bottom of screen |
| `fx/Fx` | Move to next/previous 'x' |
| `tx/Tx` | Move till before next/previous 'x' |
| `;/,` | Repeat last f/F/t/T forward/backward |
| `%` | Jump to matching brace |
| `yl` | Yank a char |

### Editing

| Shortcut | Action |
|----------|--------|
| `i/I` | Insert before cursor/at line start |
| `a/A` | Insert after cursor/at line end |
| `o/O` | Open line below/above |
| `r/R` | Replace character/enter replace mode |
| `c{motion}` | Change text |
| `cc` | Change line |
| `C` | Change to end of line |
| `d{motion}` | Delete text |
| `dd` | Delete line |
| `D` | Delete to end of line |
| `x/X` | Delete character under/before cursor |
| `y{motion}` | Yank (copy) text |
| `yy` or `Y` | Yank line |
| `p/P` | Paste after/before cursor |
| `J` | Join lines |
| `u/Ctrl+r` | Undo/redo |
| `.` | Repeat last change |
| `~` | Toggle case |
| `g~/gu/gU` | Toggle/lower/upper case |
| `==` | Auto-indent current line |
| `=G` | Auto-indent from cursor to end of file |
| `gg=G` | Auto-indent entire file (go to top, then indent to end) |

### Text Objects

| Shortcut | Action |
|----------|--------|
| `iw/aw` | Inner/a word |
| `iW/aW` | Inner/a WORD |
| `is/as` | Inner/a sentence |
| `ip/ap` | Inner/a paragraph |
| `i"/a"` | Inner/a double quoted string |
| `i'/a'` | Inner/a single quoted string |
| `i(/a(` or `ib/ab` | Inner/a parentheses block |
| `i[/a[` | Inner/a bracket block |
| `i{/a{` or `iB/aB` | Inner/a brace block |
| `i</a<` | Inner/a angle bracket block |
| `it/at` | Inner/a tag block |

### Visual Mode

| Shortcut | Action |
|----------|--------|
| `v/V/Ctrl+v` | Start character/line/block selection |
| `o/O` | Move to other end of selection/other corner |
| `=` | Auto-indent selection |
| `y/d/c/x` | Yank/delete/change/delete selection |
| `u/U` | Change selection to lowercase/uppercase |
| `I/A` | Insert at start/end of all selected lines (in block mode) |

### Search and Replace

| Shortcut | Action |
|----------|--------|
| `/pattern` | Search forward |
| `?pattern` | Search backward |
| `n/N` | Next/previous match |
| `*/＃` | Search word under cursor forward/backward |
| `:%s/old/new/g` | Replace all occurrences |
| `:s/old/new/g` | Replace in current line |
| `:%s/old/new/gc` | Replace all with confirmation |
| `gd/gD` | Go to local/global definition |

### Marks and Jumps

| Shortcut | Action |
|----------|--------|
| `m{a-zA-Z}` | Set mark |
| `` `{mark} `` | Jump to mark position |
| `'{mark}` | Jump to mark line |
| `` `. `` | Jump to position of last change |
| `Ctrl+o/i` | Go to older/newer position in jump list |
| `g;/g,` | Go to older/newer position in change list |

### Window Management

| Shortcut | Action |
|----------|--------|
| `Ctrl+w v` | Split window vertically |
| `Ctrl+w s` | Split window horizontally |
| `Ctrl+w q` | Close window |
| `Ctrl+w o` | Close all windows except current |
| `Ctrl+w h/j/k/l` | Move to left/down/up/right window |
| `Ctrl+w H/J/K/L` | Move window left/down/up/right |
| `Ctrl+w r/R` | Rotate windows down/up |
| `Ctrl+w =` | Equal dimensions for all windows |
| `Ctrl+w T` | Move window to new tab |

### Tab Management

| Shortcut | Action |
|----------|--------|
| `:tabnew` | Create new tab |
| `:tabedit {file}` | Edit file in new tab |
| `:tabclose` | Close current tab |
| `:tabonly` | Close all tabs except current |
| `gt/gT` | Go to next/previous tab |
| `{n}gt` | Go to tab n |
| `:tabs` | List all tabs |

### File Operations

| Shortcut | Action |
|----------|--------|
| `:e {file}` | Edit file |
| `:w` | Write (save) file |
| `:wa` | Write all files |
| `:q` | Quit |
| `:qa` | Quit all |
| `:wq` or `:x` or `ZZ` | Write and quit |
| `:q!` or `ZQ` | Quit without saving |
| `:saveas {file}` | Save as |
| `:r {file}` | Read file into buffer |
| `:r !{cmd}` | Read command output into buffer |

### Code Navigation (LazyVim)

| Shortcut | Action |
|----------|--------|
| `gd` | Go to definition |
| `gr` | Go to references |
| `gI` | Go to implementation |
| `gy` | Go to type definition |
| `gD` | Go to declaration |
| `K` | Show hover documentation |
| `gK` | Show signature help |
| `<leader>ca` | Code action |
| `<leader>cf` | Format code |
| `<leader>cr` | Rename symbol |
| `<leader>cd` | Line diagnostics |
| `]d/[d` | Next/previous diagnostic |
| `]e/[e` | Next/previous error |
| `]w/[w` | Next/previous warning |

### Fuzzy Finding (LazyVim)

| Shortcut | Action |
|----------|--------|
| `<leader><space>` | Find files |
| `<leader>ff` | Find files |
| `<leader>fg` | Find in git files |
| `<leader>fr` | Recent files |
| `<leader>/` | Grep in files |
| `<leader>sg` | Grep in files |
| `<leader>ss` | Go to symbol |
| `<leader>sw` | Search word under cursor |

### Git Integration (LazyVim)

| Shortcut | Action |
|----------|--------|
| `<leader>gb` | Git blame |
| `<leader>gs` | Git status |
| `<leader>gd` | Git diff |
| `<leader>gS` | Git stash |

### Buffer Management (LazyVim)

| Shortcut | Action |
|----------|--------|
| `<S-h>/<S-l>` | Previous/next buffer |
| `<leader>bb` | Switch buffer |
| `<leader>bd` | Delete buffer |
| `<leader>bo` | Delete other buffers |
| `<leader>bl` | Delete buffers to the left |
| `<leader>br` | Delete buffers to the right |
| `<leader>bp` | Toggle pin buffer |

### UI Toggles (LazyVim)

| Shortcut | Action |
|----------|--------|
| `<leader>uf` | Toggle format on save |
| `<leader>us` | Toggle spelling |
| `<leader>uw` | Toggle word wrap |
| `<leader>ul` | Toggle line numbers |
| `<leader>ud` | Toggle diagnostics |
| `<leader>uc` | Toggle conceal |
| `<leader>ub` | Toggle background |

### Terminal (LazyVim)

| Shortcut | Action |
|----------|--------|
| `<leader>ft` | Terminal (root dir) |
| `<leader>fT` | Terminal (cwd) |
| `<C-/>` | Terminal |

## VSCode with Neovim Extension

### VSCode-Specific Navigation

| Shortcut | Action |
|----------|--------|
| `gd` | Go to definition |
| `gD` | Peek definition |
| `gf` | Go to declaration |
| `gH` | Find references |
| `gh/K` | Show hover |
| `<C-w>gd` | Open definition aside |
| `gO` | Go to symbol |

### File/Buffer Management

| Shortcut | Action |
|----------|--------|
| `:e {file}` | Edit file |
| `:w` | Save file |
| `:q` | Close editor |
| `<C-w>s/:split` | Split horizontally |
| `<C-w>v/:vsplit` | Split vertically |
| `<C-w>h/j/k/l` | Navigate splits |
| `<C-w>o/:only` | Keep only current window |

### Code Actions & Formatting

| Shortcut | Action |
|----------|--------|
| `Ctrl+.` | Code actions |
| `F2` | Rename symbol |
| `Shift+Alt+F` | Format file |

### Vim Shortcut Alternatives to Multi-Cursor

| Shortcut | Action |
|----------|--------|
| `*` | Search for word under cursor |
| `cgn` | Change next occurrence |
| `.` | Repeat last change |
| `n` | Skip to next occurrence |
| `N` | Skip to previous occurrence |
| `:%s/old/new/gc` | Global search & replace with confirmation |
| `:%s/old/new/g` | Global search & replace (no confirmation) |
| `/pattern` | Search for pattern |
| `?pattern` | Search backwards for pattern |

### VSCode Native Features

| Shortcut | Action |
|----------|--------|
| `F5` | Start debugging |
| `F9` | Toggle breakpoint |
| `F10` | Step over |
| `F11/Shift+F11` | Step into/out |
| `Ctrl+Shift+`` | Toggle terminal |
| `Ctrl+Shift+E` | Show explorer |
| `Ctrl+Shift+G` | Show source control |
| `Ctrl+Shift+D` | Show debug panel |
| `Ctrl+Shift+X` | Show extensions |
| `Ctrl+P` | Quick open files |
| `Ctrl+Shift+P` | Show command palette |

### Explorer Navigation

| Shortcut | Action |
|----------|--------|
| `j/k` | Move up/down |
| `h/l` | Collapse/expand |
| `Enter` | Open file |
| `Space` | Preview file (keep focus in explorer) |
| `a/A` | New file/folder |
| `r` | Rename |
| `d` | Delete |
| `y/x/p` | Copy/cut/paste |

### General Panel Navigation

| Shortcut | Action |
|----------|--------|
| `Ctrl+0` | Focus on sidebar |
| `Ctrl+1` | Focus back to editor |

## Browser Navigation with Vimium

### Basic Navigation

| Shortcut | Action |
|----------|--------|
| `j/k` | Scroll down/up |
| `h/l` | Scroll left/right |
| `gg/G` | Scroll to top/bottom |
| `d/u` | Scroll half page down/up |
| `r` | Reload page |
| `yy` | Copy URL |
| `p/P` | Open clipboard URL in current/new tab |

### Link Navigation

| Shortcut | Action |
|----------|--------|
| `f` | Show link hints (current tab) |
| `F` | Show link hints (new tab) |
| `[[/]]` | Navigate to previous/next page |
| `gf` | Cycle focus through frames |

### Tab Management

| Shortcut | Action |
|----------|--------|
| `Ctrl+Tab` / `Ctrl+Shift+Tab` | Go to previous/next tab |
| `g0/g$ or Alt+9` | Go to first/last tab |
| `Ctrl+t` | Create new tab |
| `Ctrl+W` | Close tab |
| `T` | Search tabs |

### History Navigation

| Shortcut | Action |
|----------|--------|
| `H/L` | Go back/forward in history |

### Visual Mode

| Shortcut | Action |
|----------|--------|
| `v` | Enter visual mode |
| `V` | Enter visual line mode |
| `y` | Copy selected text (in visual mode) |

### Search

| Shortcut | Action |
|----------|--------|
| `/` | Enter find mode |
| `n/N` | Find next/previous match |

### Misc

| Shortcut | Action |
|----------|--------|
| `i` | Enter insert mode (disable Vimium) |
| `gi` | Focus first text input |
| `gs` | View source |
| `?` | Show help |

## Browser Developer Tools

### Navigation

| Shortcut | Action |
|----------|--------|
| `Ctrl+Shift+I` | Toggle DevTools |
| `Ctrl+Shift+K` | Console |
| `Ctrl+Shift+C` | Inspect element |
| `Ctrl+]` / `Ctrl+[` | Navigate forward/back in panel history |
| `Ctrl+Shift+M` | Toggle device mode |

### Debugging

| Shortcut | Action |
|----------|--------|
| `F8` or `Ctrl+\` | Pause/resume |
| `F10` or `Ctrl+'` | Step over |
| `F11` or `Ctrl+;` | Step into |
| `Shift+F11` or `Ctrl+Shift+;` | Step out |

### Console

| Shortcut | Action |
|----------|--------|
| `Ctrl+L` | Clear console |
| `Up/Down` | Navigate command history |
| `Shift+Enter` | Multi-line entry |
| `Esc` | Toggle console drawer |
