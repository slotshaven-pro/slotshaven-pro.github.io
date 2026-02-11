---
title: Synopsis
description: '- programdokumentation'
order: 80
---
En synopsis (bestemt form: _synopsen_) er en

> kortfattet, mere eller mindre detaljeret udkast til en planlagt film, bog el.lign. (kilde: ordnet.dk).

Vejledning til Programmering B skriver:

> Eksamensprojektet består af et produkt og en **synopsis**. Synopsen skal dokumentere udviklingen af det færdige produkt og har et omfang på 5-8 normalsider, eksklusiv koder, rutediagrammer, bilag mm.

I faget programmering betegner synopsen altså en beskrivelse af og vejledning til et program.
Vejledningen uddyber det således:

> En synopsis skal forstås som en tekst, der skrives til eksaminator og censor som forberedelse til den mundtlige eksamen. Det vil sige, at en synopsis giver censor og eksaminator et overblik over projektet i form af relevante abstrakte dokumentationsformer og passende forklaringer i almindelig tekst. I synopsen inddrages diagrammer og andre visualiseringer, der kan billedliggøre elevernes tanker om struktureringen af deres software. Endvidere gennemgås udvalgte dele af softwaren på kodeniveau.

Synopsen dokumenterer altså det færdige program. Man kan dog med fordel udarbejde sin synopse sideløbende med udviklingen af programmet, idet man løbende forfiner og forbedrer de beskrivelser og diagrammer som man producerer i planlægningsfasen. På den måde indgår synopsen i den iterative udviklingsproces.

Se [eksempel på opbygning af synopsis ↗️]({% link sider/synopsis-skabelon.md %}).

I synopsen dokumenterer man _overordnet_ og _i detaljer_ for sin løsning. Det gælder altså om, at forklare relevante anvendte teknologier og den overordnede arkitektur - ved hjælp af skærmbilleder, diagrammer, pseudo-kode osv. Særligt vigtigt er en gennemgang af udvalgte, centrale kode-eksempler.

Man kan også med fordel kort dokumentere hvordan brugeren anvender programmet - altså programmets anvendelse og funktioner - i et særskilt afsnit.

## AI

Vær særlig opmærksom på at dokumentere brugen af AI.

AI-genereret kode skal deklareres - det skal altså fremgå at det er genereret af AI.
Relevant prompt-historik skal dokumenteres i bilag. Bed evt. din AI om at logge al kommunikation.
Instruktionsfiler (`AGENTS.md`, `copilot-instructions.md`) skal i bilag.
