# Oppg 11-20 Del 2: Bærekraft, teori og metodespørsmål 

Det deles ikke løsningsforslag for flervalgsoppgavene. Det var satt opp 10 tilfeldige oppgaver til hvert eksamen og hver av disse var på 2 poeng.

## Oppgave 21 - teknologimatrisen

Ta utgangspunkt i følgende prosessnettverk, der det inngår fire prosesser med intern utveksling av produkter. De fire prosessene produserer henholdsvis, med angitt enhet

- tonn stål (P1, stålverk)
- kWh strøm (P2, vindkraftverk)
- $m 3$ betong (P3, betongproduksjon), og
- tonn-km transport (P4, jernbanetransport)

![](https://cdn.mathpix.com/cropped/2024_03_10_4eeb99e6f8dffbb63a1dg-1.jpg?height=754&width=1351&top_left_y=939&top_left_x=244)

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

Det er en feil i matrisa. Klikk på det tallet som du mener er feil. (Merk at dette er én av oppgavealternativene).[^0]

| Input og <br> outputs | P1 | P2 | P3 | P4 |
| :--- | :---: | :---: | :---: | :---: |
| Stål, tonn | 1 | -0.1 | 0 | -8.0 |
| Strøm, kWh | -2500 | 1 | -800 | -8.0 |
| Betong, m3 | 0 | -0.2 | -1 | -0.1 |
| Transport, tkm | -500 | 0 | -40 | 1 |

## Oppgave 22 - Livsløpsutslipp

Vi skal nå regne på livsløpsutslipp fra et prosessnettverk der det inngår fire prosesser med intern utveksling av produkter. Et flytskjema er vist under. De fire prosessene produserer henholdsvis, med angitt enhet

- tonn stål (P1, stålverk)
- kWh strøm (P2, vindkraftverk)
- $m 3$ betong (P3, betongproduksjon), og
- tonn-km transport (P4, jernbanetransport)

![](https://cdn.mathpix.com/cropped/2024_03_10_4eeb99e6f8dffbb63a1dg-2.jpg?height=808&width=1450&top_left_y=1121&top_left_x=260)

Du er gitt følgende teknologimatrise (technology matrix, A) og intervensjonsmatrise (intervention, matrix, B) for systemet.

Teknologimatrise:

| Input og <br> outputs | P1 (stål) | P2 (straum) | P3 (betong) | P4 (jernb.tr.) |
| :--- | :--- | :--- | :--- | :--- |
| Stål, tonn | 1 | -0.0001 | 0 | -0.0001 |
| Strøm, kWh | -300 | 1 | -1000 | -1.0 |
| Betong, m3 | 0 | -0.0002 | 1 | -0.0001 |
| Transport, tkm | -250 | 0 | -100 | 1 |

Intervensjonsmatrise:

| Intervensjon | $\mathrm{P} 1$ (stål) | $\mathrm{P} 2$ (straum) | $\mathrm{P} 3$ (betong) | P4 (jb-transport) |
| :--- | :---: | :---: | :---: | :---: |
| $\mathrm{CO}_{2}, \mathrm{~kg}$ | 1200 | 0.1 | 600 | 36 |
| $\mathrm{SO}_{2}, \mathrm{~g}$ | 2.5 | 0.001 | 0.7 | 25 |
| $\mathrm{Malm}, \mathrm{m} 3$ | -3.0 | 0.0 | -1.5 | 0.0 |

Regn ut livsløpsutslippene av CO2 i dette systemet av et samlet sluttforbruk på 15 tonn stål og 2 m3 betong. Oppgi svaret som et heltall i enheter $\mathrm{kg} \mathrm{CO} 2$ :

(svar innenfor +/- 50 godkjennes)

## Oppgave 23 - balanseligninger i MFA

Vi skal nå se på materialstrømsanalyse for et system med tre deler, der vi ser på møbler i norske hjem. Systemet består av følgende tre prosesser, med et flytskjema gitt under:

- P1: omsetning av møbler
- P2: bruk av møbler
- P3: avhending av møbler.

![](https://cdn.mathpix.com/cropped/2024_03_10_4eeb99e6f8dffbb63a1dg-3.jpg?height=628&width=1066&top_left_y=1294&top_left_x=238)

Kort fortalt vet vi om de ulike strømmene i systemet at:

- Den eneste innstrømmen til systemet er ved at nye møbler tas inn til omsetning i P1. Omsetningen består imidlertid av salg av både nye og brukte møbler. Det oppgis at $10 \%$ av nye og brukte møbler som kommer inn til omsetning sendes til avhending i P3. Det er 100000 tonn møbler som selges fra P1 til norske hjem årlig.
- I Norge er vi ganske gode til å bruke sorteringsanleggene og vi regner at $90 \%$ av alle møbler som går ut fra bruksfasen sendes til avhending. Resten av utstrømmen fra P2 ender som tap fra systemet, ved å gå som eksport ut av landet eller ende i annen avfallsbehandling.
- Deler av møbler som norske hjem sender til avhending blir faktisk gjenbrukt. Vi regner med at $15 \%$ av møbler som går til P3 ender i ny omsetning gjennom ulike kanaler (butikk-salg, loppemarked, bruktmarkeder hos mottaksanlegg, finn.no, arv eller gaver), og dette er vist som strøm x31. Det resterende går ut av systemet til forbrenning og regnes som eksport.
- Alle strømmer kan regnes som tonn og vi forutsetter et system i balanse (steady state).

Denne informasjonen kan vi bruke til å sette opp en koeffisientmatrise for MFA. Vi skal nå første se på balanseligningene. Her følger et forslag til koeffesientmatrise der de øverste tre linjene beskriver balanseligninger for henholdsvis P1, P2 og P3 når vi begynner med P1 øverst.

Det er en feil i én av balanseligningene. Klikk på det tallet som er feil i matrisa. (Merk at dette er én av oppgavealternativene).

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x} 31$ | $\mathrm{x} 30$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | -1 | -1 | 0 | 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | -1 | -1 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 | -1 | -1 | 0 |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |

## Oppgave 24 - modell-ligninger i MFA

I denne oppgaven skal vi fortsette med vårt MFA-system for møbler. Følgende informasjon beskriver systemet, der prosesser og strømmer er de samme som i forrige oppgave. Forskjellen er at spørsmålet til slutt gjelder modell-ligninger for systemet.

Vi skal gjøre materialstrømsanalyse for et system med tre deler som beskriver møbler i Norge. Systemet består av følgende tre prosesser, med et flytskjema gitt under:

- P1: omsetning av møbler
- P2: bruk av møbler
- P3: avhending av møbler.

![](https://cdn.mathpix.com/cropped/2024_03_10_4eeb99e6f8dffbb63a1dg-4.jpg?height=660&width=1108&top_left_y=1600&top_left_x=240)

Kort fortalt vet vi om de ulike strømmene i systemet at:

- Den eneste innstrømmen til systemet er ved at nye møbler tas inn til omsetning i P1. Omsetningen består imidlertid av salg av både nye og brukte møbler. Det oppgis at $10 \%$ av nye og brukte møbler som kommer inn til omsetning sendes til avhending i P3. Det er 100000 tonn møbler som selges fra P1 til norske hjem årlig.
- I Norge er vi ganske gode til å bruke sorteringsanleggene og vi regner at $90 \%$ av alle møbler som går ut fra bruksfasen sendes til avhending. Resten av utstrømmen fra P2 ender som tap fra systemet, ved å gå som eksport ut av landet eller ende i annen avfallsbehandling.
- Deler av møbler som norske hjem sender til avhending blir faktisk gjenbrukt. Vi regner med at $15 \%$ av møbler som går til P3 ender i ny omsetning gjennom ulike kanaler (butikk-salg, loppemarked, bruktmarkeder hos mottaksanlegg, finn.no, arv eller gaver), og dette er vist som strøm x31. Det resterende går ut av systemet til forbrenning og regnes som eksport.

Denne informasjonen kan vi bruke til å sette opp en koeffisientmatrise for MFA. Vi skal nå se på modell-ligningene. Her følger et forslag til koeffesientmatrise der de fire nederste radene beskriver modell-ligninger.

Det er en feil i én av modell-ligningene. Klikk på det tallet som er feil i matrisa. (Merk at dette er én av oppgavealternativene).

| $\mathrm{x} 01$ | $\mathrm{x} 12$ | $\mathrm{x} 13$ | $\mathrm{x} 20$ | $\mathrm{x} 23$ | $\mathrm{x} 31$ | $\mathrm{x} 30$ | $\mathrm{Y}$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |
| 0 | 1 | 0 | 0 | 0 | 0 | 0 | 100000 |
| -0.1 | 0 | 1 | 0 | 0 | -0.1 | 0 | 0 |
| 0 | -0.9 | -0.9 | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | -0.15 | 0 | -0.15 | 1 | 0 | 0 |

## Oppgave 25 - regne på strømmer i MFA

Vi fortsetter med vår møbel-MFA. Følgende informasjon beskriver systemet, der enkelte prosesser og strømmer er endret fra tidligere oppgaver. Spørsmålet til slutt gjelder beregning av én av strømmen i systemet.

Systemet består av følgende tre prosesser, med et flytskjema gitt under:

- P1: omsetning av møbler.
- P2: bruk av møbler
- P3: avhending av møbler.

![](https://cdn.mathpix.com/cropped/2024_03_10_4eeb99e6f8dffbb63a1dg-5.jpg?height=631&width=1066&top_left_y=1952&top_left_x=238)

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

Oppgi størrelsen på x31 i enhet tonn per år:

Svar innenfor +/- 50 tonn godtas som rett svar.


[^0]:    ${ }^{1}$ Det kom underveis i eksamen melding om feil i denne oppgaven, der det her skal stå $0.1 \mathrm{~m} 3$ betong, altså $\mathrm{i}$ samme enhet som det også står i den neste tabellen for P3.

