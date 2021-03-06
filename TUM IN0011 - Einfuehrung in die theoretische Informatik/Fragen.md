# 2 - Grundbegriffe

### Definiere Alphabet

### Definiere Wort

### Definiere eine formale Sprache

### Definiere die Konkatenation zweier Sprachen A und B

### Definiere $A^*$ und $A^+$

### Für welche Operation auf Sprachen gilt das Distributivgesetz?

### Was ist $\emptyset A$ und $\\{\epsilon\\}A$?

## Grammatiken

### Definiere eine Grammatik 

### Definiere die Ableitungsrelation

### Definiere die Sprache einer Grammatik

### Definiere die reflexive transitive Hülle einer Grammatik

### Definiere die Typen der Chomsky Hierarchie

### Was sind die Namen der Grammatiken und Sprachen der Chomsky Hierarchie?

### Was ist das Wortproblem?

# 3 - Reguläre Sprachen

## 3.1 - DFAs

### Definiere einen DFA

### Definiere die akzeptierte Sprache eines DFAs

### Zeige, dass es für jeden DFA $M$ eine rechtslineare Grammatik $G$ mit $L(G) = L(M)$ gibt

### Definiere einen NFA

### # Definiere die akzeptierte Sprache eines NFAs

### Zeige, dass es für jede rechtslineare Grammatik $G$ einen NFA $N$ mit $L(G) = L(M)$ gibt

### Zeige, dass es für jeden NFA $N$ einen DFA $M$ mit $L(G) = L(M)$ gibt

### Definiere einen $\epsilon$-NFA

### # Zeige, dass es für jeden $\epsilon$-NFA $N$ einen NFA $N'$ mit $L(N) = L(N')$ gibt

## 3.5 Reguläre Ausdrücke

### Definiere Reguläre Ausdrücke 

### Definiere die Sprache von Regulären Ausdrücken

### Definiere strukturelle Induktion auf regulären Ausdrücken

### Beweise, dass eine Sprache L genau dann durch einen regulären Ausdruck darstellbar ist, wenn sie regulär ist

### Gib Laufzeiten für die Konversion zwischen DFA, NFA, epsilon-NFA, und REs an

### Beweise, dass wenn R, R1 und R2 reguläre Sprachen sind, dann auch R1R2, R1 u R2, R*, $\bar{R}$, $R_1 \cap R_2$ und R1 \ R2

### Definiere den Produktautomaten und beweise, dass er den Durchschnitt von zwei Sprachen bildet

### Gibt Rechenregeln für REs $\alpha, \epsilon, \emptyset$ an

### Definiere Assoziativität, Kommutativität, Distributivität und Idempotenz bei REs

### # Gib drei Sternrechenregeln für REs

### Was ist der Satz von Redko?

### Definiere das Pumping Lemma und Pumping Lemma Zahlen

### Beweise das Pumping Lemma

### Beweise, dass L = {a^i b^i | i in N} nicht regulär ist

### Was ist ein Entscheidungsproblem? Wann ist es entscheidbar? Erkläre 4 Probleme

### # Zeige, in welcher Zeit das Wortproblem für NFAs entscheidbar ist

### Zeige, in welcher Zeit das Leerheitsproblem für DFAs / NFAs entscheidbar ist

### Zeige, dass das Endlichkeitsproblem für DFAs und NFAs entscheidbar ist

### Zeige, in welcher Zeit das Äquivalenzproblem für DFAs entscheidbar ist 

### Zeige, in welcher Zeit das Äquivalenzproblem für NFAs entscheidbar ist bei fixem Sigma

### # Was ist Ardens Lemma?

### # Wie wandelt man einen FA in einen äquivalenten regulären Ausdruck um?

### Gib den Algorithmus zur Minimierung eines DFA

### Wann sind Zustände unterscheidbar?

### Wann sind Zustände äquivalent?

### Gib den schematischen O(n^4) Algorithmus zur Berechnung äquivalenter Zustände eines DFA

### Gib den implementierten O(n^4) Algorithmus zur Berechnung äquivalenter Zustände eines DFA

### Gib den O(n^2) Algorithmus zur Berechnung äquivalenter Zustände eines DFA

### Wie ist eine Äquivalenzrelation definiert?

### Wie ist eine Quotientenmenge definiert?

### # Definiere den Quotientenautomat

### Definiere die Äquivalenzrelation einer Sprache L 

### # Beweise, dass wenn M ein DFA ohne unerreichbare Zustände ist, der M /= ein minimaler DFA für L(M) ist

### Definiere den kanonischen Minimalautomat

### Beweise die Myhill-Nerode Bedingung

### # Wie zeigt man Nichtregularität über die Myhill-Nerode Bedingung?

# 4 - Kontextfreie Sprachen

### Definiere eine Kontextfreie Grammatik

### # Wann ist eine CFG rechts- bzw. linkslinear?

### Gib die induktive Definition der Grammatik S -> eps | [S] | SS an

