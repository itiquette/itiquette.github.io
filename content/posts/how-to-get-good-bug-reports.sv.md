+++
title = 'How to get good bug reports: A guide for developers'
date = 2025-06-05T07:07:07+01:00
draft = true
tags = ["opensource", "foss", "bug","developer","guide"]
+++

# Konsten att få bra felrapporter: En guide för utvecklare

## Introduktion

Alla utvecklare som har släppt program till allmänheten har troligen också kämpat med vaga, förvirrande eller helt oanvändbara felrapporter.
Rapporter som "Det fungerar inte!", eller för lite information, eller för spretig information.
Men faktum är att det är DU som utvecklare till stor del är ansvarig för att få in bra felrapporter.
Genom att vara förebyggande kan en utvecklare avsevärt förbättra kvaliteten på den feedback som kommer in, vilket gör processen mindre frustrerande för alla.

**Viktigt: Om du konsekvent får dåliga buggrapporter ligger ansvaret hos dig och INTE hos dina användare. De flesta användare vill hjälpa till. Gör det enkelt för dem att ge dig den information du behöver, på det sätt du vill ha den.**

## Mallar är ett måste

**Om du vill ha konsekventa, kompletta felrapporter är strukturerade mallar obligatoriska.** Det är den enskilt viktigaste förbättringen du kan göra - utan en mall får du inte rapporten i det format du vill ha.

1. **Skapa obligatoriska rapportmallar** för alla kanaler där ditt projekt tar emot felrapporter
2. **Kräv att viktiga fält fylls i**
3. **Bygg upp mallen i en logisk ordning**
4. **Visa exempel och ge instruktioner i mallen**

En bra mall skapar lagom struktur och tröskel i rapporteringsprocessen för att avskräcka snabba, dåliga inlämningar, samtidigt som den inte blir ett hinder för de användare som verkligen har problem.

I kodsamverkansplattformar som GitHub, GitLab och liknande går det att skapa ärendemallar med struktur.

Här är [ett exempel på en GitHub-mall](https://github.com/itiquette/gommitlint/blob/main/.github/ISSUE_TEMPLATE/bug_report.yml)

![alt](/images//bugreport1.png)

![alt](/images/bugreport2.png)

Här är en annan exempelmall i ren Markdown:

```markdown
### Vad gick fel 
[Beskriv kort och tydligt vad problemet är]
- Vad hände som inte stämde?
- Var i programmet uppstod felet?

### Hur skulle det fungera
[Förklara vad du trodde skulle hända]
- Vad borde ha hänt istället?
- Hur har det funkat tidigare?

### Vad hände istället
[Beskriv exakt vad som gick snett]
- Vad blev fel?
- Fick du något felmeddelande?

### Hur återskapar man problemet
[Lista de exakta stegen för att upprepa felet]
1. Öppna '...'
2. Klicka på '....'
3. Bläddra ner till '....'
4. Nu syns felet

### Bilder/Video (valfritt)
[Bifoga skärmbilder eller video som visar problemet]

### Systeminformation
 - Programversion: [t.ex. v2.1.3]
 - Enhet: [t.ex. Stationär dator, iPhone 13, etc.]
 - Operativsystem: [t.ex. Windows 11, macOS 12.3, iOS 16.2]
 - Webbläsare (om relevant): [t.ex. Chrome 108.0.5359.124, Safari 16.2]

### Övrigt (valfritt)
[Lägg till annat som kan vara viktigt]
- Händer det varje gång eller bara ibland?
- Bara under vissa omständigheter?
- När såg du problemet första gången?
- Har du hittat något sätt att komma runt det?
```

**Varning**: Utan obligatoriska mallar kommer även välmenande användare att skicka in ofullständiga rapporter. En användare kan inte läsa dina tankar eller förstå din vision av vad som utgör en "bra" felrapport.

## Fokusera på kodsamverkansplattformar

Modern utveckling bygger på system som GitHub, GitLab och Bitbucket för att hantera felrapporter.
Dessa plattformar erbjuder avancerade mallfunktioner som bör vara ditt primära fokus.

## Skapa en positiv rapporteringsmiljö

Användare är mer benägna att skicka grundliga felrapporter när de känner att deras återkoppling uppskattas.

## Fokusera på problem, inte användaren

Hur du svarar på felrapporter påverkar starkt kvaliteten på framtida rapporter.
Fokusera på problemet, inte användaren. 
Om användaren är arg eller frustrerad och blir personlig, fortsätt att vara professionell och håll dig till ämnet
Uppgiften är att göra bättre programvara, inte att engagera sig i onödiga diskussioner.

### Exempel på problemorienterat språk

Istället för: "Du måste ha klickat på fel knapp."
Använd: "Beskriv vilken knapp du klickade på"

Istället för: "Det fungerar hos mig. Du måste göra något fel?"
Använd: "Jag kan inte återupprepa hos mig. Vad kan vara annorlunda i din miljö."

Istället för: "Det verkar vara ett användarfel."
Använd: "Vi kanske kan förbättra den och göra den mer intuitiv. Berätta vad du förväntade dig skulle hända?"

## Automatisera informationsinsamling

Förlita dig inte enbart på användare för att ge teknisk information.
Om möjligt, lägg till kraschdumpar, bra loggsystem etc.
Uppmuntra användaren att använda skärmbilder eller video av felet, om relevant.

## Ställ rätt frågor

Vägled användare att ge specifik information genom att ställa direkta frågor:

- **Vad gjorde du när problemet inträffade?**
- **Vad hände som du inte förväntade dig?**
- **Vad förväntade du dig skulle hända istället?**
- **Kan du återskapa problemet? I så fall, hur?**
- **Märkte du några felmeddelanden eller ovanligt beteende?**
- **När märkte du första gången detta problem?**
- **Har det hänt mer än en gång?**

## Skilj mellan olika användartyper

En teknisk och icke-teknisk användare behöver få olika frågor..

## Sammanfattning

Att få in bra felrapporter handlar inte om användaren — det handlar om vad du gör för att göra det enklare för användaren att ge den informationen, på det sätt du vill ha den.
Det gör det enklare för alla inblandade, och kommer att hjälper dig att fokusera på de faktiska problemen.
