# Laravel: 5 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=vFoK-Xv8Urg)

## Apie ką kalbėjome ir ką nuveikėme

1. Naudingi resursai:

* Naujienlaiškiai: [PHP weekly](http://www.phpweekly.com), [Laravel news](http://laravel-news.com)

* PHP questai (sudėtingas setupas ir naudojimasis, CLI interfeisas): [phpschool.io](https://phpschool.io)

* Interaktyvios pamokos step by step: [CodeSchool](https://codeschool.com)

* Daug bendros informacijos apie PHP naudojimą ir gerąsias praktikas: [PHP The Right Way](http://www.phptherightway.com)

* Nepaminėjau paskaitos metu, bet [Laracasts](https://laracasts.com). Daug nemokamų video pamokų įvairiausiomis temomis ir daugiausiai orientuot į Laravel. Labai geras dėstymo stilius, aiškūs pavyzdžiai ir švarus kodas.

2. Nukreipimas su sesijoje perduodama žinute: `redirect()->with('message', 'žinutės tekstas') ir jos išvedimas po sėkmingo išsaugojimo, redagavimo arba pašalinimo.

3. Requestų validacija, FormRequest klasės, klaidų išvedimas ir duomenų išlaikymas formoje naudojant `old()` funkciją.

4. Pranešimų vertimų saugojimas `resources/lang/en` direktorijoje esančiuose failuose.

5. Eloquent ORM, modelių kūrimas ir naudojimas. Refactoriname savo kontrolerį atsikratydami DB query builderio ir atliekame tuos pačius CRUD veiksmus naudodami modelį.

6. Modelio automatinis susiejimas su lentele DB pagal jo pavadinim, `$table` ir `$fillable` atributai.

## Užduotys

1. Susitvarkyti namuose kuriamą `ContactsController` pagal šios paskaitos medžiagą:

* nukreipimai su žinutėmis po atnaujinimo, įrašymo ir naikinimo

* request input'o validacija ir klaidų išvedimas

* modelio susikūrimas

* modelio panaudojimas vietoj DB query builderio
