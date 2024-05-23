# Umwandlung zwischen Zahlen in Dezimal- und Hexadezimaldarstellung

### Umrechnung von Dezimalzahlen in Hexadezimalzahlen {collapsible="true" default-state="collapsed"}

Um eine Dezimalzahl in eine Hexadezimalzahl umzuwandeln, kann das Verfahren der fortgesetzten Division durch `16` angewendet werden. Hierbei werden die Reste notiert und anschließend in umgekehrter Reihenfolge gelesen.

#### Beispiel: {id="example-1"}

Um die Dezimalzahl `255` in eine Hexadezimalzahl umzuwandeln:

1.  <code-block lang="tex" >
    \begin{equation}
    255 \div 16 = 15 \text{ Rest } 15 \ (F)
    \end{equation}
    </code-block>
2. <code-block lang="tex" >
    \begin{equation}
    15 \div 16 = 0 \text{ Rest } 15 \ (F)
    \end{equation}
    </code-block>

Die Hexadezimaldarstellung von `255` ist `FF`.

### Umrechnung von Hexadezimalzahlen in Dezimalzahlen {collapsible="true" default-state="collapsed"}

Um eine Hexadezimalzahl in eine Dezimalzahl umzuwandeln, multipliziert man jede Ziffer der Hexadezimalzahl mit der entsprechenden Potenz von 16 und summiert die Ergebnisse.

#### Beispiel: {id="example-2"}

Um die Hexadezimalzahl `1A3` in eine Dezimalzahl umzuwandeln:

1.  <code-block lang="tex">
    \begin{equation}
    1A3_{16} = (1 \times 16^2) + (A \times 16^1) + (3 \times 16^0)
    \end{equation}
    </code-block>
2.  <code-block lang="tex">
    \begin{equation}
    = (1 \times 256) + (10 \times 16) + (3 \times 1)
    \end{equation}
    </code-block>
3.  <code-block lang="tex">
    \begin{equation}
    = 256 + 160 + 3 = 419
    \end{equation}
    </code-block>


Die Dezimaldarstellung von `1A3` ist `419`.
