# Tecshare

API para o serviço de retomados

## Instalation

### Database

Fill `.env` variables `DB_DATABASE, DB_USERNAME, DB_PASSWORD`

Run migrations

    php artisan migrate

### Publish jwt token

    php artisan jwt:secret