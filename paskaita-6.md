# Laravel: 6 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=WTzENGJvo5c)

## Apie ką kalbėjome ir ką nuveikėme

1. Eloquent modeliuose esantys mass assignment metodai `create()` ir `fill()` bei `$fillable` ir `$guarded` prasmė whitelistinant arba blacklistinant atributus.

2. Apsivalom kontrolerį nuo nereikalingo kodo.

3. Puslapiavimas.

4. Middlewares ir request onion, jų kūrimas,  `app/Http/Kernel.php`, kuriame "pajungiame" naujus middlewares prie jau esamų.

5. Routes grupavimas, `web` ir `api` route grupių skirtumai.

6. Resurso kūrimas su komanda `php artisan make:model -a Product` ir rezultatai.

7. `php artisan make:auth` komanda, generuojanti views'us, route'us tam, kad įgalintų vartotojų funkciją. Sugeneruotų ir naudojamų failų aptarimas.

8. Tvarkomės esamus viewsus, kad jie išplėstų naujai sugeneruotą šabloną `layouts.app`.

## Užduotys

1. Viskas, ko dar nedarėt iš ankstesnių paskaitų :)

2. Pabaigti paskaitos metu pradėtą daryti produktų valdymą pagal tai, ką jau mokame.

3. Sukurti `Brand` (prekės ženklas) resursą ir jo valdymą:

* ID
* Pavadinimas
* Logo Path
* SoftDeletes
* Timestamps

4. Sukurti `UserSeeder`, kuris prikurtų netikrų user'ių ir kad galėtumėm su bet kuriuo iš jų (ar bent vienu) prisijungti.

5. Sukurti atitinkamai ir `ProductSeeder`, `BrandSeeder` bei visus seederius callinti iš bendro `DatabaseSeeder`.

**Bus papildyta**

## Projektas

1. Turėdami savo idėją projektui papasakokite man apie ją el. paštu jposiunas gmail com. Trumpas aprašymas ir wireframe, pieštas nors ir ranka ant popieriaus, kaip vartotojas vaikščios po aplikaciją, [pavyzdys čia](http://www.appsmarche.com/dashboard/blog_img/wireframe-4.png). Nepersistenkit ir nesijaudinkit, kad gal sugalvojot per mažai, užtenka bent poros langų ir juos puikiai padaryt:)

2. Kol būsiu išvykęs, rekomenduoju pradėti nuo paprasčiausių HTML/CSS/JS failų, be jokio Laravelio, tiesiog pasiruošti vizualią dalį panaudojant savo frontendo žinias. Bootstrapas, materialize, etc, labai welcome. Template'ą versijuokite GitHub'e ir atsiųskite savo repozitorijos URL man el paštu taip pat.

3. Užsiėmimų metu šabloną po truputį perkelsite į šviežutėlį frameworką ir dirbsite daugiau su backend dalimi, t.y. tai, ką dabar ir mokomės daugiausiai.

4. Jei neturite idėjų projektui, tai šioks toks rinkinys, ką galima būtų pradėti daryti:

* paprastas reprezentacinis tinklalapis su minimaliu turinio valdymu, laisva tema

* katalogas / archyvas: lankytinos vietos - gamtiniai objektai, muziejai, etc; restoranai / kavinės; mėgstamiausi klipai / filmai / serialai; muzikos albumai; renginiai; interneto nuorodos ar pan.; etc

* blog'as / žurnalas, skatinantis rašyti kasdien / užrašinė

* biudžeto planavimas / skaičiuoklė

* failų saugykla / nuotraukų albumas

* forumas / nišinis socialinis tinklas

* e. parduotuvė: prekių katalogas, krepšelis
