# TellMyShop

**Prowadź sklep PrestaShop albo WooCommerce z czatu w Claude lub ChatGPT, zwykłymi słowami.**

TellMyShop to moduł do PrestaShop i wtyczka do WordPress i WooCommerce. Łączy sklep z czatem, którego już używasz. Piszesz, czego potrzebujesz („popraw opisy meta w kategorii Buty”, „dlaczego tego produktu nie ma w Google?”), czat czyta sklep, przygotowuje zmianę i pokazuje podgląd. Nic się nie zapisze bez twojej zgody, a każdą zmianę cofniesz.

[Strona](https://tellmyshop.com/pl?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Pobierz TellMyShop Free](https://tellmyshop.com/pl/darmowy-audyt?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Pomoc](https://tellmyshop.com/pl/docs?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Bezpieczeństwo](https://tellmyshop.com/pl/bezpieczenstwo?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Cennik](https://tellmyshop.com/pl/cennik?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [English](README.md)

## Co zrobisz z TellMyShop

- **Przegląd sklepu**: SEO produktów, kategorii i stron, błędy 404, brakujące tłumaczenia, dlaczego produkt albo strona nie pokazuje się w Google.
- **Treści**: opisy produktów i kategorii, tytuły i opisy meta, strony CMS i wpisy, opisy zdjęć, tłumaczenia.
- **Katalog**: produkty, kombinacje i warianty, kategorie, cechy i filtry, marki, ceny i promocje, stany.
- **Duże zmiany za jedną zgodą**: zmiana setek produktów według reguły (kategoria, marka, brak sprzedaży od 60 dni), szukaj i zamień w treściach, kilka kroków jako jeden pakiet. Duże prace idą w tle i cofasz je jednym krokiem.
- **Gotowe zadania**: przegląd sklepu, nowa kolekcja, produkty bez sprzedaży, wycofanie produktu, porządki w katalogu i inne, z panelu albo z czatu.
- **Feedy produktowe** dla Google, Meta, Ceneo i CSV, które odświeżają się same.
- **Motyw i moduły lub wtyczki**: drobne poprawki po włączeniu przełącznika na 24 godziny.
- **Raport tygodniowy** mailem, przy każdym punkcie gotowe zdanie do wklejenia w czat.

## Jak pilnujemy zmian

- Każdy zapis najpierw pokazuje podgląd i trafia do sklepu dopiero po twojej zgodzie.
- Każdą zmianę cofniesz; w historii widać, kto ją zatwierdził.
- Kopia bazy przed pierwszą zmianą dnia oraz kopie plików motywu i modułów.
- Ryzykowniejsze obszary (motyw, moduły lub wtyczki, serwis) są wyłączone, dopóki nie włączysz ich na określony czas.
- Hasła, klucze API, płatności, podatki i statusy zamówień są zawsze zablokowane.
- Dane klientów są niedostępne dla AI, dopóki sam nie włączysz dostępu.
- Godzinowe limity działań i zmian, które ustawiasz w panelu.

## Wymagania

| Platforma | Wersje |
|---|---|
| PrestaShop | 8.1+ i 9.x (PHP 8.1+); osobna paczka dla 1.7.8–8.2 (PHP 7.2–8.0) |
| WordPress | 6.5+ z PHP 7.4+, z WooCommerce 8.0+ albo bez |
| Czat | wystarczy konto Claude albo ChatGPT, także darmowe |

Moduł działa w twoim sklepie. Czat łączy się z nim bezpośrednio, bez pośrednika między sklepem a czatem.

## Wersje

- **TellMyShop Free**: bez limitu czasu. Czyta sklep i daje gotowe raporty (przegląd sklepu, SEO, błędy 404, widoczność produktów, sprzedaż bez danych klientów). Niczego nie zapisuje.
- **TellMyShop Pro**: jednorazowa licencja na domenę, ta sama dla PrestaShop i WordPress. Dochodzi zapis zmian po twojej zgodzie, cofanie, duże zmiany, feedy produktowe i Konsultant TellMyShop. 7-dniowa gwarancja zwrotu pieniędzy.

Jedna paczka dla obu: bez licencji Pro działa jak Free. Aktualne ceny: [tellmyshop.com/pl/cennik](https://tellmyshop.com/pl/cennik?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne).

## Jak zacząć

1. [Pobierz TellMyShop Free](https://tellmyshop.com/pl/darmowy-audyt?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) i zainstaluj jak każdy inny moduł albo wtyczkę.
2. Skopiuj adres sklepu dla czatu z panelu TellMyShop.
3. Dodaj go w Claude albo ChatGPT i kliknij **Zezwól** w oknie sklepu. Szczegóły (po angielsku): [docs/connect.md](docs/connect.md), po polsku w [pomocy](https://tellmyshop.com/pl/docs?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne).

## Co jest w tym repozytorium

Dokumentacja, lista zmian i miejsce na zgłoszenie błędu. Moduł i wtyczkę pobierasz z [tellmyshop.com](https://tellmyshop.com/pl?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne).

- [Lista zmian](CHANGELOG.md)
- [Zgłoś błąd](../../issues/new/choose) (nigdy nie wklejaj klucza licencji, haseł ani danych klientów)
- [Problemy z bezpieczeństwem](SECURITY.md)

---

TellMyShop nie jest powiązany z PrestaShop SA, WordPress, WooCommerce, Anthropic ani OpenAI. PrestaShop, WordPress, WooCommerce, Claude i ChatGPT to znaki towarowe ich właścicieli. Twórca: SEMownia, Polska.
