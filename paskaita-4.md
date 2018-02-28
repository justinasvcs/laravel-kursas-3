# Laravel: 4 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=duh8HsOrMPQ)

## Apie ką kalbėjome ir ką nuveikėme

1. CRUD operacijos resursų valdymui viename controlleryje ir atitinkami veiksmai, joms įgyvendinti:

* Create (`create()`, `store()`)
* Read (`index()`, `single()`)
* Update (`edit()`, `update()`)
* Delete (`destroy()`)

2. [CSRF (cross-site resource forgery)](https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)) ir direktyva `@csrf`.

3. HTTP protokolo specifikacijos metodai `GET`, `POST`, `PUT`, `DELETE`, jų spoofinimas su direktyva `@method` ir jų panaudojimas kuriant route'us CRUD'ui.

4. Pilnas bazinis `PostsController` sukūrimas

5. `DB` serviso metodai formuojant užklausas: `where()`, `limit()`, `orderBy()`, `offset()`, `first()`, `find()`, `get()`.

## Užduotys

1. Praeitos paskaitos namų darbuose reikėjo įsivesti naują resursą `contacts`, tad reikia pratęsti atitinkamai užbaigiant jo CRUD'ą taip pat, kaip mokėmės šioje paskaitoje. Tip: route'ai, views'ai, controller'io metodai, migracija ir seederis.

2. Praeitos paskaitos užduotys, kurios dar nebuvo atliktos paskaitos metu.
