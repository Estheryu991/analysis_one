folgen und summe:


Kapitel 2
Folgen und endliche
Summen
• Folgen und ihre Eigenschaften
• Endliche arithmetische und geometrische Folgen und Reihen
• Vollstandige ¨ Induktion
• Anwendungen
Folgen/endliche Summen — Eigenschaften
Folgen
Im Allgemeinen besteht eine Folge aus einer Anordnung (nullter, erster, zweiter . . . Wert) von gewissen
reellen Zahlen. Durch diese Anordnung wird jeder
natur¨ lichen Zahl n ∈ IN genau ein Wert a(n) zugeordnet und eine Reihenfolge festgelegt:
a(0), a(1), a(2), . . .
Definition
Eine Abbildungsvorschrift a : IN → IR mit
a(n) = an heißt (unendliche) Folge. Hierfur¨
schreibt man auch
(an)n∈IN = (an) = a0, a1, a2, . . .
Die reellen Zahlen an heißen Folgenglieder.
Haufig ¨ beginnt die Abbildungsvorschrift nicht mit der
Zahl Null, sondern mit der Eins. Daher benutzen
wir das Symbol IN+ := IN\{0} fur¨ die Menge der
positiven natur¨ lichen Zahlen.
Mathematik kompakt 1
Folgen/endliche Summen — Eigenschaften
Beispiel
a) Die Folge 1, 3, 5, 7, . . . der ungeraden natur¨ lichen Zahlen kann man schreiben als
a0 = a(0) = 1, a1 = a(1) = 3,
a2 = a(2) = 5, a3 = a(3) = 7,
usw. Das Bildungsgesetz fur¨ die Folgenglieder
lautet offensichtlich
an = a(n) = 2n + 1.
Statt die Folge — wie eingangs — durch Aufzahlung ¨ ihrer Glieder zu definieren, konnen ¨ wir
daher auch (2n+1)n∈IN (Definition mittels Abbildungsvorschrift) schreiben.
b) Die Folge 1
3
, 2
3
, 3
3
, . . . lasst ¨ sich auch durch
(n
3)n∈IN+
angeben.
c) Die alternierende, nur aus zwei Werten bestehende Folge 1, −1, 1, −1 . . . kann durch das
Bildungsgesetz an = (−1)n
, n ∈ IN, definiert
werden.
Mathematik kompakt 2
Folgen/endliche Summen — Eigenschaften
Umgebung eines Punktes
Zur Untersuchung von Grenzwerteigenschaften von
Folgen, benotigt ¨ man Kenntnisse uber ¨
”
Abstandsverhalten“ von Folgengliedern.
Abstand zweier reeller Zahlen x und a: |x − a|.
Die Menge aller Punkte x ∈ IR, die von einem Punkt
a einen Abstand kleiner als eine vorgegebene Zahl
ε haben, bilden eine Umgebung von a.
Definition
Fur¨ ε > 0 ist die ε-Umgebung von a definiert durch
Uε(a) := {x ∈ IR | |x − a| < ε}
= {x ∈ IR | a − ε < x < a + ε}.
Mit a = 0 und ε = 1 ergibt sich U1(0) zu
❢ ❢ ✲ x
−1 0 1
Mathematik kompakt 3
Folgen/endliche Summen — Eigenschaften
Konvergenzbegriff
Der Konvergenzbegriff lasst ¨ sich exemplarisch an
der Folge 
− 1
2n

n∈IN+
= −1
2
, −1
4
, −1
6
, . . . und deren Visualisierung studieren:
-1/2 -1/4 -1/6 -1/8 0
x
a4
a3
a2
a1
Die Folge hat die Eigenschaften:
a) Mit zunehmenden n werden die Folgenglieder
an großer ¨ und unterscheiden sich dabei immer
weniger von der Zahl 0.
b) In jeder noch so kleinen Umgebung der Zahl
0 (Uε(0), ε beliebig klein gewahlt!) ¨ liegen fast
alle Glieder der Folge.
D.h. nur endlich viele Glieder liegen außerhalb
der vorgegebenen Umgebung.
Mathematik kompakt 4
Folgen/endliche Summen — Eigenschaften
Konvergenzbegriff — Fortsetzung
• Beispielsweise liegen in U1/6
(0) alle Folgenglieder mit Ausnahme der ersten drei,
• in U1/100(0) alle mit Ausnahme der ersten funf- ¨
zig (|a51| < 1/100),
• in U1/1000(0) alle mit Ausnahme der ersten
funfhunder ¨ t (|a501| < 1/1000), usw.
Fast alle Folgenglieder bedeutet somit: alle mit Ausnahme von endlich vielen.
Fur¨ unsere Folge gilt fur¨ fast alle n ∈ IN+
an ∈ Uε(0) bzw.



−
1
2n
− 0




< ε. (∗)
Bei jeder Wahl fur¨ ε liegen nur endlich viele Folgenglieder außerhalb von Uε(0). Die Ungleichung (∗)
1/(2n) < ε kann aquiv ¨ alent umgeformt werden in
n > 1/(2ε).
Diese Ungleichung wird bereits von der kleinsten
Zahl n0 ∈ IN erfullt, ¨ die großer ¨ als 1/(2ε) ist.
Mathematik kompakt 5
Folgen/endliche Summen — Eigenschaften
Konvergenz bzw. Divergenz einer Folge
Fast alle bedeutet auch: mindestens alle ab einem
bestimmten Index n0.
So wie sich unsere Beispielfolge der Zahl 0 naher ¨ t,
kann sich eine Folge i. Allg. natur¨ lich einer beliebigen Zahl a ∈ IR naher ¨ n.
Definition
Die Folge (an) heißt konvergent mit dem
Grenzwert (oder Limes) a, falls zu jedem
ε > 0 eine naturlic ¨ he Zahl n0 existiert,
so dass fur¨ alle n ≥ n0, n ∈ IN, gilt
|an−a| < ε. Man schreibt dann symbolisch
(mit sog. Limeszeichen oder einfacher):
n
lim
→∞
an = a oder an → a.
Ist a = 0, so heißt (an) Nullfolge. Existiert keine derartige Zahl a, dann heißt (an)
divergent.
Mathematik kompakt 6
Folgen/endliche Summen — Eigenschaften
Beispiel
a) Egal, welches beliebige ε man sich auch vorgibt, fur¨ die Folge

−
1
2n

