<a href="https://trubacizaslavlja.rs/"><img src="media/cover.jpg" alt="Trubači Stars, naslovna strana na laptopu i telefonu" width="100%"></a>

# Trubači Stars

Sajt od 105 strana za trubački orkestar iz Leskovca koji svira na slavama, krštenjima i rođendanima po celoj Srbiji, a zakazuje se samo telefonom.

**[trubacizaslavlja.rs](https://trubacizaslavlja.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/trubaci-stars) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Trubači Stars</td></tr>
  <tr><td><b>Delatnost</b></td><td>Trubački orkestar za slavlja</td></tr>
  <tr><td><b>Lokacija</b></td><td>Leskovac</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt sa više strana</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, nginx, FastCGI cache, JSON-LD, self-hosted fonts</td></tr>
</table>

## O projektu

Trubači Stars su trubački orkestar iz Leskovca koji putuje po celoj Srbiji i svira na slavama, krštenjima, rođendanima, maturama i drugim proslavama. Orkestar se zakazuje telefonom: ljudi zovu i pitaju dve stvari, da li je datum slobodan i koliko košta. Zato sajt treba da čoveka koji traži trubače u svom gradu, za svoju priliku, u što manje koraka dovede do broja telefona.

Pored šest osnovnih strana ima još 27 strana za prilike i slave i 60 strana za gradove, a sve dele sedam zajedničkih PHP fajlova. Kad je klijent tražio treći domen, izmerio sam kako stoje prva dva i umesto trećeg ih razdvojio po nameri pretrage. Sadržaj o slavljima i svadbama prešao je ovamo uz preusmerenja 301. Najteža greška bilo je pomeranje rasporeda koje Googleov laboratorijski test nije video: pri hladnoj poseti rezervni font je bio širi od pravog, pa su dugmad u hero sekciji padala u drugi red i onda skakala nazad.

## Šta sam uradio

- Nigde nema kontakt forme: pet puteva do istog broja, uz fiksnu traku za poziv, Viber i WhatsApp na telefonu
- Sopstveni brojač poziva koji za svaki klik na broj beleži vreme, stranu i dugme, bez kolačića i bez IP adrese
- Cenovnik koji objašnjava šest faktora od kojih cena zavisi, umesto da nabraja cifre
- Imena gradova ispravljena na 191 mestu na 58 strana, gde je šablon lepio padeške nastavke na nominativ
- Izmišljena ocena sa 127 glasova skinuta sa 158 strana na oba sajta orkestra
- Rezervni font sa `size-adjust: 95%` i `font-display: optional` na svih 18 deklaracija, čime je pomeranje nestalo

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 91 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `BreadcrumbList`, `FAQPage`, `LocalBusiness`, `MusicGroup`, `Organization`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Trubači Stars, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Trubači Stars, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Sekcija &quot;Više od muzike - Tradicija i strast&quot;">
<sub>Sekcija "Više od muzike - Tradicija i strast"</sub>

<img src="media/inner-2.webp" alt="Kako funkcioniše: četiri koraka od poziva do nastupa, pa muzika za svaku priliku">
<sub>Kako funkcioniše: četiri koraka od poziva do nastupa, pa muzika za svaku priliku</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
