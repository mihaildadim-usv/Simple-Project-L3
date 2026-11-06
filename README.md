# My Simple Webpage

## Descrierea proiectului

Acest proiect reprezintă o pagină web simplă, realizată folosind HTML5 și CSS3. Scopul proiectului este exersarea structurii HTML, stilizării CSS și utilizării tehnicilor moderne de design web.

Pagina conține o secțiune de prezentare personală, o galerie foto, secțiuni informative și stiluri pentru interfețe de aplicații meteo.

## Tehnologii utilizate

- HTML5 – pentru structura paginii web.
- CSS3 – pentru stilizarea elementelor.
- CSS Grid – pentru organizarea galeriei foto și a informațiilor meteo.
- Flexbox – pentru alinierea elementelor.
- Media Queries – pentru design responsive.

## Structura proiectului

- `index.html` – fișierul principal HTML.
- `styles.css` – fișierul care conține regulile CSS.
- `README.md` – documentația proiectului.

## Structura paginii

### Header
Conține titlul principal „Welcome to My Page” și meniul de navigare cu linkuri către Home, About și Contact.

### Despre Mine (#despre)
Prezintă informații despre autor, fiind inclus un titlu și un paragraf introductiv.

### Galerie foto (#galerie)
Conține:
- Un titlu „Galerie foto”.
- Trei imagini placeholder.
- Un layout realizat cu CSS Grid.
- Trei coloane pe ecrane mari.
- O singură coloană pe ecrane cu lățimea de maximum 600px.
- Un spațiu de 1rem între imagini.

### Home (#home)
Conține o scurtă prezentare a paginii web.

### About (#about)
Include informații suplimentare despre proiect.

### Contact (#contact)
Este secțiunea destinată informațiilor de contact.

### Footer
Conține mesajul privind drepturile de autor.

## Stilizare CSS

Fișierul `styles.css` include:
- Resetarea marginilor și spațierilor implicite.
- Setarea fontului Arial.
- Stilizarea meniului de navigare.
- Culori personalizate pentru fundal și text.
- Umbre și colțuri rotunjite pentru secțiuni.
- Efecte interactive folosind `:hover` și `:active`.
- Layout-uri realizate cu CSS Grid și Flexbox.

## Design Responsive

Proiectul utilizează Media Queries pentru adaptarea elementelor la diferite dimensiuni ale ecranului.

### Galerie foto

Pe ecrane mai mari de 600px, imaginile sunt afișate pe trei coloane.

Pe ecrane de maximum 600px, imaginile sunt afișate pe o singură coloană.

### Aplicații meteo

La o lățime de maximum 768px, grupurile de input și butoanele sunt afișate vertical, iar grilele pentru prognoza meteo se adaptează dimensiunii ecranului.

## Elemente CSS pentru aplicațiile meteo

Fișierul CSS conține clase dedicate interfețelor meteo:

- `.weather-container` – containerul principal.
- `.weather-app-box` – casetele aplicațiilor.
- `.input-group` – grupurile de input și butoane.
- `.result-box` – zona rezultatelor.
- `.weather-data` – informațiile meteo.
- `.forecast-grid` – grila prognozei zilnice.
- `.hourly-grid` – grila prognozei orare.
- `.loading` – indicatorul de încărcare.
- `.error` – mesajele de eroare.

Sunt incluse animații CSS și efecte vizuale pentru îmbunătățirea experienței utilizatorului.

## Instalare și utilizare

1. Descarcă sau clonează proiectul.
2. Deschide folderul proiectului.
3. Verifică existența fișierelor `index.html` și `styles.css`.
4. Deschide `index.html` într-un browser web.
5. Pentru modificarea aspectului paginii, editează `styles.css`.

## Obiectivele proiectului

- Exersarea HTML5 și CSS3.
- Utilizarea CSS Grid și Flexbox.
- Crearea unei galerii foto responsive.
- Aplicarea efectelor vizuale și animațiilor CSS.
- Înțelegerea principiilor de design responsive.

---

**Autor:** Student pasionat de tehnologie și dezvoltare web.

**An:** 2025