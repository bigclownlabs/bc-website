---
title: Nauč se v BigClownu debugovat zprávy
draft: true
date: 2019-09-21T07:16:22.362Z
weight: 60
description: >-
  Abys svůj program pro IoT krabičku vyladil k dokonalosti, pomůže ti jednoduchý
  debugger, se kterým vychytáš mouchy. Poradíme ti, jak ho nastavíš a rozjedeš.
slug: jak-debugovat
meta.title: Nauč se v BigClownu debugovat zprávy
meta.description: >-
  Abys svůj program pro IoT krabičku vyladil k dokonalosti, pomůže ti jednoduchý
  debugger, se kterým vychytáš mouchy. Poradíme ti, jak ho nastavíš a rozjedeš.
image_preview: >-
  https://res.cloudinary.com/lukasfabik/image/upload/v1569050323/projects/learn-to-debug-messages-in-bigclown/image1.png
image_main: >-
  https://res.cloudinary.com/lukasfabik/image/upload/v1569050325/projects/learn-to-debug-messages-in-bigclown/image3.png
---
Pavouk je rád, když má v síti šťavnatou mouchu nebo jiný hmyz. Do prográmku ale brouci (bugy) nepatří. Vychytej všechny bugy (tak se v angličtině označují hmyzáci i chyby v kódu) ze svých BigClowních projektů. 🐞 Ukážeme ti, jak na to.

## Co je to debug?

Debug znamená v programátorské hantýrce **ladění** či **odstranění chyb** v programu. Protože nějaká ta chybička se do kódu vždycky vloudí. 

Pro ladění používají programátoři nástroj jménem **debugger**. Ten sleduje průběh (flow) programu a programátora na chyby upozorňuje. Ajťák se potom nepřehrabuje řádky kódu, protože ví, kam sáhnout. Jednoduchý debugger najdeš i ve svém [Playgroundu](https://www.bigclown.com/cs/academy/co-je-to-bigclown-playground/). Zkontroluješ si v něm, zda tvůj program šlape tak, jak má, a odhalíš případné chybky.

## Jak debugovat v Playgroundu?

1. Je to easy. 😎 Klikni na záložku **Functions** a najdi si node **Debug**. Je to hned první nod v sekci Output a vypadá takhle:                        

{{< image >}}           

2. Debug node připoj přímo za startovní node **MQTT**. K ničemu jinému ho připojovat nemusíš, takže to bude ve tvém programu takový osamělý výběžek (ale neboj, je to introvert, takže mu to vyhovuje 🤓).

**Náš tip**: Debug node můžeš místo MQTT napojit ke kterémukoliv jinému nodu s výstupem vpravo. Zjistíš tak, jak fungují konkrétní funkce tvého programu. 👍

{{< image >}}  

3. Teď klikni na **ikonu brouka** v pravé horní části Playgroundu.🐞 

{{< image >}}  

4. **A jsi v debuggeru!** V téhle broučí záložce uvidíš zprávy o chodu svého programu. Máš-li třeba krabičku s tlačítkem, zkus tlačítko mačkat nebo ho dát do ledničky a sleduj, jaké zprávy ti tu budou v debuggeru vyskakovat.

Na základě těchto zpráv si v budoucnu během sestavování programů **ověříš, že vše funguje tak, jak má**. 👌 Bude-li ti třeba chybět propojení některých nodů, debugger tě na to upozorní.

Takto v debuggeru vypadají zprávy o tom, co tvůj program s krabičkou dělá:

{{< image >}}
