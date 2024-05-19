# Docker Compose con Node.js e PostgreSQL

Questo repository contiene un piccolo progetto realizzato con Node.js e PostgreSQL. L'applicazione è containerizzata utilizzando Docker Compose per un facile deployment e scalabilità.

## Tecnologie Utilizzate

- **Node.js**: Un runtime JavaScript basato sul motore JavaScript V8 di Chrome per eseguire codice JavaScript al di fuori di un browser web.
- **PostgreSQL**: Un potente sistema di database relazionale open-source.
- **Docker**: Una piattaforma per costruire, distribuire ed eseguire applicazioni utilizzando container.
- **Docker Compose**: Uno strumento per definire ed eseguire applicazioni Docker multi-container.

## Comandi generici

- `docker-compose up`: Questo comando crea e avvia i container definiti nel file docker-compose.yml.
- `docker-compose up --force-recreate`: Questo comando rigenera i container definiti nel file docker-compose.yml.
- `docker-compose up -d`: Avvia i container in modalità "detached" (in background).
- `docker-compose config`: Convalida e visualizza la configurazione Compose completa.
