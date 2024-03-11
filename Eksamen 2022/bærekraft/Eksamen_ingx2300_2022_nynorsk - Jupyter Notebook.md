# Eksamen Jupyter notebook 

Denne delen representerer $24 \%$ av eksamen. Det er fire spørsmål kvar verd 6 poeng. I del a) er det 1.5 p for kvar av dei fire variablane.

Viss de gjer utrekningar utanom JupyterHub må de legga merke til at rettingen legg til grunn rett svar innanfor minst 2 siffer etter komma. Det vil til dømes seia at de må skriva svaret som num_a $=1.11$ og ikkje num_a $=1.1$.

![](https://cdn.mathpix.com/cropped/2024_03_11_b1e9c9c31b1276d8a475g-1.jpg?height=503&width=1552&top_left_y=586&top_left_x=449)

## Oppgave 1: livsløpsvurdering (LCA)

## Køyr cella nedanfor for å generera oppgåva

In [2]: $\quad$ from meta import assignments assignments ().getAssignment (assignment_num=1)

Out [2]: Ta utgangspunkt i følgjande prosessnettverk, der det er tre prosessar for høvesvis produksjon av metall, straum og dingsar.

![](https://cdn.mathpix.com/cropped/2024_03_11_b1e9c9c31b1276d8a475g-2.jpg?height=449&width=1491&top_left_y=365&top_left_x=531)

Legg merke til at prosess 2 produserer straum for både prosess 1 og prosess 3.

Figuren inneheld fire udefinerte variable; num_a, num_b, num_c og num_d. Du kan bruka følgjande informasjon:

- Prosess 2 krev ein direkteinnsats på $0.09 \mathrm{~kg}$ metall per kWh produsert.
- Prosess 3 har eit direkteutslipp på $0.25 \mathrm{~kg}$ CO2 per kg dingsar.
- Prosess 1 har eit direkteutslipp på $1.4 \mathrm{~kg}$ CO2 per kg metallmalm som blir prosessert.
- Prosess $3 \mathrm{krev}$ ein direkteinnsats på $1.0 \mathrm{~kg}$ metal per kg dingsar.

a) Oppgi verdi for num_a, num_b, num_c og num_d, altså for dømes slik at num_a = tallverdi .

In [3]: $\quad$ num_a $=(0.1-0.09) / 0.09$

num_b $=0.25$

num_c $=10 * 1.4$

num_d $=1$

## Køyr cellene nedanfor for å sjekka formatering

In [4]: N assert (type(num_a) in [int, float, np.int64, np.float64]), 'Svaret må vera eit enkelt tal'

In $[5]:$

b) Ferdigstill teknologimatrisen for prosessnettverket ut frå den informasjonen som er gitt (technology matrix, kalla A). Behald rekkefølgje i rader og kolonnar. Uttrykk (definer) svaret gjennom matrisen A.

|  | P1 | P2 | P3 |
| ---: | ---: | ---: | ---: |
| Metall $(k g)$ | $0.1+$ num_d | -0.1 | $?$ |
| Strøm $(k W h)$ | -1 | 1+num_a | $?$ |
| Dingsar $(k g)$ | 0 | 0 | $?$ |

Hugs at for å laga ein $3 \times 3$ matrise bruker du $A=n p$. array ( $[1,2,3],[4,5,6],[7,8,9]])$. Du kan sjå på matrisen ved å skriva print(A).

In $[8]:$

![](https://cdn.mathpix.com/cropped/2024_03_11_b1e9c9c31b1276d8a475g-3.jpg?height=158&width=877&top_left_y=1156&top_left_x=410)

## Køyr cella nedanfor for å sjekka formatering

In [9]: $\quad$ assert type(A)== np.ndarray, 'Svaret må vera ein np.array() matrise' assert np.shape $(A)==(3,3)$, 'Matrisen må ha forma $(3,3)$ '

c) Ferdigstill intervensjonsmatrisen for prosessnettverket ut fra den informasjonen som er gitt (intervention matrix, kalt B). Behold rekkefølge i rader og koloner. Uttrykk (definer) svaret gjennom matrisen B.

![](https://cdn.mathpix.com/cropped/2024_03_11_b1e9c9c31b1276d8a475g-3.jpg?height=116&width=544&top_left_y=1850&top_left_x=1236)

![](https://cdn.mathpix.com/cropped/2024_03_11_b1e9c9c31b1276d8a475g-4.jpg?height=79&width=579&top_left_y=94&top_left_x=1201)

$\mathrm{CO}_{2}(\mathrm{~kg})$ num_c $\quad 0.5 \quad ?$

Husk at for å lage en $3 x 2$ matrise bruker du $B=n p$. array ( $[1,2,3],[4,5,6]])$. Du kan se på matrisen ved å skrive print(B).

In $[10]$ :

$\quad \mathbf{B}=$ np.array $([[-10,0,0]$,
$[$ num_c, 0.5, num_b]])

## Køyr cella nedanfor for å sjekka formatering

In [11]:

M assert type(B)== np.ndarray, 'Svaret må vera ein np.array() matrise'

assert np.shape $(B)==(2,3)$, 'Matrisen må ha forma $(2,3)$ '

d) Bruk matrisane til å rekna ut livsløpsutsleppa av $\mathrm{CO}_{2}$ forbundet med produksjon av $1 \mathrm{~kg}$ dingsar. Uttrykk (definer) svaret gjennom variabelen co2_dingser. Merk at vi spør etter ein variabel og ikkje vektoren $r$.

Nyttige funksjonar er for denne oppgåva er:

- Oppretta ein kolonnevektor: $f=n p$. array ([[1], [2], [3] ] )
- Matrisemultiplikasjon: А@B
- Inverstransformasjon $\left(A^{-1}\right)$ : np.linalg.inv(A)

Kvar plass $i$ ein matrise og ein vektor har eit tileigna nummer. For ein $2 \times 2$ matrise definert som $L=n p \cdot \operatorname{array}([[1,2],[3,4]]$ ) er til dømes $L[\theta, \theta]=1, L[\theta, 1]=2$ osb.

In $[12]:$

![](https://cdn.mathpix.com/cropped/2024_03_11_b1e9c9c31b1276d8a475g-4.jpg?height=149&width=648&top_left_y=1566&top_left_x=416)

## Køyr cella nedanfor for å sjekka formatering

In [13]: $\quad$ assert (type(co2_dingser) in [int, float, np.int64, np.float64]), 'Svaret må vera eit enkelt tal'