n∈IN+
findet man immer ein geeignetes n0, namlich ¨
n0 > 1/(2ε). Somit gilt
| − 1/(2n) − 0| < ε
fur¨ n > n0, also ist die Folge konvergent mit
dem Grenzwert 0, d.h. eine Nullfolge.
b) Auch die durch
an =
1
n
, n ∈ IN+,
definierte Folge ist eine Nullfolge. Die Existenz
der Zahl n0 ergibt sich direkt aus der Umformung von Gleichung
|1/n − 0| < ε
zu n > 1/ε. Fur¨ jede natur¨ liche Zahl großer ¨ als
1/ε ist somit |an − a| < ε erfullt. ¨
Mathematik kompakt 7
Folgen/endliche Summen — Eigenschaften
Ub¨ ung
Durch das Bildungsgesetz
an =
2n − 1
3n + 7
sei die Folge (an)n∈IN definiert.
a) Bestimmen Sie die ersten funf ¨ Folgenglieder.
Wie lauten a100 und a1000?
b) Ist 2/3 = 0.6 Grenzwert dieser Folge?
Bestimmen Sie zu ε = 10−3 ein entsprechendes n0.
Mathematik kompakt 8
Folgen/endliche Summen — Eigenschaften
Losung ¨
a) Die ersten funf ¨ Folgenglieder lauten
a0 = −
1
7
, a1 =
1
10
, a2 =
3
13
, a3 =
5
16
,
und a4 = 7
19. Ferner ist a100 = 199
307 ≈ 0.6482
und a1000 = 1999
30007 ≈ 0.6648.
b) Wir mussen ¨ zu jedem beliebig vorgegebenen
(noch so kleinen) ε > 0 eine (natur¨ lich von ε
abhangige) ¨ Zahl n0 finden, so dass |an−2
3
| < ε
fur¨ alle n > n0 gilt. Dazu beachten wir




2n − 1
3n + 7
−
2
3




=





6n − 3 − 6n − 14
3(3n + 7)





=
17
3(3n + 7) < ε,
woraus sich n > 1
3

17
3ε − 7

ergibt. Ist nun z.B.
ε = 10−3 gegeben, dann muss n > 1886.56
gelten. D.h., dass alle Glieder ab dem 1887.
Glied von 2
3
einen Abstand haben, der kleiner
als 10−3 ist. Das gesuchte n0 ist damit n0 =
1887.
Mathematik kompakt 9
Folgen/endliche Summen — Eigenschaften
Eindeutigkeit des Grenzwertes
Jede Folge (an) besitzt hochstens ¨ einen Grenzwert.
Denn waren ¨ b > a zwei verschiedene Grenzwerte
von (an), so setze man
ε =
b − a
2
.
Dann gilt fur¨ die ε-Umgebungen
Uε(a) ∩ Uε(b) = ∅.
a b
IR
a- a+ =b- b+
U (a) U (b)
Da a Grenzwert ist, liegen aber alle bis auf endlich
viele Folgenglieder in Uε(a). Somit befinden sich in
Uε(b) nur endlich viele Folgenglieder, also kann b
kein Grenzwert sein.
Mathematik kompakt 10
Folgen/endliche Summen — Eigenschaften
Divergente Folgen
Es gibt auch Folgen, die keinen Grenzwert besitzen.
Beispielsweise hat die Folge an = (−1)n keinen
Grenzwert, da unendlich viele Folgenglieder gleich
1 (a0, a2, a4, . . .), aber auch unendlich viele gleich
−1 (a1, a3, a5, . . .) sind. In keiner Umgebung Uε(1)
bzw. Uε(−1) liegen also fast alle Folgenglieder.
Die Folge an = n
3 zeigt ein interessantes Verhalten: Ihre Folgenglieder werden immer großer ¨ , schließlich ”
beliebig groß“. Mathematisch kann man dies
wie folgt ausdruc¨ ken:
Sei M > 0 eine reelle Zahl, dann sind nur endlich
viele Folgenglieder kleiner als M. Fast alle Glieder,
namlich ¨ diejenigen an mit n >
√3 M sind großer ¨ als
M. Da die Wahl von M dabei belanglos ist, hat man
die Aussage:
Fur¨ alle M > 0 gilt, dass fast alle Folgenglieder
großer ¨ als M sind.
Mathematik kompakt 11
Folgen/endliche Summen — Eigenschaften
Bestimmte Divergenz
Definition
Wenn fur¨ eine Folge (an) die Aussage
”
Fur¨
alle M > 0 bzw. M < 0 gilt, dass fast alle
Glieder an großer ¨ bzw. kleiner als M sind“
erfullt ¨ ist, dann nennt man sie bestimmt divergent mit dem uneigentlichen Grenzwert
∞ bzw. −∞. Man schreibt dann
n
lim
→∞
an = ∞ bzw.
n
lim
→∞
an = −∞.
Mathematik kompakt 12
Folgen/endliche Summen — Eigenschaften
Beschranktheit ¨ und Monotonie
Weitere wichtige Eigenschaften, mit deren Hilfe man
Konvergenzuntersuchungen durchfuhren ¨ kann, seien nachfolgend definiert:
Definition
Eine Folge (an) heißt nach oben bzw. nach
unten beschrankt, ¨ falls es eine Zahl Mo
bzw. Mu gibt, mit
an ≤ Mo bzw. an ≥ Mu fur¨ alle n ∈ IN.
Eine Folge heißt beschrankt, ¨ falls sie sowohl nach oben als auch nach unten beschrankt ¨ ist.
Folgen, fur¨ deren Glieder
an+1 ≥ an bzw. an+1 ≤ an
fur¨ alle n ∈ IN gilt, nennt man monoton
wachsend bzw. monoton fallend.
Mathematik kompakt 13
Folgen/endliche Summen — Eigenschaften
Monotoniekriterium
Damit lasst ¨ sich nun ein wichtiges Ergebnis, das wir
hier nicht beweisen wollen, formulieren:
Eine monoton wachsende, nach oben beschrankte ¨ bzw. monoton fallende, nach unten beschrankte ¨ Folge ist konvergent.
Mathematik kompakt 14
Folgen/endliche Summen — Eigenschaften
Beispiel
Die bereits untersuchte Folge
(an) =

−
1
2n

, n ∈ IN+,
ist wegen
−
1
2(n + 1) > −
1
2n
monoton wachsend.
Da sie durch die Zahl 0 nach oben beschrankt ¨ ist,
konvergiert sie.
Wir haben schon gezeigt, dass sie eine Nullfolge ist.
Mathematik kompakt 15
Folgen/endliche Summen — Eigenschaften
Beispiel
Wir zeigen jetzt die wachsende Monotonie der durch
das Bildungsgesetz
an =

