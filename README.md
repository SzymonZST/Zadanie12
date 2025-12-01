1. parent() 

Ta metoda znajduje bezpośredniego rodzica elementu. Jeśli klikniesz na akapit (np. <p>), to parent() pozwala na zmianę stylu elementu, który otacza ten akapit, czyli rodzica. W przykładzie zmieniamy tło rodzica akapitu.

2. parents()

parents() przechodzi do wszystkich przodków elementu. Oznacza to, że możesz wybrać nie tylko bezpośredniego rodzica, ale także jego rodziców, dziadków itd. W naszym przypadku używamy jej do zaznaczenia wszystkich tych przodków.

3. children()

Ta metoda daje dostęp do wszystkich bezpośrednich dzieci wybranego elementu. Na przykład, klikając na div, możemy podświetlić wszystkie elementy znajdujące się bezpośrednio w tym div (np. akapity lub listy).

4. siblings()

siblings() pozwala znaleźć wszystkie elementy które są "rodzeństwem" danego elementu. Chodzi o elementy znajdujące się na tym samym poziomie (np. w tej samej liście). Dzięki tej metodzie możemy zmienić styl wszystkich innych elementów (np. li), które są w tej samej grupie, ale nie są tym, na który kliknęliśmy.

5. find()

find() pozwala szukać konkretnych elementów wewnątrz innych. Na przykład, szukamy wszystkich elementów span w div i zmieniamy ich kolor. To jak wchodzenie w pudełko (np. div) i szukanie czegoś w środku (np. span).

6. attr()

Ta metoda pozwala na dodanie lub zmianę atrybutów elementów. Na przykład, dla wszystkich linków (a) dodajemy atrybut target="_blank", co powoduje, że po kliknięciu w link otworzy się on w nowej karcie.
