# Ableitungsregeln
## Ableitung einer Konstante ist **Null**.

$$f(x)=C \rightarrow f'(x)=0$$

## Ableitung von $x$ ist $1$.

$$f(x)=x \rightarrow f'(x)=1$$

## Potenzregel
Die Potenzregel ist immer dann anzuwenden, wenn etwas im Exponenten der x-Funktion steht.
Wie der Name bereits vermuten lässt, handelt es sich dabei um Potenzfunktionen: $f(x)=x^n$

$$f(x)=x^n \rightarrow f'(x)=n \cdot x^{n-1}$$

## Faktorregel
Wenn vor dem $x$ ein konstanter Faktor steht, wendet man die Faktorregel an.

$$f(x)=c \cdot g(x) \rightarrow f'(x)=c \cdot g'(x)$$

## Summenregel
Kommt auf **beiden Seiten** des Plus-Zeichens ein $x$ vor, ist die Summenregel anzuwenden.

$$f(x)=u(x)+v(x) \rightarrow f'(x)=u'(x)+v'(x)$$

## Differenzregel
Kommt auf **beiden Seiten** des Minus-Zeichens ein $x$ vor, ist die Differenzregel anzuwenden.

$$f(x)=u(x)-v(x) \rightarrow f'(x)=u'(x)-v'(x)$$

## Produktregel
Kommt auf beiden Seiten des Mal-Zeichens ein $x$ vor, ist die Produktregel anzuwenden.

$$f(x)=u(x) \cdot v(x) \rightarrow f'(x)=u'(x) \cdot v(x)+u(x) \cdot v'(x)$$

## Kettenregel

Die Kettenregel ist bei Funktionen anzuwenden, die als Verkettung von zwei Funktionen vorliegen.
Es geht also um den Fall, wenn zwei verschiedene Funktionen ineinander verschachtelt sind.

$$f(x)=u(v(x)) \rightarrow f'(x)=u'(v(x)) \cdot v'(x)$$

## Quotientenregel
Kommt im **Zähler und im Nenner** eines Bruchs ein $x$ vor, ist die Quotientenregel anzuwenden.

$$f(x)=\frac{g(x)}{h(x)} \rightarrow f'(x)=\frac{h(x) \cdot g'(x)-g(x) \cdot h'(x)}{[h(x)]^2}$$

## Besondere Funktionen
### Sinus/Cosinus

* $f(x)=sin(x) \rightarrow f'(x)=cos(x)$
* $f(x)=cos(x) \rightarrow f'(x)=-sin(x)$
* $f(x)=-sin(x) \rightarrow f'(x)=-cos(x)$
* $f(x)=-cos(x) \rightarrow f'(x)=sin(x)$

### $e$-Funktion

Die Ableitung der $e$-Funktion ist die $e$-Funktion.
Das kann man sich leicht merken. Schwieriger wird es jedoch, wenn nicht nur ein $$x$$ im Exponenten steht. 
Dann sind wir nämlich gezwungen, auf die *Kettenregel* zurückzugreifen.

$$f(x)=e^{2x} \rightarrow f'(x)=e^{2x} \cdot 2 = 2e^{2x}$$
