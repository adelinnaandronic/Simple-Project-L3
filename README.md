My Simple Webpage
1. Descrierea proiectului

My Simple Webpage este un proiect web realizat în cadrul unui laborator de facultate. Scopul acestuia este exersarea cunoștințelor de dezvoltare Front-End folosind HTML5 și CSS3.

Pagina web conține mai multe secțiuni informative, un meniu de navigare și o galerie foto cu trei imagini.

2. Tehnologii utilizate
HTML5 – pentru structura și organizarea conținutului paginii web.
CSS3 – pentru stilizarea elementelor, culori, spațiere și design responsiv.
3. Structura fișierelor
text
My-Simple-Webpage/
│
├── index.html
├── styles.css
├── README.md
│
└── imagini/
    ├── imagine1.jpg
    ├── imagine2.jpg
    └── imagine3.jpg

Descrierea fișierelor
index.html – conține structura principală a paginii web.
styles.css – conține regulile CSS pentru aspectul vizual al paginii.
README.md – conține documentația proiectului.
imagini/ – directorul în care sunt stocate imaginile utilizate în galerie.
4. Secțiunile paginii web
Header (Antet)

Conține titlul principal „Welcome to My Page” și meniul de navigare cu următoarele linkuri:

Home
About
Contact
Home

Secțiunea identificată prin id="home" conține un titlu și un text introductiv despre pagina web.

About (Despre Mine)

Secțiunea identificată prin id="about" conține titlul „About” și textul „Learn more about what we do.”

Aceasta este destinată prezentării unor informații generale despre autor sau proiect.

Contact

Secțiunea identificată prin id="contact" conține un titlu și un mesaj prin care vizitatorii sunt invitați să ia legătura cu autorul.

Nu există un formular de contact implementat în versiunea actuală.

Galerie

Secțiunea identificată prin id="galerie" prezintă trei imagini organizate într-o grilă.

Pentru realizarea acesteia sunt utilizate:

<section> – pentru organizarea semantică a secțiunii.
<h2> – pentru titlul „Galerie”.
<div> – pentru gruparea imaginilor.
<figure> – pentru organizarea fiecărei imagini.
<img> – pentru afișarea imaginilor.
<figcaption> – pentru descrierea imaginilor.

Galeria afișează trei coloane pe ecrane mari și o singură coloană pe ecrane cu lățimea mai mică de 600px.

Footer (Subsol)

Conține mesajul privind drepturile de autor:

© 2025 My Simple Webpage. All rights reserved.

5. Stilizarea CSS

Fișierul styles.css controlează aspectul vizual al paginii.

Principalele caracteristici sunt:

Resetarea marginilor și spațierilor implicite folosind selectorul universal *.
Utilizarea fontului Arial.
Fundal gri deschis pentru pagina web.
Antet și subsol cu fundal închis și text alb.
Meniu de navigare realizat folosind Flexbox.
Efecte hover pentru linkurile din meniu.
Secțiuni cu fundal alb, colțuri rotunjite și umbre discrete.
Utilizarea CSS Grid pentru organizarea imaginilor din galerie.
Imagini cu colțuri rotunjite și proprietatea object-fit: cover.
Design responsiv folosind media queries.

Fișierul CSS conține și stiluri pentru componente meteo, precum .weather-container, .weather-app-box, .forecast-grid și .hourly-grid. Aceste stiluri sunt definite în CSS, dar nu sunt utilizate în codul HTML furnizat.

6. Cum se deschide proiectul în browser

Pentru vizualizarea proiectului, urmează acești pași:

Deschide folderul proiectului în Visual Studio Code.
Verifică existența fișierelor index.html și styles.css.
Verifică existența directorului imagini și a celor trei imagini.
Deschide fișierul index.html.
Rulează pagina în browser folosind extensia Live Server sau deschizând direct fișierul în Google Chrome, Mozilla Firefox ori Microsoft Edge.

Nu sunt necesare instalarea unor biblioteci externe sau configurarea unui server pentru vizualizarea paginii statice.

7. Concluzie

My Simple Webpage este un proiect web static realizat cu HTML5 și CSS3, care demonstrează utilizarea elementelor HTML semantice, organizarea conținutului în secțiuni, stilizarea prin CSS, utilizarea Flexbox și CSS Grid și adaptarea paginii pentru diferite dimensiuni ale ecranului.

Proiectul poate fi dezvoltat ulterior prin adăugarea unor secțiuni noi și îmbunătățirea designului.