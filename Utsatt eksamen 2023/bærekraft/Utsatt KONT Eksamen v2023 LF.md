# Oppg 11-20 Del 2: Bærekraft, teori og metodespørsmål 

Det deles ikke løsningsforslag for flervalgsoppgavene. Det var satt opp 10 tilfeldige oppgaver til hvert eksamen og hver av disse var på 2 poeng.

## Oppgave 21 - teknologimatrisen

Ta utgangspunkt i følgende prosessnettverk, der det inngår fire prosesser med intern utveksling av produkter. De fire prosessene produserer henholdsvis, med angitt enhet

- tonn stål (P1, stålverk)
- kWh strøm (P2, vindkraftverk)
- $m 3$ betong (P3, betongproduksjon), og
- tonn-km transport (P4, jernbanetransport)

![](https://cdn.mathpix.com/cropped/2024_03_10_03427e058ff3db983ac8g-1.jpg?height=754&width=1351&top_left_y=939&top_left_x=244)

Du er i tillegg gitt at hver av de fire prosessene trenger følgende innsats i produksjon:

| P1, per tonn stål | $2500 \mathrm{kWh}$ strøm |
| :--- | :--- |
|  | 500 tonn-km jernbanetransport |
| P2, per kWh strøm | 0.1 tonn stål |
|  | $0.2 \mathrm{~m} 3$ betong |
| P3, per m3 betong | $800 \mathrm{kWh}$ strøm |
|  | 40 tonn-km jernbanetransport |
| P4, per tonn-km transport | $8.0 \mathrm{kWh} \mathrm{str}^{2} \mathrm{~m}$ |
|  | 0.1 tonn stål |
|  | 0.1 tonn betong ${ }^{1}$ |

Under er det gitt et forslag til en teknologimatrise for dette nettverket.

Det er en feil i matrisa. Klikk på det tallet som du mener er feil.[^0]

| Input og <br> outputs | P1 | P2 | P3 | P4 |
| :--- | :---: | :---: | :---: | :---: |
| Stål, tonn | 1 | -0.1 | 0 | -0.1 |
| Strøm, kWh | -2500 | 1 | -800 | -8.0 |
| Betong, m3 | 0 | -0.2 | -1 | -0.1 |
| Transport, tkm | -500 | 0 | -40 | 1 |

## LØSNING

Det er laget tre paralleller av denne oppgaven.

| Input og <br> outputs | P1 | P2 | P3 | P4 |
| :--- | :---: | :---: | :---: | :---: |
| Stål, tonn | 1 | -0.1 | 0 | $-0.1(-8.0)$ |
| Strøm, kWh | -2500 | 1 | -800 | -8.0 |
| Betong, m3 | 0 | -0.2 | $1(-1)$ | -0.1 |
| Transport, tkm | -500 | $0(-0.2)$ | -40 | 1 |

Den riktige matrise skal se slik ut:

| Input og <br> outputs | P1 | P2 | P3 | P4 |
| :--- | :---: | :---: | :---: | :---: |
| Stål, tonn | 1 | -0.1 | 0 | -0.1 |
| Strøm, kWh | -2500 | 1 | -800 | -8.0 |
| Betong, m3 | 0 | -0.2 | 1 | -0.1 |
| Transport, tkm | -500 | 0 | -40 | 1 |

Rett svar for de ulike parallellene.

|  | Balanse 1 | Balanse 2 | Balanse 3 |
| :--- | :--- | :--- | :--- |
| Kommentar | Blå, skal være 0 | Brun, skal være 1 | Rød, skal være -0.1 |

## Oppgave 22 - Livsløpsutslipp

Vi skal nå regne på livsløpsutslipp fra et prosessnettverk der det inngår fire prosesser med intern utveksling av produkter. Et flytskjema er vist under. De fire prosessene produserer henholdsvis, med angitt enhet

- tonn stål (P1, stålverk)
- $k W h$ strøm (P2, vindkraftverk)
- $m 3$ betong (P3, betongproduksjon), og
- tonn-km transport (P4, jernbanetransport)

![](https://cdn.mathpix.com/cropped/2024_03_10_03427e058ff3db983ac8g-3.jpg?height=811&width=1462&top_left_y=251&top_left_x=248)

Du er gitt følgende teknologimatrise (technology matrix, A) og intervensjonsmatrise (intervention, matrix, B) for systemet.

Teknologimatrise:

| Input og <br> outputs | P1 (stål) | P2 (straum) | P3 (betong) | P4 (jernb.tr.) |
| :--- | :--- | :--- | :--- | :--- |
| Stål, tonn | 1 | -0.0001 | 0 | -0.0001 |
| Strøm, kWh | -300 | 1 | -1000 | -1.0 |
| Betong, m3 | 0 | -0.0002 | 1 | -0.0001 |
| Transport, tkm | -250 | 0 | -100 | 1 |

Intervensjonsmatrise:

| Intervensjon | P1 (stål) | P2 (straum) | P3 (betong) | P4 (jb-transport) |
| :--- | :---: | :---: | :---: | :---: |
| $\mathrm{CO}_{2}, \mathrm{~kg}$ | 1200 | 0.1 | 600 | 36 |
| $\mathrm{SO}_{2}, \mathrm{~g}$ | 2.5 | 0.001 | 0.7 | 25 |
| $\mathrm{Malm}, \mathrm{m} 3$ | -3.0 | 0.0 | -1.5 | 0.0 |

Regn ut livsløpsutslippene av CO2 i dette systemet av et samlet sluttforbruk på 15 tonn stål og 2 m3 betong. Oppgi svaret som et heltall i enheter kg CO2: XX

(svar innenfor +/- 50 godkjennes)

## Løsning

Hva er livsløpsutslippene for produksjonen av $\mathrm{x}$ mengder av produkt $\mathrm{A}$ og $\mathrm{z}$ mengder av produkt $\mathrm{B}$ ?

Alle oppgavene har samme teknologimatrise, men det er forskjell i sluttforbruket. Det er i alt fire paralleller, der hver av disse er angitt med sluttforbruk i denne matrisa:

| $\mathrm{f} 1$ | $\mathrm{f} 2$ | $\mathrm{f3}$ | $\mathrm{f} 4$ |  |
| ---: | ---: | ---: | ---: | :--- |
| 15 | 2 | 0 | 15 | $\mathrm{P}$ 1 (tonn stål) |
| 0 | 0 | 2 | 0 | $\mathrm{P} 2$ (kWh strøm) |
| 2 | 15 | 15 | 0 | $\mathrm{P} 3$ (m3 betong) |
| 0 | 0 | 0 | 2 | P4 (tonn-km transport) |

Man kommer til sluttforbruksvektor fra informasjonen i oppgaven ved å føre opp de tallene som er gitt. Slik at sluttforbruksvektoren for f1 tilsvarer 15 tonn stål og $2 \mathrm{~m} 3$ betong (som i oppgaveteksten over). Riktig svar for hver oppgave er vist i denne tabellen.

| sluttforb | $\mathrm{f} 1$ | $\mathrm{f2}$ | $\mathrm{f3}$ | $\mathrm{f4}$ |
| :--- | ---: | ---: | ---: | ---: |
| svar | 198735 | 137090 | 112599 | 183805 |

Rett svar regnes ut som produktet $\mathrm{r}=\mathrm{b} \mathrm{A}^{-1} \mathrm{f}$. For sluttforbruksvektoren for $\mathbf{f 1}$ har vi at tallene i de ulike vektorene og matrisene er:

![](https://cdn.mathpix.com/cropped/2024_03_10_03427e058ff3db983ac8g-4.jpg?height=289&width=1779&top_left_y=1092&top_left_x=238)

## Oppgave 23 - balanseligninger i MFA

Vi skal nå se på materialstrømsanalyse for et system med tre deler, der vi ser på møbler i norske hjem. Systemet består av følgende tre prosesser, med et flytskjema gitt under:

- P1: omsetning av møbler
- P2: bruk av møbler
- P3: avhending av møbler.

![](https://cdn.mathpix.com/cropped/2024_03_10_03427e058ff3db983ac8g-4.jpg?height=625&width=1062&top_left_y=1892&top_left_x=240)

Kort fortalt vet vi om de ulike strømmene i systemet at:

- Den eneste innstrømmen til systemet er ved at nye møbler tas inn til omsetning i P1. Omsetningen består imidlertid av salg av både nye og brukte møbler. Det oppgis at $10 \%$ av nye og brukte møbler som kommer inn til omsetning sendes til avhending i P3. Det er 100000 tonn møbler som selges fra P1 til norske hjem årlig.
- I Norge er vi ganske gode til å bruke sorteringsanleggene og vi regner at $90 \%$ av alle møbler som går ut fra bruksfasen sendes til avhending. Resten av utstrømmen fra P2 ender som tap fra systemet, ved å gå som eksport ut av landet eller ende i annen avfallsbehandling.
- Deler av møbler som norske hjem sender til avhending blir faktisk gjenbrukt. Vi regner med at $15 \%$ av møbler som går til P3 ender i ny omsetning gjennom ulike kanaler (butikk-salg, loppemarked, bruktmarkeder hos mottaksanlegg, finn.no, arv eller gaver), og dette er vist som strøm x31. Det resterende går ut av systemet til forbrenning og regnes som eksport.
- Alle strømmer kan regnes som tonn og vi forutsetter et system i balanse (steady state).

Denne informasjonen kan vi bruke til å sette opp en koeffisientmatrise for MFA. Vi skal nå første se på balanseligningene. Her følger et forslag til koeffesientmatrise der de øverste tre linjene beskriver balanseligninger for henholdsvis P1, P2 og P3 når vi begynner med P1 øverst.

Det er en feil i én av balanseligningene. Klikk på det tallet som er feil i matrisa.

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x31}$ | $\mathrm{x30}$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | -1 | -1 | 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | -1 | -1 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 | -1 | -1 | 0 |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |

## Løsning

Det er laget fire paralleller av denne oppgaven, der faktoren som er endret varierer mellom oppgavene. Svaret er dermed avhengig av hvilken oppgave du fikk.

Den riktige matrise skal se slik ut, med feil tall indikert i parentes:

| x01 | x12 | x13 | x20 | x23 | x31 | x30 | Y |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | -1 | -1 | 0 | $0(1)$ | 1 | 0 | 0 |
| $0(1)$ | 1 | 0 | -1 | -1 | 0 | 0 | 0 |
| 0 | $0(1)$ | 1 | 0 | $1(0)$ | -1 | -1 | 0 |
| 0 | 1 | 0 | 0 | 0 | 0 | 0 | 10000 |
| -0.1 | 0 | 1 | 0 | 0 | -0.1 | 0 | 0 |
| 0 | -0.9 | 0 | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | -0.15 | 0 | -0.15 | 1 | 0 | 0 |


|  | Balanse 1 | Balanse 4 | Balanse 2 | Balanse 3 |
| :--- | :--- | :--- | :--- | :--- |
| Kommentar | Blå, skal være 0 | Grønn, skal være 0 | Brun, skal være 0 | Rød, skal være 1 |

## Rett matrise

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x} 31$ | $\mathrm{x} 30$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | -1 | -1 | 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | -1 | -1 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 | -1 | -1 | 0 |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |

## Oppgave 24 - modell-ligninger i MFA

I denne oppgaven skal vi fortsette med vårt MFA-system for møbler. Følgende informasjon beskriver systemet, der prosesser og strømmer er de samme som i forrige oppgave. Forskjellen er at spørsmålet til slutt gjelder modell-ligninger for systemet.

Vi skal gjøre materialstrømsanalyse for et system med tre deler som beskriver møbler i Norge.

Systemet består av følgende tre prosesser, med et flytskjema gitt under:

- P1: omsetning av møbler
- P2: bruk av møbler
- P3: avhending av møbler.

![](https://cdn.mathpix.com/cropped/2024_03_10_03427e058ff3db983ac8g-6.jpg?height=660&width=1111&top_left_y=1383&top_left_x=238)

Kort fortalt vet vi om de ulike strømmene i systemet at:

- Den eneste innstrømmen til systemet er ved at nye møbler tas inn til omsetning i P1. Omsetningen består imidlertid av salg av både nye og brukte møbler. Det oppgis at $10 \%$ av nye og brukte møbler som kommer inn til omsetning sendes til avhending i P3. Det er 100000 tonn møbler som selges fra P1 til norske hjem årlig.
- I Norge er vi ganske gode til å bruke sorteringsanleggene og vi regner at $90 \%$ av alle møbler som går ut fra bruksfasen sendes til avhending. Resten av utstrømmen fra P2 ender som tap fra systemet, ved å gå som eksport ut av landet eller ende i annen avfallsbehandling.
- Deler av møbler som norske hjem sender til avhending blir faktisk gjenbrukt. Vi regner med at $15 \%$ av møbler som går til P3 ender i ny omsetning gjennom ulike kanaler (butikk-salg,
loppemarked, bruktmarkeder hos mottaksanlegg, finn.no, arv eller gaver), og dette er vist som strøm x31. Det resterende går ut av systemet til forbrenning og regnes som eksport.

Denne informasjonen kan vi bruke til å sette opp en koeffisientmatrise for MFA. Vi skal nå se på modell-ligningene. Her følger et forslag til koeffesientmatrise der de fire nederste radene beskriver modell-ligninger.

Det er en feil i én av modell-ligningene. Klikk på det tallet som er feil i matrisa.

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x} 31$ | $\mathrm{x} 30$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
| 0 | 1 | 0 | 0 | 0 | 0 | 0 | 100000 |
| -0.1 | 0 | 1 | 0 | 0 | -0.1 | 0 | 0 |
| 0 | -0.9 | 0 | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | -0.15 | 0 | -0.15 | 1 | 0 | 0 |

## Løsning

Det er laget fire paralleller av denne oppgaven, der faktoren som er endret varierer mellom oppgavene. Svaret kan dermed avhengig av hvilken oppgave du fikk.

Den riktige matrise skal se slik ut:

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x} 31$ | $\mathrm{x} 30$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | -1 | -1 | 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | -1 | -1 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 | -1 | -1 | 0 |
| 0 | 1 | 0 | 0 | 0 | 0 | 0 | 100000 |
| -0.1 | 0 | 1 | $0(1)$ | 0 | -0.1 | 0 | 0 |
| 0 | -0.9 | $0(-0.9)$ | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | $-0.15(1)$ | 0 | -0.15 | $1(0)$ | 0 | 0 |


|  | Balanse 1 | Balanse 2 | Balanse 3 | Balanse 4 |
| :--- | :--- | :--- | :--- | :--- |
| Kommentar | Blå, skal være 0 | Brun, skal være 0 | Rød, skal være -0.15 | Grønn, skal være 1 |

## Rett matrise

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x} 31$ | $\mathrm{x} 30$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
| 0 | 1 | 0 | 0 | 0 | 0 | 0 | 100000 |
| -0.1 | 0 | 1 | 0 | 0 | -0.1 | 0 | 0 |
| 0 | -0.9 | 0 | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | -0.15 | 0 | -0.15 | 1 | 0 | 0 |

