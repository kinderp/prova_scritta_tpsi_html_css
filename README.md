## Testo prova scritta
Il repository corrente contiene i seguenti file:

* home.html
* courses.html
* contact.html
* tpsi_5a_24_25.html
* style.css

E' già presente del codice di partenza in ciascuno dei file elencati sopra.
Il tuo compito è quello di aggiungere il codice mancante e completare il sito.
Di seguito sono elencati i punti per il completamento del sito:

1. In tutte le pagine, all'interno di `<head>` sotto `<title>` linka il file css esterno: `style.css`
2. Appena sotto il `<body>`, aggiungi un `div` contenente una lista non ordinata: tag `<ul>`
   * Inserisci tre list items per le pagine: `home.html`, `courses.html`, `contacts.html` ed aggiungi rispettivamente i seguenti testi: `Home`, `Courses`, `Contacts`
   * Rendi cliccabili i tre list items in modo da reindirizzare l'utente alla pagina corretta
3. Assegna al `div` creato al punto 2. la classe `header` ed al tag `ul` la classe `nav`

![punti_1_2_3](https://github.com/user-attachments/assets/6eb50cfd-5990-43c3-8b88-f7172ca083e9)

4. Allinea al centro il testo per la classe `nav`

![punto_4](https://github.com/user-attachments/assets/0210f162-6f34-42f6-84c1-69502734db52)

5. Per tutti i list items della classe `nav` imposta:
   * `font-size` a 20 px
   * `font-weight` a bold
   * margine sinistro e destro a 40 px
   * trasforma il list item da block level tag ad inline (in moda da essere mostrati tutti sulla stessa riga)

![punto_5](https://github.com/user-attachments/assets/a953b727-4696-4d18-bec3-a0f6f166b202)

6. Eliminare la riga (sottolineatura) per ogni tag `<a>` della classe `nav`
![punto_6](https://github.com/user-attachments/assets/d98eba33-38c9-4b1a-a6a4-b61fa732dd8b)

7. Applicare alla classe `nav` le seguenti regole
   * colore di sfondo: `#FFD700`
   * padding superiore ed inferiore: 2px
   * bordo: 1 px
   * colore del bordo: `#e7e7e7`

![punto_7](https://github.com/user-attachments/assets/f54e1c7d-2e75-4dc6-bd9c-12f8bee85cb8)

8. Applicare a tutti i tag `<a>` della classe `nav` un colore del testo nero

![punto_8](https://github.com/user-attachments/assets/212d9782-fa5b-4294-bc1f-e9dfeac32a6e)

9. Assegnare in tutte le pagine (`home.html`, `courses.html`, `contacts.html`, `tpsi_5a_24_25.html`) al `div` subito sotto il `div` di chiusura della classe `.header` la classe `main`

10. Settare per la classe `main` le seguenti regole (allineamento al centro della pagina per il div .main)
    * larghezza e lunghezza: 900px
    * margine alto e basso: 0
    * margine destro e sinistro: auto
