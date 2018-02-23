# Laravel: 2 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=CojZaL1cgzE)

## Apie ką kalbėjome ir ką nuveikėme

1. Tęsiam darbą su savo gamybos framework'u:

1.1. Susikuriam views'us `resources/views` kataloge (1 paskaitos savarankiškų darbų užduotis)

1.2. Susikuriam naują pagalbinę klasę `Utils`, kuri turi statinį metodą `view()` ir atvaizduoja mums ankstesniame punkte sukurtus šablonus.

2. Diegiame Laravel framework'ą naudodamiesi komanda `composer create-project --prefer-dist laravel/laravel crm`.

3. Apžvelgiam svarbiausias direktorijas ir failus, su kuriais daugiausiai dirbsime kurso metu.

4. [Laravel dokumentacija](https://laravel.com/docs/5.6)

5. PHP artisan komandinės eilutės programa ir pirmos pažintinės komandos: `serve`, `inspire`, `up`, `down`.

6. `routes/web.php` failas ir baziniai `Route` serviso veiksmai: `get()`, `where()`, `name()`, `callable` argumentas - [anoninimė funkcija](http://php.net/manual/en/functions.anonymous.php) arba adresas į controllerį formatu `Controller@action`, kitamasis `{id}` route'o adrese.

7. [Regular Expressions](https://regexr.com/) - tik užsiminiau ir parodžiau pora pavyzdžių, tikrai naudinga ir reikalinga jau pasiekus pažengusiųjų lygį.

8. Controller'io kūrimas naudojant CLI (command line interface): `php artisan make:controller PostsController` bei pagrindiniai veiksmai, kaip tai siejama su route'ais.

9. `view()` funkcija, kintamųjų perdavimas views'ui, jų atvaizdavimas (`{{ $todayDate }}`) ir manipuliavimas (`@foreach` ciklas), komentarų rašymas (`{{-- komentaras --}}`) naudojantis Blade šablonų varikliuku.

## Užduotys

Bus papildyta.
