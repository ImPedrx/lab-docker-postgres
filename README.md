# Laboratório Docker + PostgreSQL

Este é um laboratório simples criado para estudo de Docker e PostgreSQL.

## Como usar
1. Clone este repositório
2. Execute: `docker-compose up -d`
3. Acesse o container: `docker exec -it meu_postgres bash`
4. Conecte no banco: `psql -U admin -d labdb`
5. Execute os comandos do arquivo `script.sql`

## Objetivo
- Aprender a subir containers no Docker
- Criar e manipular tabelas no PostgreSQL
- Praticar SQL básico