### Gib das Induktionsprinzip für die Grammatik S -> eps | [S] | SS an

### Wie beweist man, dass eine CFG *genau* eine Sprache mit Eigenschaft P für jedes w erzeugt?

### Gib die Induktive Definition einer beliebigen CFG an

### Gib die Induktive Definition von A -> eps | aB und B -> Aa

### Definiere eine mehrdeutige CFG / inhärent mehrdeutige CFL

### Definiere die Chomsky Normalform

### Beweise, dass man zu jeder CFG G eine CFG G' konstruieren kann, die keine eps-Produktionen enthält mit L(G') = L(G) \ {eps}

### Beweise, dass man zu jeder CFG G eine CFG G' konstruieren kann, die keine Kettenproduktionen enthält, sodass L(G') = L(G)

### Gib das Vorgehen zur Konstruktion einer Chomsky NF an

### Definiere die Greibach Normalform für eine CFG

### Gib das Pumping-Lemma für CFGs

### Beweise das Pumping-Lemma für CFGs

### Zeige, dass die Sprache L = {a^i b^i  c^i | i in N} nicht kontextfrei ist

### Definiere nützlich, erzeugend und erreichbar

### Wie kann man machen, dass eine Grammatik nur noch nützliche Symbole enthält mit L(G') = L(G)?

### Beweise, dass die Menge aller erzeugenden Symbole einer CFG berechenbar ist

### # Beweise, dass für eine CFG G "L(G) = emptyset?" entscheidbar ist

### Beweise, dass die Menge der erreichbaren Symbole einer CFG berechenbar ist

### Beweise, dass das Wortproblem für eine CFG G entscheidbar ist

### # Definiere den CYK Algorithmus. Was ist seine Laufzeit?

### Wie kann der CYK Algorithmus erweitert werden, dass er auch die Menge der Syntaxbäume für die Eingabe berechnet?

### # Welche Probleme sind für CFGs nicht entscheidbar?

### # Beweise die Abschlusseigenschaften von CFGs

### # Beweise, unter welchen operationen CFGs nicht abgeschlossen sind

## Kellerautomaten

### Definiere einen Kellerautomaten

### Definiere POP, PUSH und eps-Übergang für einen PDA

### Gib die Konfiguration und Anfangskonfiguration eines PDA M

### Definiere ->M für einen PDA

### Definiere die Sprache eines PDA

### Wie kann man M und M's konstruieren mit L_F(M) = L_eps(M')?

### Wie bringt man eine CFG in die Form A -> b B1 ... Bk mit b in Sigma u {eps}?

### Wie bringt man eine CFG in einen PDA?

### Wie bringt man einen Leerer-Keller-Akzeptanz-PDA in eine CFG?

### Definiere einen deterministischen Kellerautomaten

### Definiere eine deterministische CFL

### Gib einen tabellarischen Überblick der Abschlusseigenschaften

### Gib einen tabellarischen Überblick der Entscheidbarkeit

# 5 - Berechenbarkeit, Entscheidbarkeit

### Definiere berechenbar

### Was ist total, partiell und echt partiell?

### Definiere eine abzählbare Menge M

### Definiere eine überabzählbare Menge M

### Gibt es nicht berechenbare Funktionen?

### Definiere eine TM

### Was ist die Konfiguration und Startkonfiguration einer TM?

### Zeige, dass wenn Algorithmen als Wörter kodiert werden können, dann gibt es unberechenbare Funktionen N -> {0,1}

### Was ist die graphische Notation für delta(p, a) -> (q, b, d)?

### Definiere die Sprache einer TM

### Definiere eine Turing-berechenbare Funktion

### Wann hält eine TM?

### Definiere die sequentielle Komposition von M_1 und M_2

### Definiere WHILE-berechenbar

### Gib die Syntax-Bausteine von WHILE-Programmen

### Definiere entscheidbar

### Gib eine Band=0? TM an

### Beweise, dass das spezielle Halteproblem nicht entscheidbar ist

### Beweise, dass das allgemeine Halteproblem nicht entscheidbar ist

### Definiere reduzierbar

### Zeige, dass falls A <= B und B ist entscheidbar, dann ist auch A entscheidbar

### Wie zeigt man die Unentscheidbarkeit eines Problems?

### Definiere semi-entscheidbar

### Definiere rekursiv aufzählbar

### Gib die äquivalente Aussagen zu Semi-Entscheidbarkeit

### Zeige, dass K semi-entscheidbar ist

### Gib den Satz von Rice

### Zeige, dass es unentscheidbar ist, ob ein Programm für mindestens eine Eingabe hält

### Gib den Satz von Rice-Shapiro

### Gib die drei wichtigsten Terminationserkenntnisse

### Was ist das PCP?

### Definiere P

### Definiere NP

### Definiere einen polynomiell beschränkten Verifikator

### Definiere polynomiell reduzierbar

### Definiere SAT

### Definiere 3KNF-SAT

### Wie zeigt man NP-Vollständigkeit?









