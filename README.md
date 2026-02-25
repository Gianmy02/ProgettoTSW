# 🌐 Progetto TSW - Tecnologie Software per il Web

### ⚙️ Architettura del Sistema
Il progetto segue rigorosamente il pattern **Model-View-Controller (MVC)** per garantire una netta separazione tra la logica di business e l'interfaccia utente:

* **Model**: Gestione dei dati e della logica di business, con l'implementazione del design pattern **DAO (Data Access Object)** per l'astrazione dello strato di persistenza (MySQL).
* **View**: Interfaccia utente dinamica realizzata tramite **JSP (JavaServer Pages)**, con utilizzo di JSTL per la logica di presentazione.
* **Controller**: Gestione delle richieste HTTP tramite **Java Servlet**, che orchestrano il flusso di dati tra utente e database.

### 🛡️ Funzionalità Implementate
- **Gestione Sessioni**: Autenticazione utente e gestione del carrello tramite sessioni HTTP.
- **Sicurezza**: Protezione contro le vulnerabilità web comuni (es. SQL Injection tramite PreparedStatement).
- **CRUD Completo**: Gestione totale del catalogo prodotti e degli ordini lato amministratore.
- **Dinamismo**: Utilizzo di AJAX per aggiornamenti asincroni della UI senza ricaricamento della pagina.
