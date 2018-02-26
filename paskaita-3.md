# Laravel: 3 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=3A_KZalXBJ0)

## Apie ką kalbėjome ir ką nuveikėme

1. Blade template engine:

* Direktyvos aplikacijos šablonui valdyti: `@yield()`, `@extends()`, `@section()`, `@include()`

2. Duomenų kėlimas į `Collection` klasę, kurios objektas sukuriamas iš masyvo, patogesni veiksmai. [Dokumentacija](https://laravel.com/docs/5.6/collections)

3. [Helpers](https://laravel.com/docs/5.6/helpers): `collect()`, `dd()`, `abort()`.

4. Duomenų bazės valdymas:

* [Migrations](https://laravel.com/docs/5.6/migrations) - schemos valdymas, t.y. lentelės ir jų struktūra

* [Seeders & Faker](https://laravel.com/docs/5.6/seeding) - DB užpildymas fake duomenimis.

5. DB užklausų vykdymas duomenų įrašymui ir gavimui naudojant [Database Query Builder](https://laravel.com/docs/5.6/queries)

## Užduotys

1. Posts sąraše kiekvieno įrašo antraštė turi būti aktyvi nuoroda į tą įrašą. Pvz, `http://localhost:8000/posts/10`.

2. Patobulinti `PostsTableSeeder` taip, kad autorius nebūtų nustatomas visiems įrašams, t.y. atsitiktinai jis gali būti tuščias arba užpildytas.

3. Sukurti migraciją ir seederį, skirtą kontaktų valdymui. Lentelės pavadinimas `contacts`. Reikalingi columnai: `id`, `name`, `email`, `number`, `address`.

4. Pridėti `PostsTableSeeder` bei `ContactsTableSeeder` kvietimus į `DatabaseSeeder` klasę, jog komanda `php artisan db:seed` pripildytų duomenų bazę be jokių option'ų.

5. Sukurti viską nuo A iki Z įrašo kūrimo formai:

* naujas route'as, nurodantis į puslapį `/posts/create`

* įrašo kūrimo formos metodas `create()` kontroleryje `PostsController`

* views'as su HTML forma įrašo kūrimui (pavadinimas, turinys, autorius, draft), kuris extendina `layout` failą panaudojant `section` direktyvas.
