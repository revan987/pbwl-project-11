## Praktikum PHP MVC Pemrograman Berbasis Web Lanjutan FST UIN Sumatera Utara
## Buat Folder _db serta file didalamnya
* database.sql

## Buat Folder app serta empat folder didalamnya
* controllers
* core
* models
* views

## Buat Folder inc serta file didalamnya
* config.php

## Buat Folder layouts serta folder dan file didalamnya
* assets - (1) css; (2) images
* dashboard.php
* home.php

## Buat File index.php
## Inisialisasi Composer
## Set PSR-4
## Install filp/whoops untuk memudahkan informasi error
```
composer require filp/woops
```

## Buat File .htaccess
## Bangun teknik MVC mulai dari
* app/core/Bootstrap.php
* app/core/Controller.php
* app/core/Model.php
* app/core/Error.php

## Setting Model untuk terhubung dengan Database
```
app/models/Namaclass.php
```

## Setting Controller
```
app/controllers/Namaclass.php
```

## Setting View
```
app/view/Namafolder/Namafile.php
```

## Testing
```
http://localhost/php-mvc/
http://localhost/php-mvc/home/index
http://localhost/php-mvc/home/show
http://localhost/php-mvc/home/detail/1
http://localhost/php-mvc/dashboard
```