# Presto.it

Presto.it è una piattaforma di e-commerce ispirata a Vinted, focalizzata sulla compravendita di articoli di seconda mano.

## Tecnologie Utilizzate

Questo progetto è stato sviluppato utilizzando il TALL stack:

- **B**ootstrap CSS: Per uno styling rapido e responsivo
- **G**sap.js: Per interazioni dinamiche lato client
- **L**aravel: Come framework PHP back-end
- **L**ivewire: Per creare componenti dinamici senza scrivere JavaScript

## Funzionalità Principali

- Registrazione e autenticazione utenti
- Caricamento e gestione dei prodotti
- Sistema di ricerca avanzato
- Messaggistica tra utenti
- Gestione delle transazioni
- Responsive design per un'esperienza ottimale su tutti i dispositivi

## Installazione

1. Clona il repository
   ```
   git clone https://github.com/amitpandher03/presto.it.git
   ```
2. Installa le dipendenze PHP
   ```
   composer install
   ```
3. Installa le dipendenze JavaScript
   ```
   npm install
   ```
4. Copia il file .env.example in .env e configura le variabili d'ambiente

5. Genera una chiave dell'applicazione
   ```
   php artisan key:generate
   ```
6. Esegui le migrazioni del database
   ```
   php artisan migrate
   ```
7. Compila gli asset
   ```
   npm run dev
   ```
8. Avvia il server
   ```
   php artisan serve
   ```

## Contribuire

Le pull request sono benvenute. Per modifiche importanti, apri prima un issue per discutere cosa vorresti cambiare.

## Licenza

[MIT](https://choosealicense.com/licenses/mit/)
