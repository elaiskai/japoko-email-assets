# JAPOKO welcome serija — laiškas Nr. 1

## Kampanijos paskirtis

- Pirmasis welcome serijos laiškas.
- Tikslas: pasveikinti naują prenumeratorių, aiškiai pateikti pirmojo apsipirkimo kodą ir padėti pradėti pažintį su JAPOKO per kategorijas, ne pavienius produktus.
- Kalba: lietuvių.
- Siuntėja: Metodija / JAPOKO.

## Tema ir priešlaiškis

- Tema: **Sveiki atvykę į JAPOKO – Jūsų –5 % kodas viduje**
- Priešlaiškis: **ARIGATO – mažas ačiū už prisijungimą ir keturios japoniškų atradimų kryptys pradžiai.**

## Pasiūlymas

- Kodas: `ARIGATO`
- Vertė: –5 % pirmajam apsipirkimui.
- Pastaba: nuolaidos nesumuojamos.
- Kodas ir sąlyga perkelti iš šiuo metu aktyvaus JAPOKO welcome laiško. Prieš pakeičiant automatizaciją reikia patikrinti, kad kodas vis dar aktyvus WooCommerce.

## Vizualinė kryptis

Sujungti du šaltiniai:

1. Pateiktas japoniško restorano reference: kreminis fonas, juodos horizontalios juostos, raudoni akcentai, 2 × 2 kortelių ritmas ir ryški kondensuota tipografija.
2. Dabartinės JAPOKO kampanijos: oficialus logotipas, raudona `#D71635`, juoda `#231F20`, „Antonio“ antraštės, asmeniškas Metodijos balsas ir pasakojimas prieš pardavimą.

Reference prekės ženklas, tekstai, produktai ir iliustracijos nebuvo kopijuojami.

Kategorijų vaizdai sugrupuoti poromis pagal vienodus fonus: LaQ ir kanceliarija — geltoni; kūno priežiūra ir dovanos — šviesiai mėlyni; prekės namams ir saldumynai — švelniai rausvi. Dovanų ir saldumynų kompozicijoms fonai pakeisti išsaugant produktų turinį.

## Kategorijos

1. LaQ konstruktoriai — `https://japoko.com/produkto-kategorija/laq-konstruktoriai/`
2. Japoniška kanceliarija — `https://japoko.com/produkto-kategorija/japoniska-kanceliarija/`
3. Kūno priežiūra — `https://japoko.com/produkto-kategorija/kuno-prieziura/`
4. Dovanų rinkiniai — `https://japoko.com/produkto-kategorija/dovanos/dovanu-rinkiniai/`
5. Prekės namams — `https://japoko.com/produkto-kategorija/prekes-namams/`
6. Japoniški saldumynai — `https://japoko.com/produkto-kategorija/japoniski-saldumynai/`

Kategorijų nuotraukos paimtos iš ankstesnio JAPOKO naujienlaiškio projekto, kuriame jos buvo parsisiųstos iš oficialios JAPOKO svetainės.

## Prekės ženklo ir kontaktų šaltiniai

Patikrinta 2026-08-16:

- `https://japoko.com/`
- `https://japoko.com/musu-istorija/`
- kliento pateiktas klausimynas;
- oficialus pateiktas logotipas ir „Antonio“ šriftų šeima;
- dabartinės Omnisend automatizacijos ir 2026 m. kampanijos.

Kontaktai:

- MB „Creator Japonicus“
- Bajorų g. 9, Migūnai, Vilniaus raj., LT-13243, Lietuva
- `info@japoko.com`
- `https://japoko.com/`

## Diegimo pastabos

- `newsletter.html` naudoja vietinius `assets/` kelius ir skirtas peržiūrai bei patvirtinimui.
- Prieš perkeliant į Omnisend vaizdus reikia įkelti į viešą HTTPS talpyklą arba Omnisend vaizdų biblioteką ir pakeisti `src` adresus.
- `{{ unsubscribe_url }}` yra aiški atsisakymo žymos vieta; diegiant ji turi būti pakeista Omnisend atsisakymo nuoroda.
- Metodijos portreto blokas numatytas šiame laiške, bet bus įdėtas gavus naują, kliento patvirtintą nuotrauką. Rekomenduojamas vertikalus arba kvadratinis portretas natūralioje šviesoje, neutraliame fone, nuo juosmens arba krūtinės aukštyn.
