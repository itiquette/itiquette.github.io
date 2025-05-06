+++
title = 'Tangentbordsgenvägar (alla)'
#date = 2024-01-14T07:07:07+01:00
draft = false
type = 'page'
slug = 'shortcutsall'
+++

Guide till tangentbordsgenvägar för Linux och utvecklarverktyg

## Innehållsförteckning

- [Viktiga Ubuntu (Gnome) tangentbordsgenvägar](#viktiga-ubuntu-gnome-tangentbordsgenvägar)
- [Zellij tangentbordsgenvägar](#zellij-tangentbordsgenvägar)
- [Vim-läge i Fish Shell](#vim-läge-i-fish-shell)
- [Standardläge i Fish Shell](#standardläge-i-fish-shell)
- [Webbläsargenvägar](#webbläsargenvägar)
- [Vimium webbläsartillägg genvägar](#vimium-webbläsartillägg-genvägar)
- [VS Code tangentbordsgenvägar](#vs-code-tangentbordsgenvägar)
- [NeoVim tangentbordsgenvägar](#neovim-tangentbordsgenvägar)
- [LazyVim tangentbordsgenvägar](#lazyvim-tangentbordsgenvägar)
- [Fish Shell fzf.fish genvägar](#fish-shell-fzffish-genvägar)
- [VSCode Neovim-integration](#vscode-neovim-integration)

## Viktiga Ubuntu (Gnome) tangentbordsgenvägar

| Genväg | Åtgärd |
|----------|--------|
| `Super` | Öppnar aktivitetssökning |
| `Super+A` | Visa programmenyn (9 punkters rutnät) |
| `Ctrl+Alt+T` | Öppna terminalfönster |
| `Ctrl+Q` eller `Ctrl+W` eller `Alt+F4` | Stäng programfönster |
| `Super+Vänster/Höger/Upp/Ner` | Fäst fönster vänster/höger/maximera/minimera |
| `Alt+Tab` (Alt+Shift+Tab) | Växla programfönster |
| `Super+Tab` (Super+Shift+Tab) | Växla programgrupp |
| `Ctrl+Alt+Tab` | Växla mellan fönster i alla arbetsytor (osäker på denna todo) |
| `Ctrl+Alt+Upp/Ner/Vänster/Höger` | Växla arbetsyta |
| `Alt+F6` | Snabbväxla fönster i samma program |
| Ctrl+Alt+D` | Visa skrivbord (tryck igen för att återställa fönster) |
| `Super+M` | Växla notiseringsrad |
| `Ctrl+Alt+L` | Lås skärmen |
| `Ctrl+Alt+Del` | Logga ut |
| `Alt+F2` | Kör konsol (kommandoprompt) |
| `Ctrl+Alt+Upp/Ner/Vänster/Höger` | Växla arbetsyta |
| `Shift+Ctrl+Alt+Upp/Ner/Vänster/Höger` | Flytta fönster till arbetsyta |
| `PrtScr` | Ta skärmdump |
| `Alt+PrtScr` | Ta skärmdump av fönster |
| `Shift+PrtScr` | Ta skärmdump av område |

> 📋 Obs: Versaler i genvägar betyder inte att du trycker på Shift-tangenten. Till exempel betyder T endast 't'-tangenten, inte Shift+t.
>
### Anpassade tangentbordsgenvägar

Skapa dina egna genvägar genom att gå till:
Inställningar → Enheter → Tangentbord → Anpassade genvägar
Källor:

- <https://itsfoss.com/ubuntu-shortcuts/>

## Zellij tangentbordsgenvägar

### Låst läge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl g` | Växla till normalläge |

### Normalläge

Normalläge är standardläget i Zellij.

### Storleksändringsläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl n` | Växla till normalläge |
| `h` / `←` | Öka storlek vänster |
| `j` / `↓` | Öka storlek nedåt |
| `k` / `↑` | Öka storlek uppåt |
| `l` / `→` | Öka storlek höger |
| `H` | Minska storlek vänster |
| `J` | Minska storlek nedåt |
| `K` | Minska storlek uppåt |
| `L` | Minska storlek höger |
| `=` / `+` | Öka storlek |
| `-` | Minska storlek |

### Panelläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl p` | Växla till normalläge |
| `h` / `←` | Flytta fokus vänster |
| `l` / `→` | Flytta fokus höger |
| `j` / `↓` | Flytta fokus nedåt |
| `k` / `↑` | Flytta fokus uppåt |
| `p` | Växla fokus |
| `n` | Ny panel och växla till normalläge |
| `d` | Ny panel nedåt och växla till normalläge |
| `r` | Ny panel höger och växla till normalläge |
| `x` | Stäng fokuserad panel och växla till normalläge |
| `f` | Växla fullskärm för fokuserad panel och växla till normalläge |
| `z` | Växla panelramar och växla till normalläge |
| `w` | Växla flytande paneler och växla till normalläge |
| `e` | Växla panel inbäddad/flytande och växla till normalläge |
| `c` | Växla till namnändringläge för panel med panelnamninmatning |
| `i` | Växla panel nålad och växla till normalläge |

### Flyttläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl h` | Växla till normalläge |
| `n` / `Tab` | Flytta panel |
| `p` | Flytta panel bakåt |
| `h` / `←` | Flytta panel vänster |
| `j` / `↓` | Flytta panel nedåt |
| `k` / `↑` | Flytta panel uppåt |
| `l` / `→` | Flytta panel höger |

### Flikläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl t` | Växla till normalläge |
| `r` | Växla till namnändringsläge för flik med fliknamninmatning |
| `h` / `←` / `↑` / `k` | Gå till föregående flik |
| `l` / `→` / `↓` / `j` | Gå till nästa flik |
| `n` | Ny flik och växla till normalläge |
| `x` | Stäng flik och växla till normalläge |
| `s` | Växla aktiv synkflik och växla till normalläge |
| `b` | Bryt panel och växla till normalläge |
| `]` | Bryt panel höger och växla till normalläge |
| `[` | Bryt panel vänster och växla till normalläge |
| `1`-`9` | Gå till flik 1-9 och växla till normalläge |
| `Tab` | Växla flik |

### Rullningsläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl s` | Växla till normalläge |
| `e` | Redigera rullningsbakåt och växla till normalläge |
| `s` | Växla till sökinmatningsläge med sökinmatning |
| `Ctrl c` | Rulla till botten och växla till normalläge |
| `j` / `↓` | Rulla nedåt |
| `k` / `↑` | Rulla uppåt |
| `Ctrl f` / `PageDown` / `→` / `l` | Sid-rulla nedåt |
| `Ctrl b` / `PageUp` / `←` / `h` | Sid-rulla uppåt |
| `d` | Halv sida rulla nedåt |
| `u` | Halv sida rulla uppåt |

### Sökläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl s` | Växla till normalläge |
| `Ctrl c` | Rulla till botten och växla till normalläge |
| `j` / `↓` | Rulla nedåt |
| `k` / `↑` | Rulla uppåt |
| `Ctrl f` / `PageDown` / `→` / `l` | Sid-rulla nedåt |
| `Ctrl b` / `PageUp` / `←` / `h` | Sid-rulla uppåt |
| `d` | Halv sida rulla nedåt |
| `u` | Halv sida rulla uppåt |
| `n` | Sök nedåt |
| `p` | Sök uppåt |
| `c` | Växla skiftlägeskänslighet |
| `w` | Växla radbrytningsalternativ |
| `o` | Växla hela ord-alternativ |

### Sökinmatningsläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl c` / `Esc` | Växla till rullningsläge |
| `Enter` | Växla till sökläge |

### Namnändringsläge för flik

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl c` | Växla till normalläge |
| `Esc` | Ångra namnändring av flik och växla till flikläge |

### Namnändringsläge för panel

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl c` | Växla till normalläge |
| `Esc` | Ångra namnändring av panel och växla till panelläge |

### Sessionsläge

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl o` | Växla till normalläge |
| `Ctrl s` | Växla till rullningsläge |
| `d` | Koppla från |
| `w` | Starta eller fokusera sessionshanterarpluginet och växla till normalläge |
| `c` | Starta eller fokusera konfigurationspluginet och växla till normalläge |
| `p` | Starta eller fokusera pluginhanteraren och växla till normalläge |
| `a` | Starta eller fokusera om-pluginet och växla till normalläge |

### Tmux-läge

| Genväg | Åtgärd |
|----------|--------|
| `[` | Växla till rullningsläge |
| `Ctrl b` | Skriv 2 och växla till normalläge |
| `"` | Ny panel nedåt och växla till normalläge |
| `%` | Ny panel höger och växla till normalläge |
| `z` | Växla fullskärmsfokus och växla till normalläge |
| `c` | Ny flik och växla till normalläge |
| `,` | Växla till namnändringsläge för flik |
| `p` | Gå till föregående flik och växla till normalläge |
| `n` | Gå till nästa flik och växla till normalläge |
| `Left` / `h` | Flytta fokus vänster och växla till normalläge |
| `Right` / `l` | Flytta fokus höger och växla till normalläge |
| `Down` / `j` | Flytta fokus nedåt och växla till normalläge |
| `Up` / `k` | Flytta fokus uppåt och växla till normalläge |
| `o` | Fokusera nästa panel |
| `d` | Koppla från |
| `Space` | Nästa layoutbyte |
| `x` | Stäng fokus och växla till normalläge |

### Delade genvägar

| Genväg | Åtgärd | Tillgänglig i |
|----------|--------|-------------|
| `Ctrl g` | Växla till låst läge | Alla utom låst |
| `Ctrl q` | Avsluta | Alla utom låst |
| `Alt f` | Växla flytande paneler | Alla utom låst |
| `Alt n` | Ny panel | Alla utom låst |
| `Alt i` | Flytta flik vänster | Alla utom låst |
| `Alt o` | Flytta flik höger | Alla utom låst |
| `Alt h` / `Alt ←` | Flytta fokus eller flik vänster | Alla utom låst |
| `Alt l` / `Alt →` | Flytta fokus eller flik höger | Alla utom låst |
| `Alt j` / `Alt ↓` | Flytta fokus nedåt | Alla utom låst |
| `Alt k` / `Alt ↑` | Flytta fokus uppåt | Alla utom låst |
| `Alt =` / `Alt +` | Öka storlek | Alla utom låst |
| `Alt -` | Minska storlek | Alla utom låst |
| `Alt [` | Föregående layoutbyte | Alla utom låst |
| `Alt ]` | Nästa layoutbyte | Alla utom låst |
| `Enter` / `Esc` | Växla till normalläge | Alla utom normal och låst |

### Lägesväxlingsgenvägar

| Genväg | Åtgärd | Tillgänglig i |
|----------|--------|-------------|
| `Ctrl p` | Växla till panelläge | Alla utom panel och låst |
| `Ctrl n` | Växla till storleksändringsläge | Alla utom storleksändring och låst |
| `Ctrl s` | Växla till rullningsläge | Alla utom rullning och låst |
| `Ctrl o` | Växla till sessionsläge | Alla utom session och låst |
| `Ctrl t` | Växla till flikläge | Alla utom flik och låst |
| `Ctrl h` | Växla till flyttläge | Alla utom flytt och låst |
| `Ctrl b` | Växla till Tmux-läge | Alla utom Tmux och låst |
Källa:

- <https://github.com/zellij-org/zellij/blob/main/zellij-utils/assets/config/default.kdl>

## Vim-läge i Fish Shell

### Viktiga genvägar

| Genväg | Åtgärd |
|----------|--------|
| `Escape` | Växla till normalläge (kommandoläge) |
| `i` | Gå in i insättningsläge |
| `a` | Gå in i insättningsläge efter markören |
| `A` | Gå in i insättningsläge i slutet av raden |
| `hjkl` | Navigera vänster/ner/upp/höger |
| `0` | Flytta till radens början |
| `$` | Flytta till radens slut |
| `w` | Flytta framåt ett ord |
| `b` | Flytta bakåt ett ord |
| `dd` | Ta bort hela raden |
| `dw` | Ta bort ord |
| `d$` | Ta bort till radens slut |
| `u` | Ångra |
| `/` | Sök framåt |
| `n` | Nästa sökresultat |
| `N` | Föregående sökresultat |
| `v` | Gå in i visuellt läge för markering |
| `y` | Kopiera (yank) markerad text |
| `p` | Klistra in |
Källa:

- Fish-skal dokumentation (fish_vi_key_bindings)

## Standardläge i Fish Shell

### Navigering och historik

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+A` | Flytta till radens början |
| `Ctrl+E` | Flytta till radens slut |
| `Alt+F` | Flytta framåt ett ord |
| `Alt+B` | Flytta bakåt ett ord |
| `Ctrl+P` eller `↑` | Föregående kommando i historiken |
| `Ctrl+N` eller `↓` | Nästa kommando i historiken |
| `Ctrl+R` | Baklängessökning genom historiken |
| `Alt+.` | Infoga sista argumentet från föregående kommando |

### Redigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+U` | Ta bort från markören till radens början |
| `Ctrl+K` | Ta bort från markören till radens slut |
| `Ctrl+W` | Ta bort föregående ord |
| `Alt+D` | Ta bort ord framåt |
| `Ctrl+T` | Byt plats på två tecken |
| `Alt+T` | Byt plats på två ord |
| `Ctrl+L` | Rensa skärmen |

### Kommandokontroll

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+C` | Avbryt aktuellt kommando |
| `Ctrl+Z` | Pausa process |
| `Tab` | Auto-komplettera |
| `Alt+E` | Redigera kommando i extern editor |
| `Alt+L` | Lista kataloginnehåll |
Källa:

- Fish-skal dokumentation (standardtangentbindningar)

## Webbläsargenvägar

### Navigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+L` eller `F6` | Fokusera på adressfältet |
| `Ctrl+T` | Öppna ny flik |
| `Ctrl+N` | Öppna nytt fönster |
| `Ctrl+W` | Stäng aktuell flik |
| `Ctrl+Shift+T` | Öppna senast stängda flik |
| `Ctrl+Tab` | Växla till nästa flik |
| `Ctrl+Shift+Tab` | Växla till föregående flik |
| `Ctrl+1` till `Ctrl+8` | Växla till specifik flik (1:a till 8:e) |
| `Ctrl+9` | Växla till sista fliken |
| `Alt+Home` | Gå till startsidan |
| `Alt+←` eller `Backspace` | Gå tillbaka |
| `Alt+→` eller `Shift+Backspace` | Gå framåt |
| `F5` | Ladda om sidan |
| `Ctrl+F5` eller `Shift+F5` | Ladda om sidan (kringgå cache) |
| `Esc` | Stoppa sidladdning |

### Visning och läsning

| Genväg | Åtgärd |
|----------|--------|
| `F11` | Växla fullskärm |
| `Ctrl+F` | Sök på sidan |
| `F3` eller `Ctrl+G` | Hitta nästa träff |
| `Shift+F3` eller `Ctrl+Shift+G` | Hitta föregående träff |
| `Ctrl++` (plus) | Zooma in |
| `Ctrl+-` (minus) | Zooma ut |
| `Ctrl+0` | Återställ zoom till 100% |
| `Ctrl+U` | Visa sidkälla |
| `Space` | Rulla nedåt |
| `Shift+Space` | Rulla uppåt |
| `Home` | Gå till sidans topp |
| `End` | Gå till sidans botten |
| `Ctrl+D` | Bokmärk aktuell sida |
| `Ctrl+Shift+D` | Bokmärk alla öppna flikar |
| `Ctrl+H` | Visa historik |
| `Ctrl+J` | Visa nedladdningar |

### Redigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+C` | Kopiera markerad text |
| `Ctrl+X` | Klipp ut markerad text |
| `Ctrl+V` | Klistra in text |
| `Ctrl+Z` | Ångra |
| `Ctrl+Y` eller `Ctrl+Shift+Z` | Gör om |
| `Ctrl+A` | Markera allt |

### Övrigt

| Genväg | Åtgärd |
|----------|--------|
| `Alt+F` eller `F10` | Öppna webbläsarmeny |
| `Ctrl+K` eller `Ctrl+E` | Sök från adressfältet |
| `Ctrl+Enter` | Lägg till <www>. och .com till text i adressfältet |
| `Shift+Enter` | Lägg till <www>. och .net till text i adressfältet |
| `Ctrl+Shift+Enter` | Lägg till <www>. och .org till text i adressfältet |
| `Ctrl+Shift+Delete` | Öppna alternativ för att rensa webbläsardata |
| `Ctrl+Shift+B` | Växla bokmärkesfält |
| `Ctrl+Shift+N` | Nytt inkognitofönster/privat fönster |
| `Ctrl+P` | Skriv ut sida |
| `Ctrl+S` | Spara sida |

### Utvecklarverktyg

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+Shift+I` eller `F12` | Öppna utvecklarverktyg |
| `Ctrl+Shift+J` | Öppna utvecklarverktygskonsolen |
| `Ctrl+Shift+C` | Inspektera element-verktyg (elementväljare) |
| `Ctrl+Shift+M` | Växla enhetsemulering (responsiv designläge) |
| `F8` eller `Ctrl+\` | Pausa/återuppta skriptexekvering |
| `F10` eller `Ctrl+'` | Stega över nästa funktionsanrop |
| `F11` eller `Ctrl+;` | Stega in i nästa funktionsanrop |
| `Shift+F11` eller `Ctrl+Shift+;` | Stega ut ur aktuell funktion |
Källa:

- Vanliga webbläsargenvägar (Chrome, Firefox, Edge)

## Vimium webbläsartillägg genvägar

### Grundläggande navigering

| Genväg | Åtgärd |
|----------|--------|
| `?` | Visa hjälp (alla kommandon) |
| `j` | Rulla nedåt |
| `k` | Rulla uppåt |
| `h` | Rulla vänster |
| `l` | Rulla höger |
| `gg` | Rulla till sidans topp |
| `G` | Rulla till sidans botten |
| `d` | Rulla nedåt halv sida |
| `u` | Rulla uppåt halv sida |
| `f` | Öppna en länk i aktuell flik |
| `F` | Öppna en länk i ny flik |
| `r` | Ladda om sidan |
| `gs` | Visa sidans källkod |
| `yy` | Kopiera aktuell URL till urklipp |
| `p` | Öppna urklippets URL i aktuell flik |
| `P` | Öppna urklippets URL i ny flik |

### Flikhantering

| Genväg | Åtgärd |
|----------|--------|
| `J` eller `gT` | Gå till föregående flik |
| `K` eller `gt` | Gå till nästa flik |
| `g0` | Gå till första fliken |
| `g#` | Gå till sista fliken |
| `t` | Skapa ny flik |
| `x` | Stäng aktuell flik |
| `X` | Återställ stängd flik |
| `^` | Gå till tidigare besökt flik |
| `T` | Sök bland dina öppna flikar |

### Historik

| Genväg | Åtgärd |
|----------|--------|
| `H` | Gå bakåt i historiken |
| `L` | Gå framåt i historiken |

### Markeringar

| Genväg | Åtgärd |
|----------|--------|
| `ma` | Sätt lokal markering "a" |
| `mA` | Sätt global markering "A" |
| `'a` | Hoppa till lokal markering "a" |
| `'A` | Hoppa till global markering "A" |

### Avancerad navigering

| Genväg | Åtgärd |
|----------|--------|
| `/` | Gå in i sökläge |
| `n` | Gå framåt till nästa sökträff |
| `N` | Gå bakåt till föregående sökträff |
| `o` | Öppna URL, bokmärke eller historikepost |
| `O` | Öppna URL, bokmärke eller historikepost i ny flik |
| `b` eller `Ctrl-b` | Sök bokmärken |
| `B` | Sök bokmärken (ny flik) |
| `[[` | Följ länken märkt "föregående" eller "<" |
| `]]` | Följ länken märkt "nästa" eller ">" |

### Visuellt läge

| Genväg | Åtgärd |
|----------|--------|
| `v` | Gå in i visuellt läge |
| `V` | Gå in i visuellt radläge |
| När i visuellt läge: |
| `h`, `j`, `k`, `l` | Flytta markören |
| `y` | Kopiera markerad text |
| `Esc` | Avsluta visuellt läge |

### Övrigt

| Genväg | Åtgärd |
|----------|--------|
| `i` | Gå in i insättningsläge (inaktivera Vimium) |
| `Esc` | Avsluta insättningsläge |
| `gi` | Fokusera på första textinmatningen på sidan |
| `gf` | Växla fokus till nästa ram |
| `zi` | Zooma in sidan |
| `zo` | Zooma ut sidan |
| `zz` | Återställ zoom till standard |
| `yf` | Kopiera en länk-URL till urklipp |

### Avancerade kommandon

| Genväg | Åtgärd |
|----------|--------|
| `:` | Gå in i kommandoläge |
| Några användbara kommandon: |
| `:open example.com` | Öppna URL i aktuell flik |
| `:tabnew example.com` | Öppna URL i ny flik |
| `:duplicate` | Duplicera aktuell flik |
| `:settings` | Öppna Vimium-inställningar |
Källa:

- Vimium webbläsartillägg dokumentation

## VS Code tangentbordsgenvägar

### Grundläggande redigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+X` | Klipp ut rad (tom markering) |
| `Ctrl+C` | Kopiera rad (tom markering) |
| `Alt+↑` / `Alt+↓` | Flytta rad upp/ner |
| `Shift+Alt+↑` / `Shift+Alt+↓` | Kopiera rad upp/ner |
| `Ctrl+Shift+K` | Ta bort rad |
| `Ctrl+Enter` | Infoga rad nedanför |
| `Ctrl+Shift+Enter` | Infoga rad ovanför |
| `Ctrl+]` / `Ctrl+[` | Indentera/minska indentering för rad |
| `Home` / `End` | Gå till radens början/slut |
| `Ctrl+Home` / `Ctrl+End` | Gå till filens början/slut |
| `Ctrl+L` | Markera aktuell rad |
| `Ctrl+F2` | Markera alla förekomster av aktuellt ord |
| `Ctrl+Alt+↑` / `Ctrl+Alt+↓` | Infoga markör ovanför/nedanför |
| `Alt+Click` | Infoga markör vid position |
| `Ctrl+Space` | Trigga förslag |
| `Ctrl+Shift+Space` | Trigga parameterförslag |
| `Tab` | Emmet expandera förkortning (i HTML/CSS-filer) |

### Multimarkör och markering

| Genväg | Åtgärd |
|----------|--------|
| `Alt+Click` | Infoga markör |
| `Ctrl+Alt+↑` / `Ctrl+Alt+↓` | Infoga markör ovanför/nedanför |
| `Ctrl+U` | Ångra senaste marköroperation |
| `Shift+Alt+I` | Infoga markör i slutet av varje markerad rad |
| `Ctrl+L` | Markera aktuell rad |
| `Ctrl+Shift+L` | Markera alla förekomster av aktuell markering |
| `Shift+Alt+→` | Expandera markering |
| `Shift+Alt+←` | Krympa markering |
| `Shift+Alt+(dra mus)` | Kolumn (block) markering |
| `Ctrl+Shift+Alt+(piltangent)` | Kolumn (block) markering |

### Avancerad språkredigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+Space` | Trigga förslag |
| `Ctrl+Shift+Space` | Trigga parameterförslag |
| `Shift+Alt+F` | Formatera dokument |
| `Ctrl+K Ctrl+F` | Formatera markering |
| `F12` | Gå till definition |
| `Alt+F12` | Granska definition |
| `Ctrl+K F12` | Öppna definition åt sidan |
| `Ctrl+.` | Snabbkorrigering |
| `F2` | Byt namn på symbol |
| `Ctrl+Shift+.` / `Ctrl+Shift+,` | Ersätt med nästa/föregående värde |
| `Ctrl+K Ctrl+X` | Ta bort avslutande blanksteg |
| `Ctrl+K M` | Ändra filspråk |

### Navigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+T` | Visa alla symboler |
| `Ctrl+G` | Gå till rad... |
| `Ctrl+P` | Gå till fil... |
| `Ctrl+Shift+O` | Gå till symbol... |
| `Ctrl+Shift+M` | Visa problempanel |
| `F8` / `Shift+F8` | Gå till nästa/föregående fel eller varning |
| `Alt+←` / `Alt+→` | Gå bakåt/framåt |
| `Ctrl+M` | Växla att Tab flyttar fokus |
| `Ctrl+F` | Sök |
| `Ctrl+H` | Ersätt |
| `F3` / `Shift+F3` | Hitta nästa/föregående |
| `Alt+Enter` | Markera alla förekomster av sökträff |
| `Ctrl+D` | Lägg till markering till nästa sökträff |
| `Ctrl+K Ctrl+D` | Flytta senaste markeringen till nästa sökträff |
| `Alt+C` / `Alt+R` / `Alt+W` | Växla skiftlägeskänslighet / regex / hela ord |

### Editorhantering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+F4` / `Ctrl+W` | Stäng editor |
| `Ctrl+K F` | Stäng mapp |
| `Ctrl+\` | Dela editor |
| `Ctrl+1` / `Ctrl+2` / `Ctrl+3` | Fokusera i 1:a, 2:a, 3:e editorgruppen |
| `Ctrl+K Ctrl+←` / `Ctrl+K Ctrl+→` | Fokusera i föregående/nästa editorgrupp |
| `Ctrl+Shift+PgUp` / `Ctrl+Shift+PgDn` | Flytta editor vänster/höger |
| `Ctrl+K ←` / `Ctrl+K →` | Flytta aktiv editorgrupp |

### Filhantering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+N` | Ny fil |
| `Ctrl+O` | Öppna fil... |
| `Ctrl+S` | Spara |
| `Ctrl+Shift+S` | Spara som... |
| `Ctrl+K S` | Spara alla |
| `Ctrl+F4` | Stäng |
| `Ctrl+K Ctrl+W` | Stäng alla |
| `Ctrl+Shift+T` | Öppna senast stängda editor |
| `Ctrl+K Enter` | Behåll förhandsvisningseditor öppen |
| `Ctrl+Tab` | Öppna nästa |
| `Ctrl+Shift+Tab` | Öppna föregående |
| `Ctrl+K P` | Kopiera sökväg till aktiv fil |
| `Ctrl+K R` | Visa aktiv fil i Utforskaren |
| `Ctrl+K O` | Visa aktiv fil i nytt fönster/instans |

### Visning

| Genväg | Åtgärd |
|----------|--------|
| `F11` | Växla fullskärm |
| `Shift+Alt+0` | Växla editorlayout (horisontell/vertikal) |
| `Ctrl+=` / `Ctrl+-` | Zooma in/ut |
| `Ctrl+B` | Växla sidofältssynlighet |
| `Ctrl+Shift+E` | Visa Utforskaren / Växla fokus |
| `Ctrl+Shift+F` | Visa Sök |
| `Ctrl+Shift+G` | Visa Källkontroll |
| `Ctrl+Shift+D` | Visa Felsökning |
| `Ctrl+Shift+X` | Visa Tillägg |
| `Ctrl+Shift+H` | Ersätt i filer |
| `Ctrl+Shift+J` | Växla sökdetaljer |
| `Ctrl+Shift+U` | Visa utdatapanel |
| `Ctrl+Shift+V` | Öppna Markdown-förhandsgranskning |
| `Ctrl+K V` | Öppna Markdown-förhandsgranskning åt sidan |
| `Ctrl+K Z` | Zen-läge (Esc Esc för att avsluta) |

### Felsökning

| Genväg | Åtgärd |
|----------|--------|
| `F9` | Växla brytpunkt |
| `F5` | Starta/Fortsätt |
| `Shift+F5` | Stoppa |
| `F11` / `Shift+F11` | Stega in/ut |
| `F10` | Stega över |
| `Ctrl+K Ctrl+I` | Visa hovring |

### Integrerad terminal

| Genväg | Åtgärd |
|----------|--------|
| ``Ctrl+` `` | Visa integrerad terminal |
| ``Ctrl+Shift+` `` | Skapa ny terminal |
| `Ctrl+Shift+C` | Kopiera markering |
| `Ctrl+Shift+V` | Klistra in i aktiv terminal |
| `Ctrl+↑` / `Ctrl+↓` | Rulla upp/ner |
| `Shift+PgUp` / `Shift+PgDn` | Rulla sida upp/ner |
| `Ctrl+Home` / `Ctrl+End` | Rulla till toppen/botten |
Källa:

- VS Code standardtangentbordsgenvägar för Windows/Linux

## NeoVim tangentbordsgenvägar

### Ändra lägen

| Genväg | Åtgärd |
|----------|--------|
| `<ESC>` | Avsluta från andra lägen till NORMAL-läge |
| `i` / `I` | Gå in i INSERT-läge (före aktuellt tecken / första tecknet på raden) |
| `a` / `A` | Gå in i INSERT-läge (efter aktuellt tecken / slutet av raden) |
| `o` / `O` | Skapa tom rad nedanför/ovanför markören och gå in i INSERT-läge |
| `v` | Gå in i visuellt läge (teckenmarkering) |
| `V` | Gå in i visuellt läge (radmarkering) |
| `<CTRL>-v` | Gå in i visuellt läge (blockmarkering) |
| `:` | Gå in i COMMAND-LINE-läge |

### Grundläggande i normalläge

| Genväg | Åtgärd |
|----------|--------|
| `J` | Sammanfoga rad vid markören med raden nedanför |
| `u` | Ångra senaste redigering |
| `U` | Ångra alla ändringar på senast redigerade rad |
| `<CTRL>-r` | Gör om (motsatsen till föregående ångra) |
| `p` | Lägg till (klistra in) |
| `ZZ` | Skriv fil och avsluta |
| `.` | Upprepa senaste ändring |

### Operatorer

| Genväg | Åtgärd |
|----------|--------|
| `y` | Kopiera (Yank) |
| `c` | Ändra (ta bort och gå in i INSERT-läge) |
| `d` | Ta bort |

### Rörelsekommandon

| Genväg | Åtgärd |
|----------|--------|
| `w` / `W` | Början av nästa ord/ORD |
| `b` / `B` | Början av föregående ord/ORD |
| `e` / `E` | Slutet av nästa ord/ORD |
| `ge` / `gE` | Slutet av föregående ord/ORD |
| `0` eller `<HOME>` | Första tecknet på raden |
| `^` | Första icke-blanka tecknet på raden |
| `$` | Slutet av raden |
| `f{char}` / `F{char}` | Framåt/bakåt till tecken |
| `t{char}` / `T{char}` | Framåt/bakåt fram till tecken (stannar före) |
| `%` | Matchande par (parentes, klamrar) |

### Markörrörelser

| Genväg | Åtgärd |
|----------|--------|
| `h` eller `<LEFT>` | Flytta vänster |
| `j` eller `<DOWN>` | Flytta nedåt |
| `k` eller `<UP>` | Flytta uppåt |
| `l` eller `<RIGHT>` | Flytta höger |
| `H` | Första raden på skärmen (High) |
| `M` | Mittlinjen på skärmen |
| `L` | Sista raden på skärmen (Low) |

### Rullning

| Genväg | Åtgärd |
|----------|--------|
| `<CTRL>-u` | Rulla halv sida upp |
| `<CTRL>-d` | Rulla halv sida ner |
| `<CTRL>-y` | Rulla upp en rad |
| `<CTRL>-e` | Rulla ner en rad |
| `<CTRL>-b` | Rulla upp en skärm (minus 2 rader) |
| `<CTRL>-f` | Rulla ner en skärm (minus 2 rader) |
| `zt` | Flytta markörrad till toppen av skärmen |
| `zz` | Flytta markörrad till mitten av skärmen |
| `zb` | Flytta markörrad till botten av skärmen |

### Markeringsobjekt

| Prefix + Objekt | Åtgärd |
|----------|--------|
| `i` / `a` + `w` | Inre/ett ord |
| `i` / `a` + `W` | Inre/ett ORD (inkluderar skiljetecken) |
| `i` / `a` + `s` | Inre/en mening |
| `i` / `a` + `p` | Inre/ett stycke |
| `i` / `a` + `[` eller `]` | Inre/ett [] block |
| `i` / `a` + `(` eller `)` eller `b` | Inre/ett () block |
| `i` / `a` + `<` eller `>` | Inre/ett <> block |
| `i` / `a` + `{` eller `}` | Inre/ett {} block |

### Vanliga genvägar

| Genväg | Åtgärd |
|----------|--------|
| `s` | Ändra ett tecken |
| `x` | Ta bort tecken under markören |
| `X` | Ta bort tecken till vänster om markören |
| `r{char}` | Ersätt tecken under markören |
| `C` | Ändra till slutet av raden |
| `D` | Ta bort till slutet av raden |
| `yy` | Kopiera hela raden |
| `cc` eller `S` | Ändra hela raden |
| `dd` | Ta bort hela raden |

### Fönsterhantering

| Genväg | Åtgärd |
|----------|--------|
| `<CTRL>-w w` | Hoppa mellan fönster |
| `<CTRL>-w t` | Flytta till övre fönster |
| `<CTRL>-w b` | Flytta till nedre fönster |
| `<CTRL>-w +` | Öka fönsterstorlek |
| `<CTRL>-w -` | Minska fönsterstorlek |
| `<CTRL>-w h/j/k/l` | Navigera till fönster (vänster/ner/upp/höger) |
| `<CTRL>-w H/J/K/L` | Flytta fönster (vänster/ner/upp/höger) |
| `<CTRL>-w o` | Behåll endast aktuellt fönster (stäng andra) |

### Visuellt blockläge

| Genväg | Åtgärd |
|----------|--------|
| `o` | Ändra markör till andra änden av markeringen |
| `O` | Ändra hörn i blockmarkering |
| `I{string}<Esc>` | Infoga text till vänster om blocket på varje rad |
| `A{string}<Esc>` | Infoga text till höger om blocket på varje rad |
| `C{string}<Esc>` | Ta bort block och gå in i insättningsläge |

### Operator+rörelsekommando-kombinationer

| Genväg | Åtgärd |
|----------|--------|
| `dw` | Ta bort till nästa ord |
| `d$` eller `D` | Ta bort till slutet av raden |
| `d0` | Ta bort till början av raden |
| `diw` | Ta bort inre ord |
| `di(` | Ta bort text inuti () |
| `di{` | Ta bort text inuti {} |
| `di[` | Ta bort text inuti [] |
| `di"` | Ta bort text inuti "" |
| `dip` | Ta bort inre stycke |
| `cw` | Ändra till nästa ord |
| `c$` eller `C` | Ändra till slutet av raden |
| `c0` | Ändra till början av raden |
| `ciw` | Ändra inre ord |
| `ci(` | Ändra text inuti () |
| `ci{` | Ändra text inuti {} |
| `ci[` | Ändra text inuti [] |
| `ci"` | Ändra text inuti "" |
| `cip` | Ändra inre stycke |
| `yiw` | Kopiera (yank) inre ord |
| `yi(` | Kopiera text inuti () |
| `yi{` | Kopiera text inuti {} |
| `yi[` | Kopiera text inuti [] |
| `yi"` | Kopiera text inuti "" |
| `yip` | Kopiera inre stycke |

### Markörer

| Genväg | Åtgärd |
|----------|--------|
| `m{char}` | Sätt markör vid markörposition (a-z för fillokala, A-Z för globala) |
| `` `{char}`` | Hoppa till position för markör |
| `'{char}` | Hoppa till rad för markör |
| `` `. `` | Hoppa till position för senaste redigering |
| `'.` | Hoppa till rad för senaste redigering |
| `` `0 `` | Hoppa till position där du senast avslutade Vim |
| `` `"`` | Hoppa till position när du senast redigerade denna fil |
| `` `[ `` | Hoppa till början av senast kopierad text |
| `` `] `` | Hoppa till slutet av senast kopierad text |
| `:marks` | Lista alla markörer |

### Vikning

| Genväg | Åtgärd |
|----------|--------|
| `zo` | Öppna vikning |
| `zc` | Stäng vikning |
| `za` | Växla vikning |
| `zR` | Öppna alla vikningar |
| `zM` | Stäng alla vikningar |
| `zj` | Flytta till nästa vikning |
| `zk` | Flytta till föregående vikning |

### Makron

| Genväg | Åtgärd |
|----------|--------|
| `q{char}` | Börja spela in makro i register {char} |
| `q` | Sluta spela in makro |
| `@{char}` | Exekvera makro i register {char} |
| `@@` | Upprepa senast exekverade makro |
| `{count}@{char}` | Exekvera makro {count} gånger |

### Sök och ersätt

| Genväg | Åtgärd |
|----------|--------|
| `/{pattern}` | Sök framåt |
| `?{pattern}` | Sök bakåt |
| `n` / `N` | Nästa/föregående förekomst |
| `*` | Sök framåt efter ord under markören |
| `#` | Sök bakåt efter ord under markören |
| `:s/from/to/[flags]` | Hitta och ersätt |

### Kommandoradsläge

| Kommando | Åtgärd |
|---------|--------|
| `:edit filename` | Redigera ny fil eller ladda befintlig |
| `:q` | Avsluta |
| `:q!` | Avsluta utan att spara ändringar |
| `:w` | Spara fil |
| `:saveas filename` | Spara som nytt filnamn |
| `:file filename` | Ändra aktuellt filnamn |
| `:s/from/to/[flags]` | Hitta och ersätt |

### Fönsterkommandon

| Kommando | Åtgärd |
|---------|--------|
| `:new` | Öppna fönster på ny tom fil (ovanför) |
| `:split` | Dela fönster horisontellt |
| `:vsplit` | Dela fönster vertikalt |
| `:close` | Stäng aktuellt fönster |
| `:only` | Stäng alla fönster utom aktuellt |
Källa:

- <https://cheatography.com/marconlsantos/cheat-sheets/neovim/>

## LazyVim tangentbordsgenvägar

### Navigering och fönster

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<C-h>` | Gå till vänster fönster | n |
| `<C-j>` | Gå till nedre fönster | n |
| `<C-k>` | Gå till övre fönster | n |
| `<C-l>` | Gå till höger fönster | n |
| `<C-Up>` | Öka fönsterhöjd | n |
| `<C-Down>` | Minska fönsterhöjd | n |
| `<C-Left>` | Minska fönsterbredd | n |
| `<C-Right>` | Öka fönsterbredd | n |
| `<A-j>` | Flytta nedåt | n, i, v |
| `<A-k>` | Flytta uppåt | n, i, v |
| `<leader>-` | Dela fönster nedanför | n |
| `<leader>\|` | Dela fönster höger | n |
| `<leader>wd` | Ta bort fönster | n |
| `<leader>wm` / `<leader>uZ` | Växla zoomläge | n |
| `<leader>uz` | Växla zenläge | n |

### Bufferthantering

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<S-h>` / `[b` | Föregående buffert | n |
| `<S-l>` / `]b` | Nästa buffert | n |
| `<leader>bb` / <code><leader>\`</code> | Växla till annan buffert | n |
| `<leader>bd` | Ta bort buffert | n |
| `<leader>bo` | Ta bort andra buffertar | n |
| `<leader>bD` | Ta bort buffert och fönster | n |
| `<leader>bl` | Ta bort buffertar till vänster | n |
| `<leader>br` | Ta bort buffertar till höger | n |
| `<leader>bp` | Växla nålning | n |
| `<leader>bP` | Ta bort icke-nålade buffertar | n |
| `[B` | Flytta buffert föregående | n |
| `]B` | Flytta buffert nästa | n |

### Flikhantering

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader><tab>l` | Sista fliken | n |
| `<leader><tab>f` | Första fliken | n |
| `<leader><tab><tab>` | Ny flik | n |
| `<leader><tab>]` | Nästa flik | n |
| `<leader><tab>[` | Föregående flik | n |
| `<leader><tab>d` | Stäng flik | n |
| `<leader><tab>o` | Stäng andra flikar | n |

### Sök och hitta

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<esc>` | Avsluta och rensa hlsearch | i, n, s |
| `<leader>ur` | Rita om / Rensa hlsearch / Diff-uppdatering | n |
| `n` | Nästa sökresultat | n, x, o |
| `N` | Föregående sökresultat | n, x, o |
| `<leader>/` | Grep (rotkatalog) | n |
| `<leader>sg` | Grep (rotkatalog) | n |
| `<leader>sG` | Grep (aktuell arbetskatalog) | n |
| `<leader>sw` | Sök ord (rotkatalog) | n, x |
| `<leader>sW` | Sök ord (aktuell arbetskatalog) | n, x |
| `<leader>ss` | Gå till symbol (aerial) | n |
| `<leader>sr` | Sök och ersätt | n, v |

### Filoperationer

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<C-s>` | Spara fil | i, x, n, s |
| `<leader>fn` | Ny fil | n |
| `<leader><space>` | Hitta filer (rotkatalog) | n |
| `<leader>ff` | Hitta filer (rotkatalog) | n |
| `<leader>fF` | Hitta filer (aktuell arbetskatalog) | n |
| `<leader>fg` | Hitta filer (git-filer) | n |
| `<leader>fr` | Senaste filer | n |
| `<leader>fR` | Senaste filer (aktuell arbetskatalog) | n |
| `<leader>fc` | Hitta konfigurationsfil | n |

### Kodnavigering och LSP

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>cl` | LSP-info | n |
| `gd` | Gå till definition | n |
| `gr` | Referenser | n |
| `gI` | Gå till implementering | n |
| `gy` | Gå till typdefinition | n |
| `gD` | Gå till deklaration | n |
| `K` | Hovra | n |
| `gK` | Signaturhjälp | n |
| `<c-k>` | Signaturhjälp | i |
| `<leader>ca` | Kodåtgärd | n, v |
| `<leader>cc` | Kör codelens | n, v |
| `<leader>cr` | Byt namn | n |
| `<leader>cR` | Byt namn på fil | n |
| `<leader>cf` | Formatera | n, v |
| `<leader>cF` | Formatera injicerade språk | n, v |
| `<leader>cd` | Raddiagnostik | n |
| `]d` | Nästa diagnostik | n |
| `[d` | Föregående diagnostik | n |
| `]e` | Nästa fel | n |
| `[e` | Föregående fel | n |
| `]w` | Nästa varning | n |
| `[w` | Föregående varning | n |
| `<leader>cs` | Symboler (trouble) | n |
| `<leader>cS` | LSP-referenser (trouble) | n |

### Diagnostik och problematik

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>xx` | Diagnostik (trouble) | n |
| `<leader>xX` | Buffertdiagnostik (trouble) | n |
| `<leader>xL` | Platslista (trouble) | n |
| `<leader>xQ` | Quickfix-lista (trouble) | n |
| `<leader>xl` | Platslista | n |
| `<leader>xq` | Quickfix-lista | n |
| `[q` | Föregående quickfix | n |
| `]q` | Nästa quickfix | n |

### Terminal

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>ft` | Terminal (rotkatalog) | n |
| `<leader>fT` | Terminal (aktuell arbetskatalog) | n |
| `<c-/>` | Terminal (rotkatalog) / Dölj terminal | n, t |
| `<c-_>` | which_key_ignore | n, t |

### Git

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>gb` | Git blame-rad | n |
| `<leader>gB` | Git bläddra (öppna) | n, x |
| `<leader>gY` | Git bläddra (kopiera) | n, x |
| `<leader>gs` | Git status | n |
| `<leader>gS` | Git stash | n |
| `<leader>gd` | Git diff (hunkar) | n |

### UI-växlingar

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>uf` | Växla autoformatering (global) | n |
| `<leader>uF` | Växla autoformatering (buffert) | n |
| `<leader>us` | Växla stavning | n |
| `<leader>uw` | Växla radbrytning | n |
| `<leader>uL` | Växla relativa radnummer | n |
| `<leader>ud` | Växla diagnostik | n |
| `<leader>ul` | Växla radnummer | n |
| `<leader>uc` | Växla döljnivå | n |
| `<leader>uA` | Växla fliklinje | n |
| `<leader>uT` | Växla treesitter-markering | n |
| `<leader>ub` | Växla mörk bakgrund | n |
| `<leader>uC` | Färgscheman | n |
| `<leader>uh` | Växla inlagda tips | n |

### Kommentarer

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `gco` | Lägg till kommentar nedanför | n |
| `gcO` | Lägg till kommentar ovanför | n |

### Felsökning

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>dpp` | Växla profilerare | n |
| `<leader>dph` | Växla profileringsmarkeringar | n |
| `<leader>ui` | Inspektera position | n |
| `<leader>uI` | Inspektera träd | n |
| `<leader>da` | Kör med argument | n |
| `<leader>db` | Växla brytpunkt | n |
| `<leader>dB` | Brytpunktsvillkor | n |
| `<leader>dc` | Kör/fortsätt | n |
| `<leader>dC` | Kör till markör | n |
| `<leader>di` | Stega in | n |
| `<leader>do` | Stega ut | n |
| `<leader>dO` | Stega över | n |
| `<leader>dt` | Avsluta | n |
| `<leader>du` | Dap UI | n |
| `<leader>de` | Utvärdera | n, v |

### Extra plugins

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>l` | Lazy | n |
| `<leader>L` | LazyVim ändringslogg | n |
| `<leader>cm` | Mason | n |
| `<leader>qq` | Avsluta alla | n |
| `<leader>sn` | +noice | n |
| `<leader>sna` | Noice alla | n |
| `<leader>snd` | Avfärda alla | n |
| `<leader>snh` | Noice historik | n |
| `<leader>snl` | Noice senaste meddelande | n |
| `<leader>snt` | Noice väljare | n |
| `<leader>e` / `<leader>fe` | Utforskare (rotkatalog) | n |
| `<leader>E` / `<leader>fE` | Utforskare (aktuell arbetskatalog) | n |

### Testning

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>t` | +test | n |
| `<leader>tr` | Kör närmaste (neotest) | n |
| `<leader>tl` | Kör senaste (neotest) | n |
| `<leader>tt` | Kör fil (neotest) | n |
| `<leader>tT` | Kör alla testfiler (neotest) | n |
| `<leader>ts` | Växla sammanfattning (neotest) | n |
| `<leader>to` | Visa utdata (neotest) | n |
| `<leader>tO` | Växla utdatapanel (neotest) | n |
| `<leader>tS` | Stoppa (neotest) | n |
| `<leader>tw` | Växla övervakning (neotest) | n |
| `<leader>td` | Felsök närmaste | n |

### Sessionshantering

| Tangent | Beskrivning | Läge |
|-----|-------------|------|
| `<leader>qd` | Spara inte aktuell session | n |
| `<leader>ql` | Återställ senaste session | n |
| `<leader>qs` | Återställ session | n |
| `<leader>qS` | Välj session | n |
Källa:

- Standard LazyVim-tangentbindningar (Lägen: n=normal, i=infoga, v=visuell, x=visuell rad, s=markera)

## Fish Shell fzf.fish genvägar

### Grundkommandon

| Genväg | Åtgärd | Förhandsgranskning |
|----------|--------|---------|
| `Ctrl+Alt+F` | Sök katalog | Fil med syntaxmarkering |
| `Ctrl+Alt+L` | Sök Git-logg | Commit-meddelande och diff |
| `Ctrl+Alt+S` | Sök Git-status | Git diff av filen |
| `Ctrl+R` | Sök historik | Kommando med syntaxmarkering |
| `Ctrl+Alt+P` | Sök processer | CPU/minnesanvändning och processinformation |
| `Ctrl+V` | Sök variabler | Variabelns omfångsinformation och värden |

### Sök katalog-funktioner

- Kataloger infogas med avslutande `/` för enkel navigering
- Om markören är på en katalogsökväg med avslutande snedstreck (t.ex. `.config/`), söks den katalogen
- Ignorerar filer som också ignoreras av git
- Tab för att välja flera filer

### Sök Git-logg-funktioner

- Visar formaterad git-logg med commit-hash
- Förhandsgranskningsfönstret visar fullständigt commit-meddelande och diff
- Kan anpassas med variabeln `fzf_git_log_format`

### Sök Git-status-funktioner

- Visar modifierade, staged och oövervakade filer
- Förhandsgranskningsfönstret visar git diff av filen
- Användbart för att snabbt lägga till specifika filer till commits

### Sök historik-funktioner

- Visar tidsstämpel för varje kommando
- Tidsstämpelsformat anpassningsbart via `fzf_history_time_format`
- Bevarar Fish syntax-markering i förhandsgranskning

### Vanlig fzf-navigering

| Genväg | Åtgärd |
|----------|--------|
| `↑` / `↓` eller `Ctrl+P` / `Ctrl+N` | Navigera upp/ner i resultat |
| `Enter` | Välj aktuellt objekt och avsluta |
| `Tab` | Välj flera objekt |
| `Shift+Tab` | Avmarkera objekt |
| `Ctrl+Space` | Växla markering |
| `Alt+Enter` | Välj alla träffar |
| `Esc` | Avsluta utan att välja |
| `Alt+↑` / `Alt+↓` | Rulla förhandsgranskningsfönstret upp/ner |
| `Ctrl+/` | Växla hjälpmeny |
| `Ctrl+R` | Växla sorteringsordning |
| `Alt+W` | Växla förhandsgranskningsradbrytning |

### Konfigurationsalternativ

För att anpassa tangentbindningar, använd funktionen `fzf_configure_bindings` i din `config.fish`:

```fish
# Exempel: Inaktivera historiksökning och använd annan tangent för katalogsökning
fzf_configure_bindings --history= --directory=\e\cf
```

Källa:

- fzf.fish-plugindokumentation

## VSCode Neovim-integration

### Navigering och redigering

| Läge | Genväg | Åtgärd |
|------|----------|--------|
| Normal | `hjkl` | Grundläggande förflyttning |
| Normal | `w` / `b` / `e` | Ordnavigering |
| Normal | `0` / `^` / `$` | Radnavigering |
| Normal | `gg` / `G` | Dokumentets början/slut |
| Normal | `{` / `}` | Styckenavigering |
| Normal | `<C-u>` / `<C-d>` | Halv sida upp/ner |
| Normal | `<C-f>` / `<C-b>` | Hel sida upp/ner |
| Normal | `zz` / `zt` / `zb` | Centrera/topp/botten-vy |
| Infoga | `<C-o>` | Kör ett normallägeskommando |
| Normal | `i` / `a` / `I` / `A` | Gå in i infogningsläge |
| Visuell | `v` / `V` / `<C-v>` | Visuella markeringar |

### Kodnavigering

| Läge | Genväg | Åtgärd |
|------|----------|--------|
| Normal | `gd` | Gå till definition |
| Normal | `gD` | Förhandsgranska definition |
| Normal | `gf` | Gå till deklaration |
| Normal | `gH` | Hitta alla referenser |
| Normal | `gh` / `K` | Visa hovring |
| Normal | `<C-w>gd` | Öppna definition åt sidan |
| Normal | `gO` | Gå till symbol |
| Normal | `<C-n>` / `<C-p>` | Navigera förslagslistor |

### Fil/bufferthantering

| Läge | Genväg | Åtgärd |
|------|----------|--------|
| Normal | `:e {fil}` | Redigera fil |
| Normal | `:w` | Spara fil |
| Normal | `:q` | Stäng editor |
| Normal | `<leader>ff` | Hitta filer |
| Normal | `<leader>fg` | Hitta i git-filer |
| Normal | `<leader>sg` | Sök i filer |
| Normal | `<C-w>s` / `:split` | Dela horisontellt |
| Normal | `<C-w>v` / `:vsplit` | Dela vertikalt |
| Normal | `<C-w>h/j/k/l` | Navigera delningar |
| Normal | `<C-w>o` / `:only` | Behåll endast aktuellt fönster |

### Fönster/flikhantering

| Läge | Genväg | Åtgärd |
|------|----------|--------|
| Normal | `:tabnew` | Ny flik |
| Normal | `gt` / `gT` | Nästa/föregående flik |
| Normal | `:tabc` | Stäng flik |
| Normal | `<C-w>+` / `<C-w>-` | Ändra höjd |
| Normal | `<C-w>>` / `<C-w><` | Ändra bredd |
| Normal | `<C-Up/Down/Left/Right>` | Ändra storlek på paneler |

### Flera markörer

| Läge | Genväg | Åtgärd |
|------|----------|--------|
| Visuell rad | `ma` / `mA` | Lägg till markör i slutet av varje rad |
| Visuell rad | `mi` / `mI` | Lägg till markör i början av varje rad |
| Visuellt block | `ma` | Lägg till markör efter block |
| Visuellt block | `mi` | Lägg till markör före block |
| Infoga | `<C-v>` genomgång | Använd VSCode multimarkör |

### Kodåtgärder och formatering

| Läge | Genväg | Åtgärd |
|------|----------|--------|
| Normal/Visuell | `=` | Formatera markering |
| Normal | `==` | Formatera rad |
| Normal | `<leader>ca` | Kodåtgärder |
| Normal | `<leader>cr` | Byt namn på symbol |
| Normal | `<leader>cf` | Formatera fil |

### Utforskarnavigering

| Läge | Genväg | Åtgärd |
|------|----------|--------|
| Normal | `j` / `k` | Flytta upp/ner |
| Normal | `h` / `l` | Fäll ihop/expandera |
| Normal | `Enter` | Öppna fil |
| Normal | `o` | Växla expandering |
| Normal | `a` / `A` | Ny fil/mapp |
| Normal | `r` | Byt namn |
| Normal | `d` | Ta bort |
| Normal | `y` / `x` / `p` | Kopiera/klipp/klistra |
Källa:

- VSCodeVim/Neovim-tilläggsdokumentation