## Oppgave 25 - regne på strømmer i MFA

Vi fortsetter med vår møbel-MFA. Følgende informasjon beskriver systemet, der enkelte prosesser og strømmer er endret fra tidligere oppgaver. Spørsmålet til slutt gjelder beregning av én av strømmen i systemet.

Systemet består av følgende tre prosesser, med et flytskjema gitt under:

- P1: omsetning av møbler.
- P2: bruk av møbler
- P3: avhending av møbler.

![](https://cdn.mathpix.com/cropped/2024_03_10_03427e058ff3db983ac8g-8.jpg?height=634&width=1062&top_left_y=774&top_left_x=243)

Kort fortalt vet vi om de ulike strømmene i systemet at:

- Den eneste innstrømmen til systemet er ved at nye møbler tas inn til omsetning i P1. Omsetningen består imidlertid av salg av både nye og brukte møbler. Det oppgis at $10 \%$ av nye og brukte møbler som kommer inn til omsetning sendes til avhending i P3. Det er 95000 tonn møbler som selges fra P1 til norske hjem årlig.
- I Norge er vi ganske gode til å bruke sorteringsanleggene og vi regner at $90 \%$ av alle møbler som går ut fra bruksfasen sendes til avhending. Resten av utstrømmen fra P2 ender som tap fra systemet, ved å gå som eksport ut av landet eller ende i annen avfallsbehandling.
- Deler av møbler som norske hjem sender til avhending blir faktisk gjenbrukt. Vi regner med at $15 \%$ av møbler som går til P3 ender i ny omsetning gjennom ulike kanaler (butikk-salg, loppemarked, bruktmarkeder hos mottaksanlegg, finn.no, arv eller gaver), og dette er vist som strøm x31. Det resterende går ut av systemet til forbrenning og regnes som eksport.

Denne informasjonen kan vi bruke til å sette opp en koeffisientmatrise for MFA. Her følger en koeffesientmatrise der én av radene mangler. Gjør ferdig koeffisientmatrisa og regn ut hvor mye møbler som går fra avhending til ny omsetning. Dette er vist som x31 i flytskjema.

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x} 31$ | $\mathrm{x} 30$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | -1 | -1 | 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | -1 | -1 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 | -1 | -1 | 0 |
|  |  |  |  |  |  |  |  |
| -0.1 | 0 | 1 | 0 | 0 | -0.1 | 0 | 0 |
| 0 | -0.9 | 0 | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | -0.15 | 0 | -0.15 | 1 | 0 | 0 |

