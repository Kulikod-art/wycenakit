# WycenaKit

Darmowy generator wycen i ofert PDF dla małych firm: https://wycenakit.onrender.com/

## Funkcje
- pozycje kosztorysu, rabaty i wybrana stawka VAT
- wydruk do PDF z okna drukowania przeglądarki
- automatyczny zapis lokalny i import/eksport JSON
- przykładowe branże, responsywny interfejs
- podgląd pakietu PRO i próbki rzeczywistych materiałów

## Podstrony
- `index.html` — generator, opis produktu PRO, FAQ
- `probka.html` — próbki materiałów z pakietu PRO
- `kalkulator-stawki-godzinowej.html` — darmowy kalkulator opłacalnej stawki godzinowej, marży i VAT
- `kalkulator-marzy-i-narzutu.html` — darmowy kalkulator marży, narzutu, rabatu i VAT
- `jak-wycenic-usluge.html` — bezpłatny poradnik SEO
- `prywatnosc.html` i `informacje.html` — informacje o prywatności i sprzedaży
- `sitemap.xml` i `robots.txt` — odkrywanie stron przez wyszukiwarki
- `PLAN_PROMOCJI_7_DNI.md` — plan testu popytu i promocji

## Uruchomienie
Otwórz `index.html` w przeglądarce lub opublikuj statycznie. Nie wymaga Node, bazy danych ani kluczy API.

## Render
Static site: branch `main`, build command: `echo ready`, publish path: `.`

## Monetyzacja
Pakiet PRO jest sprzedawany zewnętrznie na https://payhip.com/b/Ko0Ad (29 zł według ustawień strony). Generator jest darmowy, zakup dotyczy materiałów cyfrowych, nie funkcji generatora.

## Analityka
Linki do Payhip są oznaczone parametrami UTM. Kod ma przygotowane zdarzenia `pro_click` i `wycenakit_pro_click`, ale **nie ma jeszcze aktywnego narzędzia analitycznego**. Zdarzenia same nie tworzą raportów. Do podłączenia Cloudflare Web Analytics wymagany jest publiczny identyfikator strony wygenerowany w panelu właściciela.

## Wymagane przed aktywną promocją
Uzupełnij dane sprzedawcy, informacje o reklamacji, prawach konsumenta, zasadach dostarczenia treści cyfrowych i ochronie danych. Strona `informacje.html` jawnie oznacza brakujące dane. Nie publikuj fikcyjnych opinii ani wyników sprzedaży.

## Uwaga
Ceny szablonów są wyłącznie demonstracyjne. Generator nie wystawia faktur. Brak gwarancji sprzedaży ani indeksowania w wyszukiwarkach.
