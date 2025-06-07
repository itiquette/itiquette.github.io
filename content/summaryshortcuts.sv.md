+++
title = 'Tangentbordsgenvägar (arbetsflöde)'
#date = 2024-01-14T07:07:07+01:00
draft = false
type = 'page'
slug = 'shortcutsworkflow'
hideDate = 'true'
+++

# Sammanfattad genvägsreferens

En sammanfattning av de mer [använda genvägarna](shortcutsall.md) för Ubuntu, terminalmultiplexers, skalmiljöer, kodredigerare, webbläsare och utvecklingsverktyg.
Förändras löpande:)

## Innehållsförteckning

- [Systemmiljö (Ubuntu/GNOME)](#systemmiljö-ubuntugnome)
- [Terminalmultiplexer (Zellij)](#terminalmultiplexer-zellij)
- [Fish Shell med Vim-läge](#fish-shell-med-vim-läge)
- [Fish Shell med fzf.fish](#fish-shell-med-fzffish)
- [Neovim/LazyVim](#neovimlazyvim)
- [VSCode med Neovim-tillägg](#vscode-med-neovim-tillägg)
- [Webbläsarnavigering med Vimium](#webbläsarnavigering-med-vimium)
- [Webbläsarens utvecklarverktyg](#webbläsarens-utvecklarverktyg)

## Systemmiljö (Ubuntu/GNOME)

### Fönsterhantering

| Genväg | Åtgärd |
|----------|--------|
| `Super` | Aktivitetsöversikt |
| `Super+A` | Programmenyn |
| `Ctrl+Alt+T` | Öppna terminal |
| `Alt+F4` eller `Ctrl+Q` | Stäng fönster |
| `Super+Vänster/Höger/Upp/Ner` | Fäst fönster vänster/höger/maximera/avmaximera |
| `Alt+Tab` (Alt+Shift+Tab) | Växla programfönster |
| `Super+Tab` (Super+Shift+Tab) | Växla programgrupp |
| `Alt+F6` | Växla fönster i samma program |
| Ctrl+Alt+D | Visa skrivbord |
| `Super+M` | Växla notifieringspanel |
| `Super+L` | Lås skärmen |
| `Ctrl+Alt+Del` | Logga ut |

### Arbetsytans navigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+Alt+Upp/Ner/Vänster/Höger` | Växla arbetsyta |
| `Shift+Ctrl+Alt+Upp/Ner/Vänster/Höger` | Flytta fönster till arbetsyta |

### Verktyg

| Genväg | Åtgärd |
|----------|--------|
| `PrtScr` | Ta skärmdump av område |
| `Alt+PrtScr` | Ta skärmdump av fönster |
| `Shift+PrtScr` | Ta skärmdump av skrivbord |

## Terminalmultiplexer (Zellij)

### Delade genvägar

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+q` | Avsluta |
| `Alt+f` | Växla flytande paneler |
| `Alt+n` | Ny panel |
| `Alt+h/j/k/l` | Flytta fokus vänster/ner/upp/höger |
| `Alt+=` eller `Alt++` | Öka storlek |
| `Alt+-` | Minska storlek |
| `Alt+[` eller `Alt+]` | Föregående/nästa layout |
| `Alt+i/o` | Flytta flik vänster/höger |
| `Shift` | Håll inne för att åsidosätta Zellij mushantering |

### Lägesväxling

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+g` | Växla till låst läge (för att använda ctrl n p i FZF etc.) |
| `Ctrl+p` | Växla till panelläge |
| `Ctrl+t` | Växla till flikläge |
| `Ctrl+n` | Växla till storleksändringsläge |
| `Ctrl+s` | Växla till rullningsläge |
| `Ctrl+o` | Växla till sessionsläge |
| `Ctrl+h` | Växla till flyttläge |
| `Ctrl+b` | Växla till Tmux-läge |
| `Enter/Esc` | Återgå till normalläge (från de flesta lägen) |

### Panelhantering (Panelläge - `Ctrl+p` först)

| Genväg | Åtgärd |
|----------|--------|
| `h/j/k/l` eller `Vänster/Ner/Upp/Höger` | Flytta fokus |
| `p` | Växla fokus |
| `n` | Ny panel |
| `d` | Ny panel nedåt |
| `r` | Ny panel höger |
| `x` | Stäng fokuserad panel |
| `f` | Växla fullskärm |
| `z` | Växla panelramar |
| `w` | Växla flytande paneler |
| `e` | Växla panel inbäddad/flytande |
| `c` | Byt namn på panel |
| `i` | Växla panel nålad |

### Flikhantering (Flikläge - `Ctrl+t` först)

| Genväg | Åtgärd |
|----------|--------|
| `h/l` eller `Vänster/Höger` | Föregående/nästa flik |
| `n` | Ny flik |
| `x` | Stäng flik |
| `r` | Byt namn på flik |
| `s` | Växla synk |
| `1-9` | Gå till flik 1-9 |
| `Tab` | Växla flik |

### Storleksändringsläge (`Ctrl+n` först)

| Genväg | Åtgärd |
|----------|--------|
| `h/j/k/l` | Öka storlek vänster/ner/upp/höger |
| `H/J/K/L` | Minska storlek vänster/ner/upp/höger |
| `=` eller `+` | Öka storlek |
| `-` | Minska storlek |

### Rullning och sökning (Rullningsläge - `Ctrl+s` först)

| Genväg | Åtgärd |
|----------|--------|
| `j/k` eller `Ner/Upp` | Rulla ner/upp |
| `Ctrl+f`/`Ctrl+b` eller `Page Down/Up` | Sidrullning ner/upp |
| `d/u` | Halv sida rulla ner/upp |
| `e` | Redigera rullningsbakåt (sättet att kopiera en listning i zellij) |
| `s` | Gå in i sökläge |
| `n/p` | Sök nästa/föregående |
| `c` | Växla skiftlägeskänslighet |
| `w` | Växla radbrytning |
| `o` | Växla hela ord |

## Fish Shell med Vim-läge

### Lägesväxling

| Genväg | Åtgärd |
|----------|--------|
| `Escape` | Gå in i normalläge |
| `i` | Gå in i insättningsläge |
| `a` | Gå in i insättningsläge (efter markör) |
| `A` | Gå in i insättningsläge (slutet av rad) |

### Navigering i normalläge

| Genväg | Åtgärd |
|----------|--------|
| `h/j/k/l` | Flytta markör vänster/ner/upp/höger |
| `0/^` | Flytta till radens början/första icke-blanka |
| `$` | Flytta till radens slut |
| `w/b` | Flytta framåt/bakåt ett ord |
| `e/ge` | Flytta till slutet av ord/föregående slut av ord |
| `fx/Fx` | Flytta till nästa/föregående förekomst av x |
| `tx/Tx` | Flytta till före nästa/föregående förekomst av x |

### Redigering i normalläge

| Genväg | Åtgärd |
|----------|--------|
| `dd` | Ta bort hela raden |
| `dw` | Ta bort ord |
| `d$` | Ta bort till radens slut |
| `cc` | Ändra hela raden |
| `cw` | Ändra ord |
| `c$` | Ändra till radens slut |
| `yy` | Kopiera (yank) rad |
| `yw` | Kopiera ord |
| `p/P` | Klistra in efter/före markör |
| `u` | Ångra |
| `r` | Ersätt tecken |
| `x` | Ta bort tecken |
| `~` | Ändra skiftläge |

### Kommandohistorik (standardläge)

| Genväg | Åtgärd |
|----------|--------|
| `k` | Föregående kommando |
| `j` | Nästa kommando |
| `Ctrl+r` | Baklängessökning genom historik |

### Radredigering (Emacs-läge)

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+a` | Flytta till radens början |
| `Ctrl+e` | Flytta till radens slut |
| `Alt+f` | Flytta framåt ett ord |
| `Alt+b` | Flytta bakåt ett ord |
| `Ctrl+u` | Ta bort från markör till radens början |
| `Ctrl+k` | Ta bort från markör till radens slut |
| `Ctrl+w` | Ta bort föregående ord |
| `Alt+d` | Ta bort nästa ord |
| `Alt+t` | Byt plats på två ord |
| `Ctrl+l` | Rensa skärm |
| `Ctrl+c` | Avbryt kommando |
| `Ctrl+z` | Pausa process |

## Fish Shell med fzf.fish

### Grundkommandon

| Genväg | Åtgärd | Beskrivning |
|----------|--------|-------------|
| `Ctrl+Alt+f/F` | Sök katalog | Hitta filer i aktuell katalog |
| `Ctrl+Alt+l` | Sök Git-logg | Bläddra och infoga commit-hash |
| `Ctrl+Alt+s` | Sök Git-status | Hitta modifierade/stage:ade/oövervakade filer |
| `Ctrl+s` | Sök historik | Hitta kommandon i skalhistoriken |
| `Ctrl+Alt+p` | Sök processer | Hitta och infoga process-ID |
| `Ctrl+v` | Sök variabler | Hitta och infoga skalvariabler |

### fzf-navigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+k/j` | Navigera upp/ner |
| `Enter` | Välj objekt |
| `Tab` | Välj flera objekt |
| `Shift+Tab` | Avmarkera objekt |
| `Esc` eller `Ctrl+g` | Avbryt |

## Neovim/LazyVim

### Grundläggande förflyttning

| Genväg | Åtgärd |
|----------|--------|
| `h/j/k/l` | Flytta markör vänster/ner/upp/höger |
| `w/W` | Flytta till nästa ord/ORD början |
| `e/E` | Flytta till nästa ord/ORD slut |
| `b/B` | Flytta till föregående ord/ORD början |
| `ge/gE` | Flytta till föregående ord/ORD slut |
| `0/$` | Flytta till radens början/slut |
| `^` | Flytta till första icke-blanka tecken |
| `gg/G` | Flytta till första/sista raden |
| `{/}` | Flytta till föregående/nästa stycke |
| `Ctrl+u/d` | Rulla halv sida upp/ner |
| `Ctrl+b/f` | Rulla sida upp/ner |
| `Ctrl+y/e` | Rulla en rad upp/ner |
| `zz/zt/zb` | Centrera/topp/botten aktuell rad |
| `H/M/L` | Flytta till toppen/mitten/botten av skärmen |
| `fx/Fx` | Flytta till nästa/föregående 'x' |
| `tx/Tx` | Flytta till före nästa/föregående 'x' |
| `;/,` | Upprepa senaste f/F/t/T framåt/bakåt |
| `%` | Hoppa till matchande klammerparentes |
| `yl` | Kopiera ett tecken |

### Redigering

| Genväg | Åtgärd |
|----------|--------|
| `i/I` | Infoga före markör/vid radens början |
| `a/A` | Infoga efter markör/vid radens slut |
| `o/O` | Öppna rad nedan/ovanför |
| `r/R` | Ersätt tecken/gå in i ersättningsläge |
| `c{rörelse}` | Ändra text |
| `cc` | Ändra rad |
| `C` | Ändra till radens slut |
| `d{rörelse}` | Ta bort text |
| `dd` | Ta bort rad |
| `D` | Ta bort till radens slut |
| `x/X` | Ta bort tecken under/före markör |
| `y{rörelse}` | Kopiera (yank) text |
| `yy` eller `Y` | Kopiera rad |
| `p/P` | Klistra in efter/före markör |
| `J` | Sammanfoga rader |
| `u/Ctrl+r` | Ångra/gör om |
| `.` | Upprepa senaste ändring |
| `~` | Växla skiftläge |
| `g~/gu/gU` | Växla/gör litet/gör stort skiftläge |
| `==` | Auto-indentera aktuell rad |
| `=G` | Auto-indentera från markör till slutet av fil |
| `gg=G` | Auto-indentera hela filen (gå till toppen, sedan indentera till slutet) |

### Textobjekt

| Genväg | Åtgärd |
|----------|--------|
| `iw/aw` | Inre/ett ord |
| `iW/aW` | Inre/ett ORD |
| `is/as` | Inre/en mening |
| `ip/ap` | Inre/ett stycke |
| `i"/a"` | Inre/en dubbelt citerad sträng |
| `i'/a'` | Inre/en enkelt citerad sträng |
| `i(/a(` eller `ib/ab` | Inre/en parentesblock |
| `i[/a[` | Inre/ett hakparentesblock |
| `i{/a{` eller `iB/aB` | Inre/ett klammerparentesblock |
| `i</a<` | Inre/ett vinkelparentesblock |
| `it/at` | Inre/ett taggblock |

### Visuellt läge

| Genväg | Åtgärd |
|----------|--------|
| `v/V/Ctrl+v` | Starta tecken/rad/block-markering |
| `o/O` | Flytta till andra änden av markering/annat hörn |
| `=` | Auto-indentera markering |
| `y/d/c/x` | Kopiera/ta bort/ändra/ta bort markering |
| `u/U` | Ändra markering till gemener/versaler |
| `I/A` | Infoga i början/slutet av alla markerade rader (i blockläge) |

### Sök och ersätt

| Genväg | Åtgärd |
|----------|--------|
| `/mönster` | Sök framåt |
| `?mönster` | Sök bakåt |
| `n/N` | Nästa/föregående träff |
| `*/＃` | Sök ord under markören framåt/bakåt |
| `:%s/gammal/ny/g` | Ersätt alla förekomster |
| `:s/gammal/ny/g` | Ersätt i aktuell rad |
| `:%s/gammal/ny/gc` | Ersätt alla med bekräftelse |
| `gd/gD` | Gå till lokal/global definition |

### Markörer och hopp

| Genväg | Åtgärd |
|----------|--------|
| `m{a-zA-Z}` | Sätt markör |
| `` `{markör} `` | Hoppa till markörposition |
| `'{markör}` | Hoppa till markörrad |
| `` `. `` | Hoppa till position för senaste ändring |
| `Ctrl+o/i` | Gå till äldre/nyare position i hopplistan |
| `g;/g,` | Gå till äldre/nyare position i ändringslistan |

### Fönsterhantering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+w v` | Dela fönster vertikalt |
| `Ctrl+w s` | Dela fönster horisontellt |
| `Ctrl+w q` | Stäng fönster |
| `Ctrl+w o` | Stäng alla fönster utom aktuellt |
| `Ctrl+w h/j/k/l` | Flytta till vänster/ner/upp/höger fönster |
| `Ctrl+w H/J/K/L` | Flytta fönster vänster/ner/upp/höger |
| `Ctrl+w r/R` | Rotera fönster ner/upp |
| `Ctrl+w =` | Lika dimensioner för alla fönster |
| `Ctrl+w T` | Flytta fönster till ny flik |

### Flikhantering

| Genväg | Åtgärd |
|----------|--------|
| `:tabnew` | Skapa ny flik |
| `:tabedit {fil}` | Redigera fil i ny flik |
| `:tabclose` | Stäng aktuell flik |
| `:tabonly` | Stäng alla flikar utom aktuell |
| `gt/gT` | Gå till nästa/föregående flik |
| `{n}gt` | Gå till flik n |
| `:tabs` | Lista alla flikar |

### Filoperationer

| Genväg | Åtgärd |
|----------|--------|
| `:e {fil}` | Redigera fil |
| `:w` | Skriv (spara) fil |
| `:wa` | Skriv alla filer |
| `:q` | Avsluta |
| `:qa` | Avsluta alla |
| `:wq` eller `:x` eller `ZZ` | Skriv och avsluta |
| `:q!` eller `ZQ` | Avsluta utan att spara |
| `:saveas {fil}` | Spara som |
| `:r {fil}` | Läs fil till buffert |
| `:r !{cmd}` | Läs kommandoutdata till buffert |

### Kodnavigering (LazyVim)

| Genväg | Åtgärd |
|----------|--------|
| `gd` | Gå till definition |
| `gr` | Gå till referenser |
| `gI` | Gå till implementering |
| `gy` | Gå till typdefinition |
| `gD` | Gå till deklaration |
| `K` | Visa hovringsdokumentation |
| `gK` | Visa signaturhjälp |
| `<leader>ca` | Kodåtgärd |
| `<leader>cf` | Formatera kod |
| `<leader>cr` | Byt namn på symbol |
| `<leader>cd` | Raddiagnostik |
| `]d/[d` | Nästa/föregående diagnostik |
| `]e/[e` | Nästa/föregående fel |
| `]w/[w` | Nästa/föregående varning |

### Ostrukturerad sökning (LazyVim)

| Genväg | Åtgärd |
|----------|--------|
| `<leader><space>` | Hitta filer |
| `<leader>ff` | Hitta filer |
| `<leader>fg` | Hitta i git-filer |
| `<leader>fr` | Senaste filer |
| `<leader>/` | Grep i filer |
| `<leader>sg` | Grep i filer |
| `<leader>ss` | Gå till symbol |
| `<leader>sw` | Sök ord under markör |

### Git-integration (LazyVim)

| Genväg | Åtgärd |
|----------|--------|
| `<leader>gb` | Git blame |
| `<leader>gs` | Git status |
| `<leader>gd` | Git diff |
| `<leader>gS` | Git stash |

### Bufferthantering (LazyVim)

| Genväg | Åtgärd |
|----------|--------|
| `<S-h>/<S-l>` | Föregående/nästa buffert |
| `<leader>bb` | Växla buffert |
| `<leader>bd` | Ta bort buffert |
| `<leader>bo` | Ta bort andra buffertar |
| `<leader>bl` | Ta bort buffertar till vänster |
| `<leader>br` | Ta bort buffertar till höger |
| `<leader>bp` | Växla nåla buffert |

### UI-växlingar (LazyVim)

| Genväg | Åtgärd |
|----------|--------|
| `<leader>uf` | Växla formatering vid sparande |
| `<leader>us` | Växla stavning |
| `<leader>uw` | Växla ordbrytning |
| `<leader>ul` | Växla radnummer |
| `<leader>ud` | Växla diagnostik |
| `<leader>uc` | Växla conceal |
| `<leader>ub` | Växla bakgrund |

### Terminal (LazyVim)

| Genväg | Åtgärd |
|----------|--------|
| `<leader>ft` | Terminal (rotkatalog) |
| `<leader>fT` | Terminal (aktuell arbetskatalog) |
| `<C-/>` | Terminal |

## VSCode med Neovim-tillägg

### VSCode-specifik navigering

| Genväg | Åtgärd |
|----------|--------|
| `gd` | Gå till definition |
| `gD` | Förhandsgranska definition |
| `gf` | Gå till deklaration |
| `gH` | Hitta referenser |
| `gh/K` | Visa hovring |
| `<C-w>gd` | Öppna definition åt sidan |
| `gO` | Gå till symbol |

### Fil/bufferthantering

| Genväg | Åtgärd |
|----------|--------|
| `:e {fil}` | Redigera fil |
| `:w` | Spara fil |
| `:q` | Stäng editor |
| `<C-w>s/:split` | Dela horisontellt |
| `<C-w>v/:vsplit` | Dela vertikalt |
| `<C-w>h/j/k/l` | Navigera delningar |
| `<C-w>o/:only` | Behåll endast aktuellt fönster |

### Kodåtgärder och formatering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+.` | Kodåtgärder |
| `F2` | Byt namn på symbol |
| `Shift+Alt+F` | Formatera fil |

### Vim-genvägsalternativ till multi-cursor

| Genväg | Åtgärd |
|----------|--------|
| `*` | Sök efter ord under markören |
| `cgn` | Ändra nästa förekomst |
| `.` | Upprepa senaste ändring |
| `n` | Hoppa till nästa förekomst |
| `N` | Hoppa till föregående förekomst |
| `:%s/gammal/ny/gc` | Global sök och ersätt med bekräftelse |
| `:%s/gammal/ny/g` | Global sök och ersätt (ingen bekräftelse) |
| `/mönster` | Sök efter mönster |
| `?mönster` | Sök bakåt efter mönster |

### VSCode-nativa funktioner

| Genväg | Åtgärd |
|----------|--------|
| `F5` | Starta felsökning |
| `F9` | Växla brytpunkt |
| `F10` | Stega över |
| `F11/Shift+F11` | Stega in/ut |
| `Ctrl+Shift+`` | Växla terminal |
| `Ctrl+Shift+E` | Visa utforskaren |
| `Ctrl+Shift+G` | Visa källkontroll |
| `Ctrl+Shift+D` | Visa felsökningspanel |
| `Ctrl+Shift+X` | Visa tillägg |
| `Ctrl+P` | Snabböppna filer |
| `Ctrl+Shift+P` | Visa kommandopalett |

### Utforskarnavigering

| Genväg | Åtgärd |
|----------|--------|
| `j/k` | Flytta upp/ner |
| `h/l` | Fäll ihop/expandera |
| `Enter` | Öppna fil |
| `Space` | Förhandsgranska fil (behåll fokus i utforskaren) |
| `a/A` | Ny fil/mapp |
| `r` | Byt namn |
| `d` | Ta bort |
| `y/x/p` | Kopiera/klipp/klistra |

### Allmän panelnavigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+0` | Fokusera på sidofältet |
| `Ctrl+1` | Fokusera tillbaka till editorn |

## Webbläsarnavigering med Vimium

### Grundläggande navigering

| Genväg | Åtgärd |
|----------|--------|
| `j/k` | Rulla ner/upp |
| `h/l` | Rulla vänster/höger |
| `gg/G` | Rulla till toppen/botten |
| `d/u` | Rulla halv sida ner/upp |
| `r` | Ladda om sidan |
| `yy` | Kopiera URL |
| `p/P` | Öppna urklipps-URL i aktuell/ny flik |

### Länknavigering

| Genväg | Åtgärd |
|----------|--------|
| `f` | Visa länkmarkörer (aktuell flik) |
| `F` | Visa länkmarkörer (ny flik) |
| `[[/]]` | Navigera till föregående/nästa sida |
| `gf` | Växla fokus mellan ramar |

### Flikhantering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+Tab` / `Ctrl+Shift+Tab` | Gå till föregående/nästa flik |
| `g0/g$` eller `Alt+9` | Gå till första/sista fliken |
| `Ctrl+t` | Skapa ny flik |
| `Ctrl+W` | Stäng flik |
| `T` | Sök flikar |

### Historiknavigering

| Genväg | Åtgärd |
|----------|--------|
| `H/L` | Gå bakåt/framåt i historiken |

### Visuellt läge

| Genväg | Åtgärd |
|----------|--------|
| `v` | Gå in i visuellt läge |
| `V` | Gå in i visuellt radläge |
| `y` | Kopiera markerad text (i visuellt läge) |

### Sökning

| Genväg | Åtgärd |
|----------|--------|
| `/` | Gå in i sökläge |
| `n/N` | Hitta nästa/föregående träff |

### Övrigt

| Genväg | Åtgärd |
|----------|--------|
| `i` | Gå in i insättningsläge (inaktivera Vimium) |
| `gi` | Fokusera första textinmatning |
| `gs` | Visa källkod |
| `?` | Visa hjälp |

## Webbläsarens utvecklarverktyg

### Navigering

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+Shift+I` | Växla utvecklarverktyg |
| `Ctrl+Shift+K` | Konsol |
| `Ctrl+Shift+C` | Inspektera element |
| `Ctrl+]` / `Ctrl+[` | Navigera framåt/bakåt i panelhistorik |
| `Ctrl+Shift+M` | Växla enhetsläge |

### Felsökning

| Genväg | Åtgärd |
|----------|--------|
| `F8` eller `Ctrl+\` | Pausa/återuppta |
| `F10` eller `Ctrl+'` | Stega över |
| `F11` eller `Ctrl+;` | Stega in |
| `Shift+F11` eller `Ctrl+Shift+;` | Stega ut |

### Konsol

| Genväg | Åtgärd |
|----------|--------|
| `Ctrl+L` | Rensa konsol |
| `Upp/Ner` | Navigera kommandohistorik |
| `Shift+Enter` | Flerradig inmatning |
| `Esc` | Växla konsollåda |