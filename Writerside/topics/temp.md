# RGB-Format

Das RGB-Farbmodell ist ein Farbmodell, bei dem Licht in den drei Grundfarben Rot (R), Grün (G) und Blau (B) gemischt wird, um eine breite Palette von Farben zu erzeugen. Es wird in vielen Bereichen wie Computergrafik, Fotografie und Fernsehtechnologie verwendet.

## Grundlagen

Im RGB-Farbmodell werden Farben durch die Intensität der drei Grundfarben dargestellt. Jede dieser Farben kann einen Wert zwischen `0` und `255` annehmen, wobei `0` die geringste und `255` die höchste Intensität darstellt.

### Beispiel: {id="example-1"}

Die Farbe Weiß entsteht durch die maximale Intensität aller drei Grundfarben:

```tex
\begin{equation}
\text{Weiß} = (R, G, B) = (255, 255, 255)
\end{equation}
```

Die Farbe Schwarz entsteht durch die minimale Intensität aller drei Grundfarben:

```tex
\begin{equation}
\text{Schwarz} = (R, G, B) = (0, 0, 0)
\end{equation}
```

## Farbmischung

Durch die Kombination unterschiedlicher Intensitäten der Grundfarben können verschiedene Farben erzeugt werden. Hier sind einige Beispiele:

### Beispiel: {id="example-2"}

Die Farbe Rot entsteht durch maximale Intensität von Rot und minimale Intensität von Grün und Blau:

```tex
\begin{equation}
\text{Rot} = (R, G, B) = (255, 0, 0)
\end{equation}
```

Die Farbe Grün entsteht durch maximale Intensität von Grün und minimale Intensität von Rot und Blau:

```tex
\begin{equation}
\text{Grün} = (R, G, B) = (0, 255, 0)
\end{equation}
```

Die Farbe Blau entsteht durch maximale Intensität von Blau und minimale Intensität von Rot und Grün:

```tex
\begin{equation}
\text{Blau} = (R, G, B) = (0, 0, 255)
\end{equation}
```

## Anwendungen

### In `HTML` {collapsible="true" default-state="collapsed"}

Im HTML und CSS wird das RGB-Farbmodell verwendet, um Farben anzugeben. Dies geschieht in der Regel durch das `rgb()`-Format oder durch Hexadezimalwerte.

#### Beispiel: {id="example-3"}

<p style="color: rgb(255, 0, 0);">Dieser Text ist rot.</p>
<p style="color: #00FF00;">Dieser Text ist grün.</p>


In diesem Beispiel wird der erste Text rot und der zweite Text grün angezeigt.
