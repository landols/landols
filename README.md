# Mario Landolfo

Full-stack developer · Santa Maria Capua Vetere (CE)

Progetto, sviluppo e mantengo in produzione applicazioni web per aziende:
portali B2B, piattaforme SaaS e gestionali, dal modello dei dati al deploy.

## Competenze

| Area | Tecnologie |
|---|---|
| Backend | PHP 8.x, Laravel, Symfony, Doctrine, API REST, integrazioni SOAP e FTP/SFTP |
| Frontend | React, TypeScript, Inertia.js, Vite, Tailwind CSS, MUI |
| Dati | MySQL, MariaDB, PostgreSQL, Redis |
| Infrastruttura | Docker, Docker Compose, Traefik, nginx, VPS Linux, storage S3-compatibile |
| Qualità | PHPUnit, Playwright, Laravel Pint, ESLint, code review, ADR |

## Progetti recenti

Il codice dei progetti per i clienti è privato; ne riassumo perimetro e scelte tecniche.

**Portale B2B per la distribuzione di pneumatici**
Vendita fra operatori del settore. Il catalogo si costruisce dai listini dei
fornitori, acquisiti via FTP/SFTP, normalizzati e confrontati con il magazzino.
Laravel 11, Inertia, React 19, MySQL, Docker. Circa 1.850 test automatici,
E2E con Playwright, 36 decisioni architetturali documentate.

**Piattaforma SaaS multi-tenant per siti di piccole e medie imprese**
Generazione dei siti con contenuti assistiti da AI e pubblicazione statica.
Laravel, PostgreSQL, Redis, React 19 con MUI, Astro.

**Gestionale per una rete di scuole dell'infanzia in franchising**
Accessi distinti per famiglie e personale, riservatezza per singolo bambino.
Symfony 7, Doctrine, autenticazione JWT, React e TypeScript, storage S3.

**Libreria di integrazione con provider di hosting e domini**
Pacchetto PHP con contratti, implementazioni reali e mock per le API di
20i e OpenProvider, condiviso fra più applicazioni.

**Migrazione di un e-commerce legacy**
Applicazione PHP 7.4 con catalogo via SOAP portata in container su VPS.

## Metodo

- Test automatici a ogni livello prima del rilascio.
- Decisioni architetturali registrate come ADR, con un glossario del dominio per ogni progetto.
- Ambienti riproducibili con Docker, dallo sviluppo alla produzione.
- Strumenti di sviluppo assistito da AI per review, ricerca di bug e audit di sicurezza:
  [landols/skills](https://github.com/landols/skills).

## Contatti

- Email: mario.landols@gmail.com
- LinkedIn: [linkedin.com/in/mariolandolfo](https://www.linkedin.com/in/mariolandolfo/)
