# Eksamen Jupyter notebook 

Denne delen representerer $24 \%$ av eksamen.

Pass på å levere eksamensbesvarelsen ved å trykke "submit", på samme måte som du har gjort i de andre innleveringene i emnet. Husk også på å svare ut spørsmålet i Inspera hvorvidt du har levert eller ikke.

Vi har ikke mulighet å gi poeng for oppgavesett som ikke er levert ("submit") innenfor eksamenstiden, inkludert utvidet eksamenstid for de det gjelder.

Opplever du problemer med å submit, vær vennlig og vent 5 minutt og prøv igjen. Vi vil følge overbelastning på server og utvide innleveringstiden om nødvendig.

Hvis dere gjør beregninger utenom JupyterHub må dere legge merke til at rettingen legger til grunn rett svar innenfor minst 2 siffer etter komma. Det vil for eksempel si at dere må skrive svaret som num_a $=1.11$ og ikke num_a $=1.1$.

## Kjør cellen nedenfor før du starter eksamen

In $[1]:$

![](https://cdn.mathpix.com/cropped/2024_03_11_add17adf2f972e711d87g-1.jpg?height=464&width=1596&top_left_y=1255&top_left_x=405)

## Oppgave 1: LCA for produksjon av vindmølle

## Kjør cellen nedenfor for å generere oppgaven

In [2]: $\quad$ H

from meta import assignments assignments ( ).getAssignment (assignment_num=1)

Out [2]: Ta utgangspunkt i følgende tre prosesser, henholdsvis produksjon av strøm, stål og vindmøller. Mer informasjon om de enkelte prosessene følger under flytskjema.
![](https://cdn.mathpix.com/cropped/2024_03_11_add17adf2f972e711d87g-2.jpg?height=1114&width=832&top_left_y=430&top_left_x=478)

Informasjon til oppgaven:

- Prosess 1 krever $n_{21}=3000 \mathrm{~kg}$ stål for å produsere $n_{1}=98000 \mathrm{kWh}$ strøm, og dette innebærer et vannforbruk på $w_{1}=14700 \mathrm{~m} 3$ vann og et direkteutslipp fra P1 på $q_{1}=93 \mathrm{~kg}$ NOx og $p_{1}=4900 \mathrm{~kg}$ CO2.
- Prosess 2 (P2) krever $n_{12}=98000 \mathrm{kWh}$ strøm fra P1 for å produsere $n_{2}=140000 \mathrm{~kg}$ stål. I produksjon av dette stålet er det et vannforbruk på $w_{2}=0 \mathrm{~m} 3$ vann og et utslipp på $q_{2}=255 \mathrm{~kg}$ NOx og $p_{2}=13400 \mathrm{~kg}$ CO2.
- For at P3 skal levere 25 vindmøller, krever prosessen innsats av $n_{13}=14000 \mathrm{kWh}$ strøm og $n_{23}=140000 \mathrm{~kg}$ stål, og et forbruk av $w_{3}=2800 \mathrm{~m} 3$ vann, og et utslipp på $q_{3}=285 \mathrm{~kg}$ NOx og $p_{3}=15000 \mathrm{~kg} \mathrm{CO} 2$.
a) (5 poeng) Ferdigstill teknologimatrisen for prosessnettverket ved å fylle inn de tomme cellene $\mathrm{i}$ matrisa under (technology matrix, kalt A) ut fra den informasjonen du er gitt. Behold rekkefølge i rader og koloner. Angi svaret som matrisen A .

![](https://cdn.mathpix.com/cropped/2024_03_11_add17adf2f972e711d87g-3.jpg?height=260&width=529&top_left_y=317&top_left_x=928)

Husk at for å lage en $3 \times 3$ matrise bruker du $A=n p$. array $([[1,2,3],[4,5,6],[7,8$, 9] ]) . Du kan se på matrisen ved å skrive $\operatorname{print}(A)$.

In [3]: $\quad$ n $21=3000 \quad \#$ randomisert

$\mathrm{n} 12=98000 \quad \#$ randomisert

$\mathrm{n} 23=140000$ \# randomisert

$\mathrm{n} 13=14000 \quad \#$ randomisert

$\mathrm{n} 1=\mathrm{n} 12$

$\mathrm{n} 2=\mathrm{n} 23$

$A=n p \cdot \operatorname{array}([[n 1,-n 12,-n 13], \#$ strom

$[-\mathrm{n} 21, \mathrm{n} 2,-\mathrm{n} 23]$, \# stal

$[0,0,25]])$ \# vindmoller

## Kjør cellen nedenfor for å sjekke formatering

In [4]: $\quad$ assert type(A)== np.ndarray, 'Svaret må være en np.array() matrise' assert np.shape $(A)==(3,3)$, 'Matrisen må ha formen $(3,3)^{\prime}$

b) (5 poeng) Ferdigstill intervensjonsmatrisen for prosessnettverket ved å fylle inn de tomme cellene i matrisa under (intervention matrix, kalt B). Merk at ressursuttak noteres som negative verdier. Behold rekkefølge i rader og koloner. Angi svaret som matrisen B .

|  | P1 | P2 | P3 |
| ---: | ---: | ---: | ---: |
| Vann $\left(\mathrm{m}^{3}\right)$ | $-w_{1}$ | $?$ | $?$ |
| $\mathrm{NO}_{\mathrm{x}}(\mathrm{kg})$ | $?$ | $q_{2}$ | $?$ |
| $\mathrm{CO}_{2}(\mathrm{~kg})$ | $?$ | $?$ | 15000 |

In $[5]$ :

$$
\begin{aligned}
& \mathrm{w} 1=14700 \# \text { randomisert } \\
& \mathrm{q} 1=93 \quad \# \text { randomisert } \\
& \text { p1 }=4900 \quad \# \text { randomisert } \\
& \mathrm{w} 2=0 \quad \text { \# randomisert } \\
& \mathrm{q} 2=255 \quad \# \text { randomisert } \\
& \text { p2 }=13400 \# \text { randomisert } \\
& \text { w3 }=2800 \quad \# \text { randomisert } \\
& \text { q3 }=285 \quad \# \text { randomisert } \\
& \text { p3 }=15000 \# \text { randomisert } \\
& B=n p \cdot \operatorname{array}([[-w 1,-w 2,-w 3], \# v a n n \\
& {[q 1, q 2, q 3] \text {, \#nox }} \\
& [p 1, p 2, p 3]]) \# c o 2
\end{aligned}
$$

## Kjør cellen nedenfor for å sjekke formatering

In [6]: $\quad$ K

assert type(B)== np.ndarray, 'Svaret må være en np.array() matrise' assert np.shape $(B)==(3,3)$, 'Matrisen må ha formen $(3,3)$ '

c) (5 poeng) Bruk teknologimatrisa $\mathrm{A}$ og intervensjonsmatrisa $\mathrm{B}$ til å regne ut livsløpsutslippene av NOx forbundet med produksjon av 1 vindmølle. Angi svaret som variabelen nox_vindmolle .

Merk at vi spør etter en variabel og ikke vektoren r. Nyttige funksjoner for denne oppgaven er:

- Opprette en kolonnevektor: $f=n p$. array ([[1], [2], [3] ] )
- Matrisemultiplikasjon: A@B
- Inverstransformasjon $\left(A^{-1}\right)$ : np.linalg.inv(A)

Hver plass $\mathrm{i}$ en matrise har et tilegnet nummer. For en $2 \times 2$ matrise definert som $\mathrm{L}=$ np.array $([[11,12],[13,14]]$ ) er for eksempel $L[0,0]=11, L[0,1]=12$ osv.

In [7]: $\quad \mathrm{f}=\mathrm{np} . \operatorname{array}([[\theta],[\theta],[1]])$

$r=B @ n p . l i n a l g . i n v(A) @ f$

nox_vindmolle $=r[1,0]$

## Kjør cellen nedenfor for å sjekke formatering

In [8]: $\quad$ assert (type(nox_vindmolle) in [int, float, np.int64, np.float64]), 'Svaret m

## Oppgave 2: Materialstrømsanalyse for bruer

## Kjør cellen nedenfor for å generere oppgaven

In $[9]$ :

from meta import assignments

assignments ().getAssignment(assignment_num=2)

Out [9]: Vi skal i denne oppgaven se på materialstrømmene for produksjonen av bruer. Det er et tenkt system for en norsk bruprodusent som lager kassebruer i aluminium. Bruene er designet for å fungere som midlertidige installasjon i påvente av oppgradering eller i forbindelse med veiutbygging. Bruene har ulik dimensjon, men vi antar her at de er i en «standard» brustørrelse for tofelts-veg ( 8 meter bred) og samlet spenn på 30 meter.

Vi begynner med prosessen for produksjon (P1), som kan antas å levere 68 slike standardbruer hvert år fra produksjon (P1) til installasjon (P2). I hver bru er det 29 tonn aluminium. Videre er det gitt at:

- $81 \%$ av aluminium inn i P1 ender som material i en bru som blir solgt (til P2). Resten av aluminium i P1 sorteres og sendes til gjenvinning (i P3).
- I produksjonen av bruer benyttes det $50 \%$ gjenvunnet material (fra P3), og resten er import til systemet av nyprodusert aluminium.

Vi legger til grunn at det ikke er akkumulering $i$ systemet og du kan anta at materialsammensetningen er lik for alle utstrømmer fra P1. Et flytskjema for aluminiumsstrømmene er vist under.

![](https://cdn.mathpix.com/cropped/2024_03_11_add17adf2f972e711d87g-5.jpg?height=609&width=1499&top_left_y=1235&top_left_x=497)

a) (5 poeng) Hvor mye nytt aluminium trenger produsenten i P1 årlig? Dette er i flytskjema identifisert som $\mathrm{x} 01$.

Angi svaret med variabelen m_ny , i enheter tonn/år.

![](https://cdn.mathpix.com/cropped/2024_03_11_add17adf2f972e711d87g-5.jpg?height=208&width=769&top_left_y=2173&top_left_x=193)

Kjør cellen nedenfor for å sjekke formatering

In $[11]:$ assert (type(m_ny) in [int, float, np.int64, np.float64]), 'Svaret må være et assert (m_ny $>0$ ), 'Svaret må være en positiv verdi'

b) (4 poeng) Ferdigstill balanseligningene for de tre prosessene ved å fylle inn de tomme cellene i matrisa under.

Uttrykk (definer) svaret gjennom matrisen A_bal . Bruk rekkefølger i kolonner og rader som gitt i følgende matrise, og merk at noen tallverdier er ført inn allerede.

|  | $\mathbf{x 0 1}$ | $\mathbf{x 1 2}$ | $\times 13$ | $\times 31$ | $\times 20$ | $\times 23$ | $\times 03$ |
| ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| P1 | 1 | $?$ | $?$ | $?$ | $?$ | $?$ | $?$ |
| P2 | $?$ | 1 | $?$ | $?$ | $?$ | $?$ | $?$ |
| P3 | $?$ | $?$ | 1 | $?$ | $?$ | $?$ | $?$ |

In [12]: $\quad$ A_bal $=$ np.array $([[1,-1,-1,1,0,0,0], \# P 1$

$[\theta, 1,0, \theta,-1,-1,0], \# P 2$

$[0,0,1,-1,0,1,1]])$ \#P3

## Kjør cellen nedenfor for å sjekke formatering

In [13]: $\quad$ assert type(A_bal) == np.ndarray, 'Svaret må være en np.array() matrise' assert np.shape(A_bal) $==(3,7)$, 'Matrisen må ha formen $(3,7)^{\prime}$

In [ ]: $\mathrm{M}$

