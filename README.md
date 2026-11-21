# Mario Landolfo

Full-stack developer · Santa Maria Capua Vetere (CE)

Progetto, sviluppo e mantengo in produzione applicazioni web per aziende:
portali B2B, piattaforme SaaS e gestionali, dal modello dei dati al deploy.
Il mio stack principale è Symfony, con cui lavoro in Capri Online Srl; nei progetti
indipendenti uso anche Laravel.

## Competenze

| Area | Tecnologie |
|---|---|
| Backend | PHP 8.x, Symfony, Doctrine, Laravel, API REST, integrazioni SOAP e FTP/SFTP |
| Frontend | React, TypeScript, Inertia.js, Vite, Tailwind CSS, MUI |
| Dati | MySQL, MariaDB, PostgreSQL, Redis |
| Infrastruttura | Docker, Docker Compose, Traefik, nginx, VPS Linux, storage S3-compatibile |
| Qualità | PHPUnit, Playwright, Laravel Pint, ESLint, code review, ADR |

## Esperienza

**Capri Online Srl**: sviluppo di applicazioni web in Symfony.

## Progetti recenti

Il codice dei progetti per i clienti è privato; ne riassumo perimetro e scelte tecniche.

**Gestionale per una rete di scuole dell'infanzia in franchising**
Accessi distinti per famiglie e personale, riservatezza per singolo bambino.
Symfony 7, Doctrine, autenticazione JWT, React e TypeScript, storage S3.

**Portale B2B per la distribuzione di pneumatici**
Vendita fra operatori del settore. Il catalogo si costruisce dai listini dei
fornitori, acquisiti via FTP/SFTP, normalizzati e confrontati con il magazzino.
Laravel 11, Inertia, React 19, MySQL, Docker. Circa 1.850 test automatici,
E2E con Playwright, 36 decisioni architetturali documentate.

**Piattaforma SaaS multi-tenant per siti di piccole e medie imprese**
Generazione dei siti con contenuti assistiti da AI e pubblicazione statica.
Laravel, PostgreSQL, Redis, React 19 con MUI, Astro.

**Libreria di integrazione con provider di hosting e domini**
([laravel-20i-openprovider](https://github.com/landols/laravel-20i-openprovider))
Pacchetto PHP con contratti, implementazioni reali, mock e ibride per le API di
20i e OpenProvider, condiviso fra più applicazioni. Test con HTTP simulato e CI.

**Migrazione di un e-commerce legacy**
Applicazione PHP 7.4 con catalogo via SOAP portata in container su VPS.

## Metodo

- Test automatici a ogni livello prima del rilascio.
- Decisioni architetturali registrate come ADR, con un glossario del dominio per ogni progetto.
- Ambienti riproducibili con Docker, dallo sviluppo alla produzione.
- Strumenti di sviluppo assistito da AI per review, ricerca di bug e audit di sicurezza:
  [landols/claude-skills](https://github.com/landols/claude-skills).

## Contatti

- Email: mario.landols@gmail.com
- LinkedIn: [linkedin.com/in/mariolandolfo](https://www.linkedin.com/in/mariolandolfo/)