1 +
1
n
n
, n ∈ IN+,
definierten Folge. Dazu benutzen wir, dass hier
an > an−1 zu
an
an−1
> 1
aquiv ¨ alent ist:
an
an−1
=

n + 1
n
n
·

n − 1
n
n−1
=
(n + 1)n
nn
·
(n − 1)n
nn
·
n
n − 1
=

n
2 − 1
n2
!n
·
n
n − 1
=

1 −
1
n2
n
·
n
n − 1
.
Anwendung der Bernoulli-Ungleichung liefert

1 −
1
n2
n
> 1 −
1
n
und damit gilt
an
an−1
>

1 −
1
n

·
n
n − 1
=
n − 1
n
·
n
n − 1
= 1.
Mathematik kompakt 16
Folgen/endliche Summen — Eigenschaften
Beispiel — Fortsetzung
Somit ist die wachsende Monotonie gezeigt.
Man kann sogar beweisen, dass die Folge durch
den Wert Mo = 3 nach oben beschrankt ¨ ist. Nach
dem Monotoniekriterium konvergiert die Folge daher.
Mittels tiefer gehender Untersuchungen lasst ¨ sich
dieser Grenzwert ermitteln:
Es gilt:
n
lim
→∞


1 +
1
n


n
= e ≈ 2.7182818.
Der Grenzwert der Folge ist die wichtige Euler’sche
Zahl e.
Mathematik kompakt 17
Folgen/endliche Summen — Eigenschaften
Maximum, Minimum und Infimum, Supremum
Wenn man von der Reihenfolge der Folgenglieder
abstrahiert, so kann eine Folge auch als eine Menge reeller Zahlen aufgefasst werden. Besitzt diese
Zahlenmenge einen großten ¨ bzw. kleinsten Wert, so
nennt man diesen Maximum bzw. Minimum.
Zur Folge an = 1
n
gehor¨ t die Menge
{
1
n
| n ∈ IN+}.
Das Maximum ist die 1 (a1 = 1!), wahrend ¨ offensichtlich ein Minimum nicht existiert.
Die Folge ist aber z.B. durch die Werte −100, −10
oder 0 nach unten beschrankt. ¨
Die großte ¨ untere Schranke — in unserem Beispiel
die 0 — nennt man das Infimum der Folge.
Die kleinste obere Schranke bezeichnet man als Supremum. In unserem Beispiel sind Supremum und
Maximum identisch gleich 1.
Mathematik kompakt 18
Folgen/endliche Summen — Eigenschaften
Grenzwertregeln
Fur¨ die Bildung von Grenzwerten gelten gewisse
Rechenregeln, die es erlauben, von den Grenzwerten einfacher Folgen — etwa (an), (bn) — auf die
Grenzwerte komplizierter Folgen, wie z.B. Summenfolge (an+bn) oder Produktfolge (an·bn), zu schließen:
Fur¨ zwei konvergente Folgen (an) und (bn)
mit den Grenzwerten a und b gilt:
n
lim
→∞(an + bn) = a + b,
n
lim
→∞(an − bn) = a − b,
n
lim
→∞(an · bn) = a · b,
n
lim
→∞(c · an) = c · a, c ∈ IR const.
n
lim
→∞


an
bn


=
a
b
, falls bn 6= 0, b 6= 0.
Mathematik kompakt 19
Folgen/endliche Summen — Eigenschaften
Grenzwertregeln bei bestimmter Divergenz
Ist eine der Folgen (an), (bn) bestimmt divergent,
z.B. limn→∞ bn = ∞, dann gelten ahnliche ¨ Rechenregeln ( dabei soll ∞ keine Zahl sein, sondern
ein Symbol fur¨ bestimmte Divergenz):
”
a ± ∞ = ±∞“
,
”
a · ∞ = ±∞“
,
”
a
∞
= 0“
,
”
∞
a
= ±∞“.
Ferner gilt auch
”
∞ · ∞ = ∞
“.
Man beachte aber, dass
”
∞ − ∞, 0 · ∞,
0
0
,
∞
∞
, 0
0
; 1∞“
(0 steht dabei als Symbol fur¨ limn→∞ an = 0) unbestimmte Formen sind und bei jedem Auftreten eine eigene Untersuchung erfordern.
Es gilt lediglich (falls b 6= 0)
”
b
0
= ±∞“.
Mathematik kompakt 20
Folgen/endliche Summen — Eigenschaften
Beispiel
a) Da wir bereits wissen, dass
lim
n→∞
1
n
= 0
ist, konnen ¨ wir nun schließen:
lim
n→∞
1
n2
= lim
n→∞
1
n
· lim
n→∞
1
n
= 0 · 0 = 0.
b) Um den Grenzwert der durch
an =
4 − n
2n − 1
definierten Folge zu bestimmen, benutzen wir
limn→∞
1
n
= 0 und erhalten
lim
n→∞
4 − n
2n − 1
= lim
n→∞
n
n
·
(4/n) − 1
2 − 1/n
=
4 · 0 − 1
2 − 0
= −
1
2
.
Mathematik kompakt 21
Folgen/endliche Summen — Eigenschaften
Ub¨ ung
a) Wie lautet der Grenzwert der Folge

n + 1
n

