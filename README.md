## What is ICES

**ICES (Internet Computer Event System)** is a canister custom event log storage and analysis service on Dfinity. Any canister can access ICES without permission, store the interactive data permanently, and query it through the public API and dashboard provided by ICES.

## ICES backend API service

Technology frameworks used in the ICES backend

* [Hasura](https://hasura.io/) provides graphql APIs
* PostgreSQL  IC on-chain data storage
* Synchronization program [ices-sync](https://github.com/icpfans-xyz/ices-sync)

## Deployment Profiles
* [ices-sync](https://github.com/icpfans-xyz/ices-sync/blob/main/Dockerfile) Dockerfile build ices-sync image

* [docker-compose.yaml](./docker-compose.yaml) Run docker container

* [ices-sql](./db_ices.sql)SQL for database tables and views

## 🔗 Links

* Website **[https://ices.one/](https://ices.one/)**
* Twitter **[https://twitter.com/icesHQ](https://twitter.com/icesHQ)**
* Code **[https://github.com/icpfans-xyz/ices-contract](https://github.com/icpfans-xyz/ices-contract)**