Oppgi størrelsen på x31 i enhet tonn per år: XX. Svar innenfor +/- 50 tonn godtas som rett svar.

## Løsning

Det er laget fire paralleller av denne oppgaven, der faktoren som er endret varierer mellom oppgavene. Svaret kan dermed avhengig av hvilken oppgave du fikk.

Den riktige matrise skal se slik ut, der $\mathrm{X}$ er verdien som skal fylles inn. Verdien for $\mathrm{X}$ er lik det som er oppgitt som solgte møbler $i$ tonn per år fra P1:

| $x 01$ | $x 12$ | $x 13$ | $x 20$ | $x 23$ | $x 31$ | $x 30$ | $Y$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | -1 | -1 | 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | -1 | -1 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 | -1 | -1 | 0 |
| 0 | 1 | 0 | 0 | 0 | 0 | 0 | X |
| -0.1 | 0 | 1 | 0 | 0 | -0.1 | 0 | 0 |
| 0 | -0.9 | 0 | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | -0.15 | 0 | -0.15 | 1 | 0 | 0 |


|  | MFA 1 | MFA 2 | MFA 3 | Modell 4 |
| :--- | :--- | :--- | :--- | :--- |
| Svar | X31 = 14 408 | X31=15 925 | X31 =18 200 | X31 =19 717 |
| Kommentar | X=95000 | $X=105000$ | $X=120000$ | $X=13000$ |

