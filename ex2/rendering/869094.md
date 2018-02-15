Modellazione di una sedia: Jokkmokk, IKEA
1. Modellazione di un buco senza boleane (Necessari per i fori delle viti).
Partire da un Box, applicare Edit poly e inserire 3 loop verticali (equidistanti) e 3 loop orizzontali (equidistanti).
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/buco/buco_1.png
Selezionando Vertex collegare i 4 vertici del quadrato creato utilizzando Connect.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/buco/buco_2.png
Selezionando il comando Chamfer creare un ottagono poartendo dal vertice in cui si incontrano le diagonali del quadrato. 
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/buco/buco_3.png
Selezioanre Polygon e con il comando Remove eleiminare l'ottagono creato.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/buco/buco_4.png
Selezionando i Border dell'ottagono da entrambe le parti del box iniziale creare le pareti del buco con il comando Bridge.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/buco/buco_5.png
Applicare Creaze:1 a i due border superiore e inferiore del buco.
2. Modellazione di una scanalatura (Presenti sui sostegni sotto la seduta).
Partire da un Box rettangolare allungato.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/scanalatura/scanalatura_1.png
Applicare il modificatore Edit poly e inserire 5 loop equidistanti tra loro.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/scanalatura/scanalatura_3.png
Selezionare Vertex e utilizzare il comando Move per spostare in basso i vertici più interni in modo da creare una conca.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/scanalatura/scanalatura_4.png
Inserire loop di sostegno lungo i lati della scanalatura.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/scanalatura/scanalatura_5.png
3. Modellazione di un elemento dello schienale.
Partendo da un'immagine di riferimento ricalcare l'ingombro massimo dell'elemento con un Box.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/schienale/schienale_1.png
Applicare il modificatore Edit poly.
Vista TOP.
Inserire un loop centrale e 3 loop alla sua detra e 3 loop alla sua sinistra.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/schienale/schienale_2.png
Selezionando Vertex e utilizzando Move spostare i vertici in modo da ricreare la curva desiderata.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/schienale/schienale_3.png 
Applicare loops di sostegno lungo i bordi dell'elemento.
Applicare Turbosmooth.
4. Modellazione di una vite: 122620 (Da utizzare sotto la seduta)
Partire da un Box.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_1.png
Applicare Edit poly.
Inserire 4 loop utilizzando Swift loop creando una cornice al quadrato (vista TOP).
Selezionare Polygon ed estrudere il quadrato interno alla cornice verso il basso.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_2.png
Posizionarsi sulla vista laterale e inserire 6 loop verticali e 3 orizzontali.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_3.png
Selezioare i vertici dell'oggetto e abbassarli fino ad arrivare alla forma desiderata (Comando: Move)
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_4.png
Posizionarsi con la vista sul retro dell'oggetto e inserire altri 3 loop vericali centrali al box (equidistanti). 
Ripetere il procedimento illustato sopra per creare un ottagono partendo da un quadrato (Vedi punto 1).
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_5.png
Estrudere l'ottagono selezionando prima Polygon e poi Extrude.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_6.png
Per realizzare il buco sulla base dell'oggetto ripetere il procedimento illustarto al punto 1 sfruttando i loop già realizzati.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_7.png
Inserire il comando creaze:1 al bordo di tutti gli ottagoni realizzati (buco ed estrusione sul retro).
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_8.png
Applicare il modificatore Turbosmooth.
-https://github.com/e-lazzarotto/labmod17_ex2/blob/master/img/tutorial/vite/vite_9.png