n∈IN+
?
b) Unter Verwendung von Teil a) bestimme man
den Grenzwert der durch
an =
n
n + 1
, n ∈ IN+,
definierten Folge.
Mathematik kompakt 22
Folgen/endliche Summen — Eigenschaften
Losung ¨
a) Es ist
lim
n→∞
n + 1
n
= lim
n→∞
1+ lim
n→∞
1
n
= 1+0 = 1.
b) Es gilt
an =
1
bn
mit bn =
n + 1
n
.
Aus Teil a) wissen wir bereits, dass
lim
n→∞
bn = 1
ist. Aus den Grenzwertregeln folgt daher sofort
lim
n→∞
an =
1
limn→∞ bn
= 1.
Mathematik kompakt 23
Folgen/endliche Summen — Eigenschaften
Wichtige Grenzwerte
Ohne Beweise fuhren ¨ wir einige Grenzwerte von Folgen auf, deren Kenntnis fur¨ spatere ¨ Anwendungen
wichtig ist:
Es seien c ∈ IR eine Konstante und q eine
reelle Zahl mit |q| < 1, dann gilt:
n
lim
→∞
√n
c = 1,
n
lim
→∞
√n
n! = ∞,
n
lim
→∞
√n n = 1,
n
lim
→∞ q
n
= 0.
Mathematik kompakt 24
Folgen/endliche Summen — Endliche Folgen
Arithmetische und geometrische Folge
Definition
Eine Zahlenfolge (an) heißt arithmetische
bzw. geometrische Folge, falls die Differenz
k bzw. der Quotient q benachbarter Elemente konstant ist, d.h.
an+1 − an = k bzw.
an+1
an
= q.
Bei der geometrischen Folge ist naturlic ¨ h
an 6= 0 fur¨ alle n ∈ IN erforderlich.
Mathematik kompakt 25
Folgen/endliche Summen — Endliche Folgen
Bildungsgesetze
Unmittelbar aus der Definition folgt:
Arithmetische bzw. geometrische Folgen
besitzen beide jeweils ein einfaches Bildungsgesetz:
an = a0 + n · k bzw. an = a0 · q
n.
Das ”
arithmetische“ Bildungsgesetz erkennt man sofort.
Das ”
geometrische“ Bildungsgesetz folgt wegen
an
an−1
= q
aus
an = an−1q = (an−2q) · q
= (an−3q) · q
2 = . . . = a0q
n
.
Mathematik kompakt 26
Folgen/endliche Summen — Endliche Folgen
Beispiel
a) Durch an = n/2, d.h.
0,
1
2
, 1,
3
2
, 2, . . . ,
ist eine arithmetische Folge mit k = 1
2
definiert.
b) Durch an = 2
n
, d.h.
(an) = 1, 2, 4, 8, 16, . . . ,
ist eine geometrische Folge mit q = 2 gegeben.
Mathematik kompakt 27
Folgen/endliche Summen — Endliche Folgen
Ub¨ ung
Welche Folgen sind durch
a) an = 5n + 3
b) an = (
1
4
)
n
gegeben?
Mathematik kompakt 28
Folgen/endliche Summen — Endliche Folgen
Losung ¨
a) Die Folge (5n + 3)n∈IN, d.h.
3, 8, 13, 18, 23, . . . ,
ist eine arithmetische Folge mit k = 5.
b) Die Folge
1
4
n
n∈IN
,
d.h.
1,
1
4
,
1
16
,
1
64
, . . . ,
ist eine geometrische Folge mit q = 1
4
.
Mathematik kompakt 29
Folgen/endliche Summen — Endliche Reihen
Endliche arithmetische und geometrische
Reihe
Nun kann man endlich viele Glieder der obigen Folgen auch aufsummieren, man spricht dann von endlichen Reihen.
Diese Reihen haben viele praktische Anwendungen.
So benotigt ¨ man sie z.B. bei der Berechnung von
einfachen Zinsen, Zinseszinsen oder Hypothekendarlehen.
Definition
Sind a0, a1, . . . , an−1 Glieder einer endlichen arithmetischen bzw. geometrischen
Folge, dann heißt die Summe
sn := a0 + a1 + . . . + an−1, n ∈ IN+,
endliche arithmetische bzw. geometrische
Reihe.
Mathematik kompakt 30
Folgen/endliche Summen — Endliche Reihen
Das Summenzeichen
Endliche Summen, die aus vielen Summanden bestehen, schreibt man in der Regel bequemer durch
Benutzung des Summenzeichens P
.
So z.B. die Summe sn in der Form
n
X−1
i=0
ai
:= a0 + a1 + . . . + an−1.
Definitionsgemaß¨ ist dabei der Summationsindex i
der Reihe nach durch die Zahlen 0 bis n − 1 zu
ersetzen. Allgemein lasst ¨ sich dann die Summe der
Summanden
am, am+1, . . . , an; n ≥ m,
schreiben als
X
n
i=m
ai
:= am + am+1 + . . . + an.
Mathematik kompakt 31
Folgen/endliche Summen — Endliche Reihen
Wert von endlicher arithmetischer und
geometrischer Reihe
Es gibt einfache Formeln, mit denen man den Wert
der Reihen sofort berechnen kann:
Ist sn := a0+a1+. . .+an−1 eine endliche
arithmetische Reihe, dann gilt:
sn =
n
2
(a0 + an−1).
Ist sn := a0 + a1 + . . . + an−1 eine endliche geometrische Reihe mit dem Quotienten q := ak+1/ak 6= 1, dann gilt:
sn = a0
q
n − 1
q − 1
.
Die Formel fur¨ die arithmetische Reihe lasst ¨ sich mit
einer Idee von Klein-Gauß leicht herleiten.
Mathematik kompakt 32
Folgen/endliche Summen — Endliche Reihen
Formel fur¨ die geometrische Reihe —
Herleitung
Um die Formel fur¨ die geometrische Reihe zu zeigen, benutzen wir deren Bildungsgesetz und erhalten zunachst ¨
sn = a0 + a0q + a0q
2 + . . . + a0q
n−1
.
Multiplikation dieser Gleichung mit q 6= 0 liefert nun
qsn = a0q + a0q
2 + a0q
3 + . . . + a0q
n
.
Subtraktion der vorletzten Gleichung von der letzten
ergibt
qsn−sn = a0q
n−a0 ⇐⇒ sn(q−1) = a0(q
n−1).
Falls q 6= 1 (nicht konstante Folge), konnen ¨ beide
Seiten durch q − 1 dividiert werden. Dies fuhr ¨ t zur
behaupteten Formel:
sn = a0
q
n − 1
q − 1
.
Mathematik kompakt 33
Folgen/endliche Summen — Endliche Reihen
Ub¨ ung
a) Eine endliche arithmetische Reihe besteht aus
10 Elementen. Es ist a0 = 20 und a4 = 40.
Wie lauten k und s10?
b) Ein gemutlicher ¨ Student beschließt, sich durch
die anstehende Prufung ¨ nicht stressen zu lassen. Er hat noch 12 Tage Zeit und will sich folgendermaßen vorbereiten:
Am ersten Tag 1 Minute, am zweiten Tag 2 Minuten, an jedem weiteren Tag will er den Arbeitsaufwand lediglich verdoppeln.
Wie lange ist dann seine Vorbereitungszeit am
12. Tag?
Wie lange ist die gesamte Vorbereitungszeit?
Mathematik kompakt 34
Folgen/endliche Summen — Endliche Reihen
Losung ¨
a) Es muss gelten
40 = a4 = a0 + 4k = 20 + 4k,
woraus k = 20/4 = 5 folgt. Zur Berechnung
der Reihe benotigen ¨ wir zunachst ¨ den letzten
Summanden: a9 = a0+9k = 65. Damit ergibt
sich
s10 =
10
2
(20 + 65) = 425.
b) Es handelt sich um eine geometrische Folge
mit a0 = 1, q = 2 und n = 12. Der Arbeitsaufwand am 12. Tag ist
a11 = a0q
11 = 1 · 2
11 = 2048.
Also lediglich gut 34 Stunden! Deutlich wird hier
das exponentielle Wachstum geometrischer Reihen. Insgesamt muss der Student
s12 = a0
q
12 − 1
q − 1
= 1 ·
2
12 − 1
2 − 1
= 4095
Minuten arbeiten. Dies sind ca. 68 Stunden.
Mathematik kompakt 35
Folgen/endliche Summen — Vollstandige ¨ Induktion
Beweisprinzip der Vollstandig ¨ en Induktion
Um die Gultigkeit ¨ einer Aussage A(n) fur¨
alle naturlic ¨ hen Zahlen n ∈ IN zu beweisen, muss man zweierlei zeigen:
• A(0) ist wahr, d.h. die Aussage gilt fur¨
n = 0 (Induktionsbeginn),
• Aus A(n) folgt A(n + 1), d.h. wenn
die Aussage fur¨ eine beliebige naturli- ¨
che Zahl n gilt, dann gilt sie auch fur¨
die nachfolgende Zahl n+1 (Induktionsschluss).
Der Induktionsbeginn besagt also: A(0) gilt. Durch
den Induktionsschluss folgt, dass die Aussage auch
fur¨ den Nachfolger 1 der Zahl 0 gilt: also A(1). Wiederum durch den Induktionsschluss folgt, dass die
Aussage auch fur¨ den Nachfolger 2 der Zahl 1 gilt:
also A(2), usw. Damit kann man A(n) fur¨ jede beliebige natur¨ liche Zahl n zeigen.
Mathematik kompakt 36
Folgen/endliche Summen — Vollstandige ¨ Induktion
Bemerkungen zum Prinzip der Vollstandig ¨ en
Induktion
• Statt von ”
Induktionsbeginn“ spricht man auch
von ”
Induktionsanfang“ oder ”
Induktionsbasis“;
fur¨ den ”
Induktionsschluss“ sind ebenso die Begriffe
”
Induktionsschritt“ oder ”
Schritt von n auf
n + 1“ gebrauchlich. ¨
• Der Induktionsbeginn muss nicht bei 0 liegen,
auch 1 oder irgendeine andere natur¨ liche (oder
sogar ganze) Zahl sind ub¨ lich.
• Es gibt Moglichk ¨ eiten der Verallgemeinerung:
Man kann etwa im Induktionsschritt von A(0),
A(1), ..., A(n) auf A(n + 1) schließen, also
nicht von einer Zahl auf die nachste ¨ , sondern
von mehreren Vorganger ¨ n aus.
Andererseits gelten Aussagen nur fur¨ alle geraden bzw. ungeraden Zahlen, wenn man von
A(n) auf A(n + 2) im Induktionsschluss folgern kann.
Mathematik kompakt 37
Folgen/endliche Summen — Vollstandige ¨ Induktion
Beispiel
Beweis der folgenden Summenformel:
1 + 2 + 3 + ... + n =
X
n
i=1
i =
n · (n + 1)
2
(∗)
Induktionsbeginn:
Gezeigt wird Formel (∗) fur¨ n = 1.
Fur¨ n = 1 besteht die Summe auf der linken Seite
nur aus einem einzigen Summanden, namlich ¨ der 1.
Auf der rechten Seite ergibt n(n+1)
2
nach Einsetzen
von n = 1 ebenfalls
1 · (1 + 1)
2
=
1 · 2
2
= 1,
womit dann die Formel (∗) fur¨ n = 1 bewiesen
ware ¨ .
Induktionsschluss:
Wir setzen jetzt voraus, dass die Formel (∗) fur¨ n
gilt, und zeigen, dass sie dann auch fur¨ n+1 richtig
ist. Also formal aufgeschrieben:
Induktionsvoraussetzung: (Das wird vorausgesetzt!)
1 + 2 + 3 + ... + n =
n · (n + 1)
2
(∗∗)
Mathematik kompakt 38
Folgen/endliche Summen — Vollstandige ¨ Induktion Beispiel
— Fortsetzung
1
+
2
+
3
+ ...
+
n
=
n · (
n
+ 1)
2
(∗∗
)
Induktionsbehauptung: (Das ist zu
zeigen!)
1
+
2
+
3
+ ...
+
n
+
(
n
+ 1)
=
(
n
+ 1) · (
n
+ 2)
2
(
∗
∗
∗
)
Auf die Induktionsbehauptung wiederum
kommt man, indem man in der
Induktionsvoraussetzung uber ¨ all,
w
o
n steht, dieses durch
n
+
1 ersetzt
(auf Klammersetzung achten!).
Beim Induktionsschluss
kommt es
nun darauf an, (∗
∗
∗) aus (∗∗) herzuleiten
— man wird also auch irgendw
o in der Be
weiskette das Bekannte,
also (∗∗), benutzen
mussen. ¨ Wir starten mit der linken Seite der Induktionsbehauptung:
1
+
2
+
3
+ ...
+
n
+
(
n
+ 1)
= [1
+
2
+
3
+ ...
+
n] | {z
}
=
n
(
n
+ 1)
2
+(
n
+ 1)
Mathematik kompakt 39
Folgen/endliche Summen
—
Vollstandige ¨ Induktion
Beispiel — Fortsetzung
Wir starten mit der linken Seite der Induktionsbehauptung:
1 + 2 + 3 + ... + n + (n + 1) = [1 + 2 + 3 + ... + n] | {z }
=
n(n + 1)
2
+(n + 1)
nach Induktionsvoraussetzung (∗∗), und fahren fort mit dem Ausklammern
von (n + 1):
n(n + 1)
2 + (n + 1) = (n + 1) · n2 + 1 = (n + 1) · (n + 2) 2 .
Damit haben wir die rechte Seite der Induktionsbehauptung (∗ ∗ ∗) stehen
— was zu beweisen war!
Mathematik
kompakt 40
Folgen/endliche Summen — Vollstandige ¨ Induktion
Ub¨ ung
Beweisen Sie durch Vollstandige ¨ Induktion:
1 + 3 + 5 + ... + (2n − 1) =
X
n
i=1
(2i − 1) = n
2
.
Mathematik kompakt 41
Folgen/endliche Summen
—
Vollstandige ¨ Induktion
Losung ¨
Der Induktionsbeginn ist wiederum einfach: 1 = 12. Fur¨ den Induktionsschluss schreiben wir explizit die Induktionsvoraussetzung
1 + 3 + 5 + ... + (2n − 1) = X
n
i=1
(2i − 1) = n2
und die Induktionsbehauptung
1 + 3 + 5 + ... + (2n − 1) + (2n + 1) =
n
X
+1
i=1
(2i − 1) = (n + 1)2
hin. Die Induktionsbehauptung ist mit Hilfe der Induktionsvoraussetzung
recht einfach zu zeigen:
1 + 3 + 5 + ... + (2n − 1) + (2n + 1) = n2 + (2n + 1) = (n + 1)2.
Mathematik
kompakt 42
Folgen/endliche Summen — Vollstandige ¨ Induktion
Losung ¨ — Fortsetzung
Die Aussage der Formel lasst ¨ sich ubr ¨ igens leicht
veranschaulichen. Die Abbildung zeigt einen Spezialfall von 1 + 3 + 5 + . . . + (2n − 1) = n
2:
1+3+5+7 = 42
Mathematik kompakt 43
Folgen/endliche Summen — Vollstandige ¨ Induktion
Rekursion, Fakultaten ¨
Vollstandige ¨ Induktion ist eng verwandt mit Rekursion, was folgendes Beispiel gut verdeutlicht:
Fakultaten ¨ sind bekanntlich definiert als
n! = n · (n − 1) · (n − 2) · ... · 3 · 2 · 1,
etwa
6! = 6 · 5 · 4 · 3 · 2 · 1.
Wenn man nun aber 5! = 120 kennt, ware ¨ es doch
dumm, 6! = 6 · 5 · 4 · 3 · 2 · 1 auszurechnen — das
geht namlich ¨ einfacher:
6! = 6 · 5! = 6 · 120 = 720.
Dass man, wie gesehen, 6! auf 6 · 5! zuruc¨ kfuhren ¨
kann, wird mit dem Begriff Rekursion bezeichnet.
Fakultaten ¨ kann man also rekursiv definieren:
0! := 1, (n + 1)! = (n + 1) · n!.
Mathematik kompakt 44
Folgen/endliche Summen — Vollstandige ¨ Induktion
Ub¨ ung
Definieren Sie entsprechend Summen
sn :=
n
X−1
i=0
ai
rekursiv.
Mathematik kompakt 45
Folgen/endliche Summen — Vollstandige ¨ Induktion
Losung ¨
s1 = a0, sn+1 = sn + an.
Mathematik kompakt 46
Folgen/endliche Summen — Vollstandige ¨ Induktion
Potenzen, Potenzgesetze
Ein anderes Beispiel fur¨ eine rekursive Definition
sind Potenzen:
a
0 = 1, a
n+1 = a
n
· a.
Wenn man nun noch Potenzen fur¨ negative Exponenten wie folgt erklar¨ t:
a
−n = (a
−1
)
n =