Rett svar regnes ut som produktet $x=A^{-1} y$. For $y$ som angitt $i$ oppgaveteksten, $y=95000$, så har vi det som er oppgitt for MFA1 over, altså x31 = 14 408:

|  |  |  | Koeffisientmatrisa |  |  |  |  |  | -1 | Y-vektor |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 14408 |  |  |  |  |  |  |  |  |  |  |
|  | $=$ | 1 | -1 | -1 | 0 | 0 | 1 | 0 | * | 0 |
|  |  | 0 | 1 | 0 | -1 | -1 | 0 | 0 |  | 0 |
|  |  | 0 | 0 | 1 | 0 | 1 | -1 | -1 |  | 0 |
|  |  | 0 | 1 | 0 | 0 | 0 | 0 | 0 |  | 95000 |
|  |  | $-0,1$ | 0 | 1 | 0 | 0 | $-0,1$ | 0 |  | 0 |
|  |  | 0 | $-0,9$ | 0 | 0 | 1 | 0 | 0 |  | 0 |
|  |  | 0 | 0 | $-0,15$ | 0 | $-0,15$ | 1 | 0 |  | 0 |


[^0]:    ${ }^{1}$ Det kom underveis i eksamen melding om feil i denne oppgaven, der det her skal stå $0.1 \mathrm{~m} 3$ betong, altså $\mathrm{i}$ samme enhet som det også står i den neste tabellen for P3.

