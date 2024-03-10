# Beregningsoppgave 1- Teknologimatrise 3 poeng 

Ta utgangspunkt i følgende prosessnettverk, der det inngår fire prosesser med intern utveksling av produkter. De fire prosessene produserer henholdsvis, med angitt enhet

- tonn stål (P1, stålverk)
- $k W h$ strøm (P2, vindkraftverk)
- $m 3$ betong (P3, betongproduksjon), og
- tonn-km transport (P4, jernbanetransport)

![](https://cdn.mathpix.com/cropped/2024_03_09_279b8ceb610e8e048e06g-1.jpg?height=811&width=1465&top_left_y=811&top_left_x=250)

Du er i tillegg gitt at hver av de fire prosessene trenger følgende innsats i produksjon:

| P1, per tonn stål | $2500 \mathrm{kWh}$ strøm |
| :--- | :--- |
|  | 500 tonn-km jernbanetransport |
| P2, per kWh strøm | 0.1 tonn stål |
|  | $0.2 \mathrm{~m} 3$ betong |
| P3, per m3 betong | $800 \mathrm{kWh}$ strøm |
|  | 40 tonn-km jernbanetransport |
| P4, per tonn-km transport | $8.0 \mathrm{kWh}$ strøm |
|  | 0.1 tonn stål |
|  | 0.1 tonn betong |

Her er ett forslag til en teknologimatrise for dette nettverket, der rekkefølgen på radene er lik den for kolonnene. (merk at dette er matrisen i ett av oppgavealternativene)

| P1 (stål) | P2 (strøm) | P3 (betong) | P4 (jb- <br> transport) |
| :--- | :--- | :--- | :--- |
| 1 | -0.1 | 0 | -0.1 |
| -2500 | 1 | -8.0 | -8.0 |
| -0 | -0.2 | 1 | -0.1 |
| -500 | 0 | -40 | 1 |

Det er en feil i matrisen. Oppgi hva verdien for dette tallet skulle vært, som en absolutt verdi (du kan bruke enten punktum eller komma som desimaltegn, oppgi svaret som en positiv verdi)

## Beregningsoppgave 2 - Livsløpsanalyse 15 poeng

Vi bruker samme flytskjema som i forrige oppgave, men med en noe endret teknologi-matrise. (Amatrise). De ulike prosessene leverer som før tonn stål (P1, stålverk), kWh strøm (P2, vindkraftverk), $m 3$ betong ( $P 3$, betongproduksjon), og tonn-km transport (P4, jernbanetransport). Flytskjema er slik:

Samme flytskjema som i sted

Vi bruker følgende A-matrise:

|  | P1 (stål) | P2 (strøm) | P3 (betong) | P4 (jernb.tr.) |
| :--- | :--- | :--- | :--- | :--- |
| P1 | 1 | -0.0001 | 0 | -0.0001 |
| P2 | -300 | 1 | -1000 | -1.0 |
| P3 | 0 | -0.0002 | 1 | -0.0001 |
| P4 | -250 | 0 | -100 | 1 |

Du er gitt at de direkte klimautslippene fra hver prosess per produsert enhet er slik:

|  | P1, per tonn | P2, per kWh | P3, per m3 | P4, per tonn-km |
| :--- | :--- | :--- | :--- | :--- |
| kg CO2 | 1200 | 0.005 | 500 | 0.05 |

Regn ut livsløpsutslippene i $\mathrm{kg} \mathrm{CO}_{2}$ av et samlet sluttforbruk på 15 tonn stål og 2 m3 betong. Oppgi svaret som et heltall: . (svar innenfor +/- 50 godkjennes)

## Beregningsoppgave 3 MFA 6 poeng

Under er et flytskjema for materialstrømsanalyse av stål i byggenæringen, med alle strømmer og systemgrenser tegnet inn. Du vet om dette systemet at:

- I Bygg og anlegg blir $25 \%$ av stålet tapt til annen behandling ut av systemet. Resten går til Avfallsmottak for sortering.
- I Avfallsmottaket blir 5\% av innlevert stål sendt videre til annen behandling, mens resten går som en sortert strøm til omsmelting til nye stålprodukter fra stålverket.
- Vi er gitt at det er 500000 tonn stål som leveres til Avfallsmottak fra bygg og anlegg årlig.

![](https://cdn.mathpix.com/cropped/2024_03_09_279b8ceb610e8e048e06g-3.jpg?height=674&width=1130&top_left_y=263&top_left_x=243)

Du er oppgitt en nesten komplett koffisientmatrise og y-vektor for dette systemet, det eneste som mangler er materialbalansen for P1 (stålverket). (Merk at dette er for én av oppgaveparallellene).

| $\mathrm{X}_{01}$ | $\mathrm{X}_{12}$ | $\mathrm{X}_{20}$ | $\mathrm{X}_{23}$ | $\mathrm{X}_{30}$ | $\mathrm{X}_{31}$ | $\mathrm{y}$-vektor |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 1 | -1 | -1 | 0 | 0 | 0 |
| 0 | 0 | 0 | 1 | -1 | -1 | 0 |
|  |  |  |  |  |  |  |
| 0 | 0 | 0 | -0.05 | 1 | 0 | 0 |
| 0 | 0 | 0 | 1 | 0 | 0 | 500000 |

Gjør matrisen ferdig og regn ut størrelsen på strømmen x01, det vil si systemets import av nytt stål. Skriv svaret som et helsiffer i tonn/år: . (svar innenfor +/- 50 godkjennes).

