# Laravel: 1 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=yaKkTeIlkTU)

## Apie ką kalbėjome ir ką nuveikėme

1. [PHP FIG](http://php-fig.org): 

* [PSR-1](http://www.php-fig.org/psr/psr-1/) (Basic Coding Standard)
* [PSR-2](http://www.php-fig.org/psr/psr-2/) (Coding Style Guide)
* [PSR-0](http://www.php-fig.org/psr/psr-1/) (Autoloading Standard (deprecated))
* [PSR-4](http://www.php-fig.org/psr/psr-2/) (Autoloader)

2. [Composer](https://getcomposer.org): PHP trečiųjų šalių bibliotekų valdymo įrankis, įdiegimas savo kompiuteryje

3. [Packagist](https://packagist.org): pagrindinė Composer bibliotekų repozitorija (saugykla)

4. [MVC (model-view-controller) patternas](https://realpython.com/blog/python/the-model-view-controller-mvc-paradigm-summarized-with-legos/) ir veikimo principas, privalumai. Gaminame savo minimalų framework'ą pagal MVC.

4.1. Pagrindiniai projekto katalogai ir failai:

* `index.php` - entry point'as, kuriame automatiškai pagal URL nusprendžiama, kokio controllerio ir kokio jo actiono (metodo) reikės
* `app/controllers` - aplikacijos controlleriai

4.2. Naudojame Composer suteikiamą PSR-4 autoload'ą, aprašomą `composer.json` faile, generuojam `vendor/autoload.php`, kuris atlieka reikiamą darbą pasinaudojus komandine eilute: `composer dumpautoload`.

## Užduotys

1. Susikurti naują controller'į, skirtą darbui su produktais, reikalingi metodai: rodyti visus, rodyti vieną, pridėti naują.

2. Jau turimo `PostsController` metodai atitinkamai turi rodyti paprastus šablonus pasinaudojant savo HTML žiniomis (duomenų bazė nereikalinga, atvaizduojami dummy duomenys):

* `create` - forma su pavadinimo ir teksto laukais
* `showSingle` - puslapis su antrašte ir tekstu
* `showAll` - sąrašas su įrašų pavadinimais ir jų sukūrimo datomis

Kiekvienam metodui - atitinkamai naujas `.html` failas, kur kiekvieną saugome naujai sukurtame `resources/views` kataloge.