1
a
n
=
1
a
n
,
dann gelten (zunachst ¨ fur¨ ganze Zahlen m, n) die
bekannten Potenzgesetze:
am · a
n
= am+n
,
am
an
= am−n
,
(am)
n
= am·n
,
(a · b)
n
= a
n · b
n
,


a
b


n
=
a
n
bn
Mathematik kompakt 47
Folgen/endliche Summen — Vollstandige ¨ Induktion
Ub¨ ung
Vereinfachen Sie

9x
2y
25a
2b
2
!2
·

3axy2
5b
2
!−3
.
Mathematik kompakt 48
Folgen/endliche Summen — Vollstandige ¨ Induktion
Losung ¨

9
x
2
y
25
a
2
b
2
!
2
·

3axy
2
5
b
2
!
−
3
=
9
2
x
4
y
2
25
2
a
4
b
4 · 5
3
b
6
3
3
a
3
x
3
y
6
=
9
2
x
4
y
2
25
2
a
4
b
4 · 5
3
b
6
3
3
a
3
x
3
y
6
=
3
4 · 5
3
5
4 · 3
3 ·
x
4
x
3 ·
y
2
y
6 · 1
a
4 · a
3 ·
b
6
b
4
=
3
5 · x · 1
y
4 · 1
a
7 · b
2
=
3xb
2
5
y
4
a
7
Mathematik kompakt 49
Folgen/endliche Summen — Vollstandige ¨ Induktion
Rekursive Definition von Zahlenfolgen
Man kann Zahlenfolgen bilden, indem man die erste
Zahl (den Startwert) a0 vorgibt, sowie eine Rekursionsvorschrift, wie sich die (n+1)-te Zahl an+1 aus
der n-ten Zahl an berechnet.
So ist etwa durch
a0 = 1 und an+1 =
1
2
(an +
2
an
)
eine Zahlenfolge rekursiv definiert. Durch iteratives
Verwenden der Rekursionsformel erhalt ¨ man
a1 =
1
2
(a0 +
2
a0
) = 1.5,
a2 =
1
2
(a1 +
2
a1
) ≈ 1.4157,
a3 =
1
2
(a2 +
2
a2
) ≈ 1.4142
usw.
Diese Folge ist ubr ¨ igens schon seit uber ¨ 2000 Jahren bekannt. Als ”
Verfahren von Heron“ liefert sie mit
wachsendem n immer bessere Naher ¨ ungswerte fur¨ √
2.
Mathematik kompakt 50
Folgen/endliche Summen — Vollstandige ¨ Induktion
Ub¨ ung
a) Welche Zahlenfolge ist durch
a0 = 1; an+1 = 2an + 1
gegeben?
Berechnen Sie a1, a2 . . . , a5 und erraten Sie
ein Bildungsgesetz!
b) Beweisen Sie dieses Bildungsgesetz mittels Vollstandiger ¨ Induktion.
Mathematik kompakt 51
Folgen/endliche Summen — Vollstandige ¨ Induktion
Losung ¨
a) Die ersten Zahlen aus der rekursiv definierten
Folge lauten:
a1 = 3, a2 = 7, a3 = 15, a4 = 31, a5 = 63.
Es sind die um Eins verminderten Zweierpotenzen 4, 8, 16, 32, 64. Das Bildungsgesetz der Folge ist daher einfach an = 2
n+1 − 1.
b) Fur¨ n = 0 ergibt sich a0 = 2
0+1 − 1 = 1
(Induktionsbeginn). Der Induktionsschluss lauft ¨
wie folgt: Durch die rekursive Definition erhalten
wir: an+1 = 2an + 1.
Die Induktionsvoraussetzung liefert:
an = 2
n+1 − 1.
Also gilt insgesamt:
an+1 = 2an + 1 = 2 · (2n+1 − 1) + 1
= 2
n+2 − 2 + 1 = 2
n+2 − 1.
an+1 = 2
n+2 − 1 ist aber gerade die Induktionsbehauptung.
Mathematik kompakt 52
Anwendung — Beweise in der Mathematik
Beweise in der Mathematik
Zur Mathematik gehoren ¨ Beweise — wie das Amen
zur Kirche, wie Versuche zur Experimentalphysik,
wie Messungen zu den Ingenieurwissenschaften.
Beweise sind in allen exakten Wissenschaften wirklich wichtig, denn ein bloß intuitives Verstandnis ¨ kann
— das ist auch eine Alltagserfahrung — leicht tau- ¨
schen. Dabei gibt es auch in der Mathematik ganz
unterschiedliche Beweistypen.
Mathematische Aussagen haben oft die Gestalt
”
Wenn A, dann B“.
In der Logik verwendet man dafur¨ die Abkurzung ¨
”
A ⇒ B“
(sog. ”
Implikation“). Aber ”
A ⇒ B“ kann man nicht
immer direkt zeigen, d.h. mit Zwischenschritten
”
A ⇒ Zw1 ⇒ Zw2 ⇒ . . . ⇒ Zwn ⇒ B“
herleiten. Manchmal kommt man auf scheinbaren
Umwegen weiter.
Mathematik kompakt 53
Anwendung — Beweise in der Mathematik
Beweis durch Kontraposition
Ein solcher vermeintlicher Umweg ist der so genannte ”
Beweis durch Kontraposition“. Hier zeigt man anstelle von
”
A ⇒ B“
die Kontraposition
”
B ⇒ A“
(wobei A fur¨ die Verneinung von A steht).
Dass ”
A ⇒ B“ und ”
B ⇒ A“ aquiv ¨ alent (also logisch gleichwertig) sind, lernt man in der Logik —
dort lernt man ubr ¨ igens auch, dass
”
A ⇒ B“
etwas ganz anderes als
”
B ⇒ A“
ist.
Mathematik kompakt 54
Anwendung — Beweise in der Mathematik
Widerspruchsbeweise
Eine andere Moglichk ¨ eit, eine Aussage ”
A ⇒ B“ zu
beweisen, ist der so genannte Widerspruchsbeweis.
Er funktioniert indirekt: Man setzt
”
A ∧ B“
(A und nicht-B) voraus und leitet daraus einen Widerspruch ab.
Ein Glanzstuc¨ k solcher mathematischer Beweiskunst
ist etwa der Beweis Euklids, dass es unendlich viele Primzahlen geben muss: Euklid nahm an, es gebe nur endlich viele Primzahlen und leitete daraus
einen Widerspruch her.
Euklid (etwa 3. Jahrhundert v.Chr.) liefert auch das
Stichwort fur¨ eine weitere wichtige Charakterisierung
der Mathematik im Zusammenhang mit Beweisen:
die so genannte axiomatische Vorgehensweise.
Mathematik kompakt 55
Anwendung — Beweise in der Mathematik
Neuere Beweise
Dass mathematische Beweise immer komplizierter
werden, ist auch kein Geheimnis. Manchmal kann
ein solcher Beweis nur einer großeren ¨ Gemeinschaft
von Wissenschaftlern gelingen. So waren etwa an
der Klassifikation der so genannten endlichen Gruppen mehr als 100 Mathematiker beteiligt.
Andere Beweise sind das Werk einzelner Genies,
wie z.B. der Beweis des so genannten Fermat’schen
Satzes von Andrew Wiles. Dieser Klassiker der Mathematikerzunft hat folgenden Hintergrund:
Bekanntlich gibt es Zahlentripel (x, y, z), die die Gleichung x
2 + y
2 = z
2 erfullen, ¨ etwa (3, 4, 5) die
Gleichung 3
2 + 4
2 = 5
2. Wie steht es nun mit der
Gleichung x
n+y
n = z
n? Gibt es andere natur¨ liche
Zahlen n, so dass sich entsprechende Zahlentripel
mit n als Exponenten finden lassen?
Die Antwort ist — nein.
Andrew Wiles ist fur¨ den Beweis des Fermat’schen
Satzes mit der Fields-Medaille ausgezeichnet worden (einer Art Nobelpreis fur¨ Mathematiker).
Mathematik kompakt 56
Anwendung
—
Kurs und Rendite einer Anleihe
Bor¨ senkurs und Rendite einer Anleihe
Bankangebote fur¨ Kunden zum Kauf von Wertpapieren haben meist die
Form
Zins Anleihenbeschreibg. Kurs Rendite Restlaufzeit
7% Inhaberschuldver. 96.01 8.00% 5 Jahre
10% Off
¨
. Pfandbrief 105.56 6.93% 2 Jahre
. . . . . . . . . . . . . . . . . . . . .
Wichtige Entscheidungskriterien fur¨ den Kauf ¨ er sind dabei der Nominalzins (oben 7% bzw. 10%), der Borsenkurs ¨ , die Rendite und die Restlaufzeit.
Mathematik
kompakt 57
Anwendung — Kurs und Rendite einer Anleihe
Bor¨ senkurs, Rendite und Restlaufzeit
Der Borsenkurs ¨ gibt den jeweiligen Kurs der Anleihe
an der Borse ¨ an.
So musste ¨ man im obigen Fall fur¨ nominal 100 Euro
der Inhaberschuldverschreibung nur 96.01 Euro bezahlen, nominal 100 Euro des Pfandbriefes wurden ¨
aber 105.56 Euro kosten. Wie wird nun dieser Bor- ¨
senkurs bestimmt?
Dazu gehen wir zunachst ¨ auf die Bedeutung obiger
Kennzeichen ein:
• Der Nominalzins liefert die fur¨ den Anleger zunachst ¨ interessanteste Angabe, d.h. wie viel Zinsen er fur¨ sein angelegtes Geld pro Jahr (= p.a.
”
pro anno“) erhalt. ¨ Zu nominal 100 Euro der obigen Inhaberschuldverschreibung gehoren ¨ 7 Euro, zu nominal 10000 Euro entsprechend 700
Euro, namlich ¨ 7%. Beim Pfandbrief liegt der Nominalzins entsprechend hoher ¨ , namlich ¨ bei 10%.
• Die Restlaufzeit gibt an, auf wie viele Jahre das
Geld festgelegt (und auch verzinst) wird.
Mathematik kompakt 58
Anwendung — Kurs und Rendite einer Anleihe
Endliche Zahlenfolgen
Die angebotenen Anlagen lassen sich mathematisch
auch als (endliche) Zahlenfolgen auffassen. Wenn
Sie eine Anleihe mit jahr ¨ licher Zinszahlung K (Kupon) und einer Laufzeit von n Jahren kaufen, dann
entspricht dies der Zahlenfolge
( a0 = 0, a1 = K, a2 = K, . . . , an−2 = K,
an−1 = K, an = K + T ).
Das heißt, dass Sie jedes Jahr Ihre Zinszahlung K
erhalten und am Ende der Laufzeit natur¨ lich neben
der Zinszahlung K auch das eingesetzte Kapital,
den sog. Tilgungsbetrag T, zuruc¨ kbekommen.
In unserem Beispiel: Zu nominal 10000 Euro der
obigen Inhaberschuldverschreibung gehor¨ t die Zahlenfolge
(0, 700, 700, 700, 700, 700+10000 = 10700).
Und zu nominal 10000 Euro des Pfandbriefs lautet
die Zahlenfolge
(0, 1000, 1000 + 10000 = 11000).
Mathematik kompakt 59
Anwendung — Kurs und Rendite einer Anleihe
Fairer Bor¨ senkurs und Barwert
Jede Anleihe wurde vom Emittenten mit einem festen Nominalzins, dem die Zahlungen K entsprechen,
versehen. Dieser Zins weicht natur¨ lich in der Regel
von der derzeit auf dem Markt erzielbaren Rendite
r ab.
Der faire Borsenkurs ¨ entspricht daher dem Barwert
BW der Zahlenfolge unter Zugrundelegung der Rendite r (
”
Was musste ¨ man heute bei der Bank anlegen, um die Zahlenfolge zu realisieren?“).
Mochte ¨ man etwa nach einem Jahr eine Zahlung
von 700 Euro bei einem Zinssatz von 5% erhalten,
so muss man heute 666.67 Euro anlegen. In einem
Jahr werden dann mit Zinsen 700 Euro (666.67 ·
1.05 = 700) ausbezahlt.
Will man hingegen nach zwei Jahren eine Auszahlung von 700 Euro erhalten, so sind heute 634.92
Euro festzulegen (634.92 · 1.052 = 700).
Die jeweils berechneten Anlagebetrage ¨ nennt man
Barwerte.
Mathematik kompakt 60
Anwendung
—
Kurs und Rendite einer Anleihe
Barwertberechnung
Allgemein ist also der Barwert der Zinszahlung K im Jahre t bei einer
Rendite r mit K · (1 + r)−t anzusetzen.
Bei einer Zahlenfolge der Gestalt (a0 = 0, a1 = K, a2 = K, . . . ,
an−2 = K, an−1 = K, an = K + T) erhalt ¨ man den Barwert entsprechend als Summe zu
BW = X
n
t=1
K(1+r)−t+T(1+r)−n = K X
n
t=1
(1+r)−t+T(1+r)−n.
Setzt man q := (1 + r)−1, so ist
X
n
t=1
(1 + r)−t = X
n
t=1
qt.
Die Summanden (q1, q2, q3, . . . qn) dieser Reihe bilden eine geometrische Folge, da der Quotient benachbarter Elemente konstant gleich q ist.
Mathematik
kompakt 61
Anwendung — Kurs und Rendite einer Anleihe
Barwertberechnung — Fortsetzung
Damit haben wir eine geometrische Reihe, deren
Wert sich zu
X
n
t=1
q
t = q
q
n − 1
q − 1
=
1
1 + r
·
(1 + r)
−n − 1
(1 + r)−1 − 1
=
(1 + r)
−n − 1
−r
ergibt. Erweiterung von Zahler ¨ und Nenner jeweils
mit (1 + r)
n liefert dann
X
n
t=1
q
t =

