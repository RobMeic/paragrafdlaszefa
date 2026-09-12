# Landing page: paragrafdlaszefa.pl

Strona statyczna, bez budowania. Wrzucasz folder i działa.

## Pliki

| Plik | Co to |
|---|---|
| index.html | Cała strona |
| style.css | Style |
| okladka.png | Okładka poradnika w sekcji górnej |
| podglad-pulapka.png, podglad-test.png, podglad-koszty.png | Trzy strony z poradnika w sekcji "Zajrzyj do środka" |
| og-image.png | Obrazek podglądu przy udostępnianiu linku na Facebooku, WhatsAppie, LinkedInie |
| favicon.ico, favicon-32.png, apple-touch-icon.png | Ikony strony |
| robots.txt, sitemap.xml | Dla wyszukiwarek |

## Wdrożenie na Netlify

1. Wejdź na app.netlify.com i zaloguj się.
2. Wybierz "Add new site", potem "Deploy manually".
3. Przeciągnij **zawartość** tego folderu (nie sam folder) na pole zrzutu. Netlify od razu wystawi stronę pod adresem tymczasowym.
4. Sprawdź stronę pod tym adresem, zwłaszcza na telefonie.

## Podpięcie domeny paragrafdlaszefa.pl

W Netlify: "Domain management", potem "Add a domain", wpisujesz paragrafdlaszefa.pl.
Netlify poda wartości, które wpisujesz w panelu DNS u rejestratora domeny:

- rekord A dla domeny głównej na adres IP podany przez Netlify,
- rekord CNAME dla www na adres w postaci nazwa-strony.netlify.app.

Po propagacji DNS (zwykle kilkadziesiąt minut) Netlify samo wystawi certyfikat HTTPS. Jeśli certyfikat nie pojawi się po godzinie, kliknij "Renew certificate" w ustawieniach domeny.

## Po wdrożeniu

1. Sprawdź, czy linki "Kup poradnik" prowadzą do właściwego produktu na Gumroad.
2. Ustaw adres e-mail kontakt@paragrafdlaszefa.pl albo podmień go w stopce na ten, którego faktycznie używasz. Teraz jest tam adres, którego możesz jeszcze nie mieć.
3. Dodaj stronę do Google Search Console i wyślij sitemap.xml.
4. Wstaw link do strony w bio na Instagramie i TikToku.

## Aktualizacja treści

Wszystko jest w index.html, edytujesz w zwykłym edytorze tekstu. Po zmianie wrzucasz folder na Netlify jeszcze raz w ten sam sposób.

Jeśli zmieni się stan prawny, pamiętaj o trzech miejscach: data w sekcji górnej, data w stopce i treść odpowiedzi w sekcji z pytaniami.
