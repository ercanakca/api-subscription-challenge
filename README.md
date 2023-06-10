### Kurulum Aşamaları

1. Aşağıdaki komut ile docker build alıp sistemi ayağa kaldırın.
```
docker-compose up -d
```

2. `app` container içine girin.
```
docker-compose exec app bash
```

3. Migrate ve Seed komutlarını çalıştırın
```
php artisan migrate && php artisan db:seed
```

