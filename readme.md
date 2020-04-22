# Laravel X Vue Musing

# Install Dependencies
composer install

# Run Migrations
php artisan migrate

# Import Articles
php artisan db:seed

# If you get an error about an encryption key
php artisan key:generate

# Install JS Dependencies
npm install

# Watch Files
npm run watch
```

## Endpoints

### List all articles with links and meta
``` bash
GET api/articles
```
### Get single article
``` bash
GET api/article/{id}
```

### Delete article
``` bash
DELETE api/article/{id}
```

### Add article
``` bash
POST api/article
title/body
```

### Update article
``` bash
PUT api/article
article_id/title/body
```


```

## Info 
From Brad Traversy [Traversy Media](http://www.traversymedia.com) Youtube tutorial
# laravel-X-vue-Musing
# laravel-X-vue-Musing
# laravel-X-vue-Musing
