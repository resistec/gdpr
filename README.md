# Magyar & Angol GDPR Kérvény Sablon / GDPR Request Template

**Összefoglaló**: Az Európai Unió (EU) 2016-os General Data Protection Regulation (GDPR)-jának köszönhetően jogod van adataid törlését kérvényezni bármely weboldaltól vagy adatkezelőtől email-ben vagy telefonon az adatkezelő Adatvédelmi Tisztviselőjén (DPO) keresztül. Az alábbi oldalon angol és magyar nyelvű GDPR kérvény sablonokat találsz, illetve tanácsokat adataid proaktív védelmére.

# Mi a GDPR?

A GDPR (Általános Adatvédelmi Rendelet) egy európai uniós szabályozás, amely az [adatvédelemről](https://nki.gov.hu/it-biztonsag/kiadvanyok/szorolapok/az-adatbiztonsag-alapelvei/) és a magánélet védelméről szól. Célja, hogy rendelkezési jogot biztosítson minden állampolgár számára [személyes adataikkal](https://nki.gov.hu/wp-content/uploads/2018/06/201805-ouch-may-hungarian.pdf) kapcsolatban. 

A GDPR biztosítja, hogy a vállalatok biztonságosan és átláthatóan kezeljék felhasználóik és ügyfeleik személyes adatait. A rendelet minden olyan szervezetre vonatkozik, amely a EU-s állampolgárok vagy lakosok adatait kezeli, illetve az EU területén végez adatkezelői tevélenységet.

További információk: 
- GDPR tanácsadás, [*Gyakran ismételt kérdések*](https://gdpr-tanacsadas.hu/gyakran-ismetelt-kerdesek/)
- [A GDPR magyar nyelvű átirata](https://net.jogtar.hu/jogszabaly?docid=A1600679.EUP)

# GDPR kérvény: Miért kell ez nekem?

A GDPR kérvény egy hivatalos kérelem, amit akkor nyújthatsz be, ha szeretnél hozzáférni a rólad tárolt adatokhoz, illetve azok módosítását vagy törlését kéred.

A GDPR-ra hivatkozva megvédheted személyes adataidat, és biztosíthatod, hogy jogaidat tiszteletben tartsák. 

> Ha bűncselekmény áldozata vagy, fordulj a rendőrséghez mielőtt adatot törölnél, vagy naplózd a károkozás és -csökkentés részleteit.

Okok, amiért töröltetni szerethetnéd magadat: 

- adataidat hozzájárulás nélkül tették nyilvánossá;
- olyan adataid kerültek nyilvánosságra, amik már nem relevánsak, régiek vagy [veszélyesek](https://nki.gov.hu/it-biztonsag-kategoria/adathalaszat/);
- sok [spam](https://nki.gov.hu/it-biztonsag/tudastar/levelszemet-spam/) vagy [phishing](https://nki.gov.hu/it-biztonsag/tudastar/adathalasz-tartalom-phishing/) üzenetet kapsz.

További információkat az alábbi oldalakon találhatsz: 

- Nemzeti Kibervédelmi Intézet, [*Ezeket érdemes tudni a GDPR-ról és a webes sütikről*](https://nki.gov.hu/it-biztonsag/elemzesek/ezeket-erdemes-tudni-a-gdpr-rol-es-a-webes-sutikrol/)
- Nemzeti Kibervédelmi Intézet, [*GPDR-hoz kapcsolódi hírek, cikkek*](https://nki.gov.hu/it-biztonsag-cimke/gdpr/)
- Nemzeti Kibervédelmi Intézet, [*Hová fordulhatunk segítségért digitális visszaélések esetén?*](https://nki.gov.hu/wp-content/uploads/2021/05/digit%C3%A1lis-vissza%C3%A9l%C3%A9sek.pdf)
- Nemzeti Adatvédelmi Információszabadság Hatóság (NAIH), [*Adatvédelmi tisztviselő nyilvántartás*](https://dpo-online.naih.hu/DPO/Search)

# Hogyan találjam meg, mi van rólam az interneten?

Az egyszerű válasz: google-zd ki magad! 

Használd a következő [összetett kereső kifejezéseket](https://bpdigital.hu/keresesi-operatorok-specialis-keresesek/) ("advanced google dorks") a saját neveddel egy egyszerű böngészőn keresztül (pl. [DuckDuckGo](https://duckduckgo.com/), [Chrome](https://www.google.com/chrome/)): 

```python
#Név permutációk
""keresztnév" "vezetéknév""
""vezetéknév" "keresztnév""
#ha van középső neved akkor azt középre illeszd be két további idézőjel közé

"keresztnév" AND "vezetéknév"
"vezetéknév" AND "keresztnév"
inurl:"vezetéknév keresztnév"
intitle:"vezetéknév keresztnév"
intext:"vezetéknév keresztnév"

("vezetéknév keresztnév" | "keresztnév vezetéknév") AND "lakhely_település"
("vezetéknév keresztnév" | "keresztnév vezetéknév") AND "iskola"
("vezetéknév keresztnév" | "keresztnév vezetéknév") AND "munkahely"
#az "AND" operátor után beilleszthetst bármilyen kulcsszót, ami, úgy gondolod, specifikus rád, pl. kiskutya neve, sportág, sportverseny

#Felhasználóneves keresések
inurl:felhasználónév
site:facebook.com inurl:felhasználónév
site:tiktok.com inurl:felhasználónév
#stb.

#Weboldal-specifikus keresések
"vezetéknév keresztnév" inurl:.nebih.hu (ha a nebih weboldalán szeretnél magadról adatot találni)
"vezetéknév keresztnév" inurl:elte.hu (ha pl. az ELTE-n tanulsz vagy dolgozol)
#stb.
```

A fenti példák egy-egy sora (amelyik nem # jellel kezdődik) felel meg egy adott keresésnek, ami sok-sok találatot fog hozni.

A pozitív (rád vonatkozó) találatok URL-jét mentsd el egy biztonságos helyre! Jegyezd fel az oldal nevét és adatvédelmi tisztviselőjének (DPO) kapcsolatfelvételi adatait!

**Tipp**: linux számítógépet használók kipróbálhatják [**Poison**](https://github.com/resistec/poison) nevű automatizációs eszközömet is, ami segít a fenti folyamat felgyorsításában.

# Adatvédelmi Tisztviselő / Data Protection Officer

A GDPR szerint az adatvédelmi tisztviselő (DPO) egy olyan személy, aki azért felelős, hogy egy szervezet megfeleljen az adatvédelmi szabályoknak. A DPO figyelemmel kíséri az adatkezelési folyamatokat, tanácsot ad az adatvédelemmel kapcsolatos kérdésekben, és kapcsolatot tart a felügyeleti hatóságokkal. Az ő feladata, hogy biztosítsa, hogy az adatokat biztonságosan kezeljék és a jogszabályokat betartsák.

Ha szeretnéd, hogy töröljék az adataidat, érdemes az adatvédelmi tisztviselőt (DPO) megkeresni. Ő az a személy, aki segít az ilyen kérések intézésében, ő tudja biztosítani, hogy a törlési kérelmed megfelelően legyen kezelve és a jogszabályoknak megfelelően történjen. Írj neki egy e-mailt vagy keresd meg más hivatalos úton, és jelezd, hogy mely adatokat szeretnéd eltávolíttatni.

Ha szeretnéd felvenni a kapcsolatot az adatvédelmi tisztviselővel (DPO), akkor először nézd meg a vállalat vagy szervezet weboldalát. Gyakran az **adatvédelmi nyilatkozatban** vagy a **kapcsolat menüpont** alatt megtalálod az elérhetőségeit. Ha ott nem találod, próbáld meg az **ügyfélszolgálatot** megkeresni, ők biztosan tudnak segíteni. E-mailben vagy telefonon is keresheted a DPO-t, de mindig használd a hivatalos csatornákat, hogy biztosan célba érjen a kérésed.

A bejegyzett tisztviselőkre rákereshetsz a Nemzeti Adatvédelmi Információszabadság Hatóság (NAIH) [*Adatvédelmi tisztviselő nyilvántartás*](https://dpo-online.naih.hu/DPO/Search)ában.

> Ha nem találsz adatvédelmi tisztviselőt egy weboldalhoz, küldj egy email-t az oldal:
> - info@ vagy hasonló általános email címére
> - jogászának / jogi képviselőjének
> - fenntartójának
> - a NAIH-nak (ezzel jelented a weboldalt a magyar hatóságoknál)


# Sablon GDPR kérvény / Template of a GDPR Request

Az alábbi sablon GDPR kérvényt felhasználhatod, hogy kérvényezd adataid törlését. Ezeket a kérvényeket érdemes email-ben elküldened arról az email címről, amelyről az adott szolgáltatásra, weboldalra vagy adatkezelőnél regisztráltál.

Nem érdemes a már megadott adatoknél többel ellátni az adatkezelőt, ám tudd, hogy bizonyos adatokat (pl. név, elérhetőség) a törléshez egyes esetekben meg kell majd adnod.

Amit meg kell majd változtatnod a sablonban:

- a címzett (adavédelmi biztos / weboldal) email címe
- a küldő email címe
- webcímek (URL), amiket töröltetni szeretnél
- teljes neved az aláírásban
- keltezés (város, dátum)

## Magyar nyelven

```python
Tárgy: GDPR Kérvény személyes és különleges adataim teljeskörű és végleges törlésére

Tisztelt Hölgyem / Uram!

Az EURÓPAI PARLAMENT ÉS A TANÁCS 2016/679 Általános Adatvédelmi Rendeletének (a továbbiakban: GDPR) 17. cikkében szereplő jogommal élve kérem minden személyes és különleges adatom teljeskörű és végleges törlését.

A következő webcímeken személyes adatok találhatóak, ám a jelen kérvény túlmutat rajtuk: 

[url-ek]

Felhívom szíves figyelmét, hogy a GDPR 19. cikke alapján a törlésről az adatkezelő köteles engem, továbbá mindazokat értesíteni, akiknek korábban az adatot adatkezelés céljára továbbították. Amint ezt megtették, kérem tájékoztassanak erről. 

A választ az alábbi e-mail címre kérem megküldeni: [email].

Szeretném felhívni szíves figyelmét, hogy a törvényben meghatározott törlési kötelezettség nem teljesítése esetén, az Infotv. 52. § (1) bekezdése értelmében a Nemzeti Adatvédelmi és Információszabadság Hatóságnál bejelentéssel bárki vizsgálatot kezdeményezhet arra hivatkozva, hogy személyes adatok kezelésével kapcsolatban jogsérelem következett be, vagy annak közvetlen veszélye fennáll.

Együttműködését köszönöm!

Tisztelettel:
[Név)

Kelt: [város], [dátum]

```

## Angol nyelven

```python
Subject: GDPR Request for the complete and permanent erasure of personal and special data

To whom it may concern,

In accordance with the 2016/679 General Data Protection Regulation of the European Parliament and of the Council, in an intended use of my right, I request the complete and permanent erasure of all personal and special data you hold in relation to me,

Specifically, the following webpages have been identified for this request, although action regarding them does not necessarily constitute all your legal obligations in this case:

[URLs]

I would like to draw your kind attention to that, according to Article 19 of the GDPR, the data controller is obliged by the law to notify me and all related parties who have been provided with my data of the procedures undertaken in compliance with this request and the relevant international and national laws and regulations.

Please send me an email confirmation once you have completed the erasure process.

You can contact me at: [email].

Furthermore, I would like to inform you that anyone holds the right to initiate legal action against you or any related data controller at the National Authority for Data Protection and Freedom of Information upon reasonable doubt for non-compliance.

Thank you for your cooperation!

Faithfully,
[Full Name]

[Date], [location]
```

# Proaktív adatvédelem

GDPR kérvények benyújtása utólagos enyhítése digitális lábnyomodnak. Míg ezen technika elengedhetetlen a legtöbb ember esetében, sok jövőbeli munkát spórolhatsz meg magadnak, ha adataidat még az internetre való kikerülésük előtt elkezded védeni. Az alábbi tanácsok egy ilyen proaktív védelmi vonal felállításában segítenek:

1. Ne adj meg valós személyes adatokat, ahol lehet!
2. Ahol muszáj, a lehető legkevesebb személyes adatodat add meg!
3. Védd adataidat!

---

Pár hasznos adatszivárgást limitáló **böngésző kiegészítő/bővítmény**:

- Privacy Badger: [Chrome](https://chromewebstore.google.com/detail/pkehgijcmpdhfbdbbnkijodmdjhbjlgp) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/) | Safari
- uBlock Origin: [Chrome](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=homepage-collection-featured) | Safari
- Random User-Agent (Switcher): [Chrome](https://chromewebstore.google.com/detail/random-user-agent-switche/einpaelgookohagofgnnkcfjbkkgepnp) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/random_user_agent/) | Safari
- CSS Exfil Protection: [Chrome](https://chromewebstore.google.com/detail/css-exfil-protection/ibeemfhcbbikonfajhamlkdgedmekifo) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/css-exfil-protection/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) | Safari
- Popup Blocker (strict): [Chrome](https://chromewebstore.google.com/detail/popup-blocker-strict/aefkmifgmaafnojlojpnekbpbmjiiogg) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/popup-blocker/) | Safari
- ClearURLs: [Chrome](https://chromewebstore.google.com/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) | Safari

Ezeket általában laptopon és otthoni számítógépes álláson tudod telepíteni a böngésződ kiegészítők / bővítmények (addons / extensions) áruházából ([Chrome](https://chromewebstore.google.com/) | [Firefox](https://addons.mozilla.org/en-US/firefox/) | [Safari](https://apps.apple.com/us/story/id1377753262)).

Hogyan telepíts böngésző kiegészítőket **telefonról**: 

- [Chrome](https://support.google.com/chrome_webstore/answer/2664769?hl=hu#zippy=%2Ctelep%C3%ADt%C3%A9s-a-telefonra)
- [Firefox](https://support.mozilla.org/hu/kb/firefox-android-kiegeszitok-keresese-es-telepitese)
- [Safari](https://hasznaltalma.hu/tippek-es-trukkok/2022/02/05/a-legjobb-safari-bovitmenyek)

Használhatsz **alternatív** böngészőket és keresőmotorokat is:

| Böngésző (app) | Keresőmotor (technológia) |
| --- | --- |
| https://www.mozilla.org/en-US/firefox/browsers/mobile/focus/ | https://search.brave.com/ |
| https://duckduckgo.com/app | https://metager.org/ |
| https://librewolf.net/ | https://duckduckgo.com/ |

> Ezen túl pedig érdemes **minden internetes felületen az általános adatvédelmi és adatkezelési beállításokat a számodra legkedvezőbb módon beállítani**.

# Figyelem!

Az oldalon feltűntetett információk tájékoztató jellegűek; az azok felhasználásából származó jogi következményekért a szerző nem, csakis a felhasználó felelős!
