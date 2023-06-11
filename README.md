Proiect An TMPS --> 

Codul dat este creat pentru a implementa un sistem simplu de vânzare a biletelor folosind diverse șabloane de proiectare.
Acesta utilizează o interfață de linie de comandă (CLI) pentru a interacționa cu utilizatorul și îi oferă următoarele acțiuni:
sellTicket(): Această funcție permite utilizatorului să cumpere un bilet. Utilizatorul este întrebat despre numărul de loc, numărul de rând, dacă locul este VIP și dacă clientul beneficiază de un discount. În funcție de răspunsurile utilizatorului, se creează un obiect Ticket corespunzător și se vinde prin intermediul unui obiect TicketFacade. Apoi, se afișează informații despre biletul vândut și prețul acestuia. La final, se oferă utilizatorului opțiunea de a alege o altă acțiune.
displayTickets(): Această funcție afișează toate biletele disponibile folosind un iterator pentru a itera prin colecția de bilete obținută de la TicketFacade. Biletele sunt afișate unul câte unul, iar utilizatorul primește apoi opțiunea de a alege o altă acțiune.
chooseAction(): Această funcție întreabă utilizatorul să aleagă o acțiune (sell/display/exit). 
În funcție de acțiunea aleasă, se apelează funcțiile corespunzătoare sau se încheie interacțiunea în cazul opțiunii "exit".

În plus, codul importă mai multe clase și module asociate cu șabloanele de proiectare utilizate:

TicketFacade reprezintă o interfață simplificată pentru gestionarea vânzărilor de bilete.
TicketBuilder este utilizat pentru a construi obiecte Ticket într-un mod flexibil și ușor de utilizat.
TicketIterator este un iterator utilizat pentru a itera prin colecția de bilete.
StudentDiscountTicket este o clasă derivată a clasei Ticket care aplică un discount pentru studenți la prețul biletului.
În ansamblu, acest cod demonstrează utilizarea șabloanelor de proiectare pentru a crea un sistem simplu de vânzare a biletelor cu interfață CLI, oferind funcționalități precum cumpărarea de bilete, afișarea biletelor disponibile și gestionarea acțiunilor utilizatorului.