(1 + r)
−n − 1

· (1 + r)
n
−r · (1 + r)
n
=
1 − (1 + r)
n
−r(1 + r)
n
=
1
r
−
1
r
(1 + r)
−n
.
Setzt man dieses Ergebnis in die Formel
BW = K
X
n
t=1
(1 + r)
−t + T(1 + r)
−n
ein, so erhalt ¨ man eine einfache Formel zur Bestimmung des Borsenkurses ¨ BW einer Anleihe:
BW =
K
r
+

T −
K
r

(1 + r)
−n
.
Mathematik kompakt 62
Anwendung — Kurs und Rendite einer Anleihe
Barwertberechnung fur¨ die Anleihen
BW =
K
r
+

T −
K
r

(1 + r)
−n
.
Auf unsere Inhaberschuldverschreibung angewandt
ergibt sich das Folgende:
Sie soll eine Rendite von 8% p.a. haben. Ihr Kurs
BWIHS (fur¨ 100 Euro Nennwert und damit Kupon
K = 7) lasst ¨ sich dann folgendermaßen berechnen:
BWIHS =
7
0.08
+

100 −
7
0.08
(1.08)−5
= 96.0073.
Entsprechend ergibt sich der Kurs des Pfandbriefes
BWPFB (fur¨ 100 Euro Nennwert und damit Kupon
K = 10) bei einer Rendite von 6.93% zu
BWPFB =
10
0.0693
+

100 −
10
0.0693
(1.0693)−2
= 105.5560.
Mathematik kompakt 63
Anwendung — Kurs und Rendite einer Anleihe
Berechnung der Rendite
Wir haben bisher bei vorgegebener Rendite r den
Barwert der Anleihe ermittelt.
Umgekehrt ist es natur¨ lich auch moglich, ¨ bei vorgegebenem Anleihenkurs BW die Rendite zu berechnen. Multipliziert man die Formel
BW =
K
r
+

T −
K
r

(1 + r)
−n
mit r (Achtung: eine Losung ¨ r = 0 kommt falschli- ¨
cherweise hinzu!) und (1+r)
n
, so erhalt ¨ man nach
Umordnung der Terme
BW · r(1 + r)
n − K [(1 + r)
n − 1] − T · r = 0.
Dies ist eine Polynomgleichung (n+1)-ten Grades
in r. Die Losung ¨ r kann i.Allg. nicht analytisch berechnet werden. Es muss daher auf gangige ¨ Nahe- ¨
rungsverfahren (z.B. Sekanten- oder Newtonverfahren) zuruc¨ kgegriffen werden.
Mathematik kompakt 64
