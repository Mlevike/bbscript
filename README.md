# bbscript

bbscript - Egy egyszerű szkript szöveg BetaBrite 1036 típusú fényújságra küldéséhez.

Szintaktika:

bbscript [Üzenet] [Port] [Paraméterek]

Lehetséges paraméterek:

-c -C --color --COLOR [Szín]

A szöveg színének beállítása, az alábbi színek lehetségesek ( A szín paraméter a három betűs azonosítót fogadja el):

[RED] - Piros

[LRD] - Halvány piros

[GRN] - Zöld

[LGN] - Halvány zöld

[AMB] - Borostyán

[BRN] - Barna

[ORG] - Narancssárga

[YEL] - Citromsárga

[RB1] - Szivárvány 1

[RB2] - Szivárvány 2

[MIX] - Kevert színek

[ACL] - Automata színbeállítás, ez az alapértelmezett

-s -S --speed --SPEED [Sebbesség (1-5)]

A szöveg sebességének beállítása 1-tól 5-ig tartó intervallumon.

-m -M --mode  --MODE [Mód]

A szöveg megjelenítési üzemmódjának beállítása, az alábbi módok lehetségesek:

 [AUT] - Automatikus üzemmód, a kijelző az üzenethez a módokat automatikus választja ki. Ez az alapértelmezett. 

 [SPC5] - Cycle colors üzemmód, a kijelzőn váltakozó színekkel jeleníti meg az üzenetet.

 [FLS] - Flash üzemmód, az üzenetet villogtatja a kijelzőn.

 [HLD] - Hold üzemmód, az üzenetet több másodpercig a kijelzőn tartja.

 [SPC3] - Interlock üzemmód, az üzenetet kétsoronként felbontja és kétoldalról egymásra csúsztatja.

 [RLUP] - Roll UP üzemmód, a kijelzőn az üzenet felfelé gördül.

 [RLDN] - Roll DOWN üzemmód, a kijelzőn az üzenet lefelé gördül.

 [RLL] - Roll LEFT üzemmód, a kijelzőn az üzenet balra gördül.

 [RLR] - Roll RIGHT üzemmód, a kijelzőn az üzenet jobra gördül.
 
 [ROT] - Rotate üzemmód, az üzenetet a kijelzőn vízszintesen jobbról balra forgatja.

 [CRT] - Condensed Rotate üzemmód, az üzenetet a kijelzőn vízszintesen jobbról balra forgatja és közben oldalról összenyomja, hogy a mozgás hatását jobban szemléltesse.

 [SCR] - Scroll üzemmód, folyamatosan görgeti az üzenetet lentről felfelé a kijelző tetejére, majd tovább felfelé míg kifut a képből.

 [SPC2] - Snow üzemmód, a jelenlegi üzenetre ír havazó hatással.

 [SPC1] - Sparkle, új üzenetet pezsegtet a jelenlegi üzenetre. Az üzenet megáll a kijelzőn ha egyszerre kifér és nincs következő üzenet.

 [SPC6] - Spray üzemmód, az üzenetet pontonként, jobbról balra a kijelzőn keresztül "beporlasztja" 

 [SPC7] - Starburst üzemmód, az üzenetet tűzijátékokkal berobantja a kijelzőre.

 [SPC4] - Switch üzemmód, az üzenet karaktereit különböző irányokból kitolja a kijelzőről. Az első karakter felfelé tolódik, a következő lefelé stb.

 [SPC0] - Twinkle üzemmód, oszcilláló, villódzó, mozgó hatás.

 [WIUP] - Wipe UP üzemmód, a jelenlegi üzenetet alulról felfelé felülírja az új üzenettel.

 [WIDN] - Wipe DOWN üzemmód, a jelenlegi üzenetet felülről lefelé felülírja az új üzenettel.

 [WIL] - Wipe LEFT üzemmód, a jelenlegi üzenetet jobbról balra felülírja az új üzenettel.

 [WIR] - Wipe RIGHT üzemmód, a jelenlegi üzenetet balról jobbra felülírja az új üzenettel.

-a -A --animation --ANIMATION : Animáció beillesztése a szöveg elé 

-f -F --font --FONT : Betűtípus beállítása
