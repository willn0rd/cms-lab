# MP1 – FastBike: firma, persony i mapa strony

## 1. Firma

| | |
|---|---|
| **Nazwa** | FastBike |
| **Branża** | Serwis i sprzedaż rowerów |
| **Grupa docelowa** | Osoby jeżdżące rekreacyjnie |
| **Propozycja wartości** | Szybka, przejrzysta i przewidywalna cenowo opieka nad rowerem |

### Oferta

- **Naprawa rowerów** – diagnostyka i usuwanie usterek
- **Sprzedaż części i akcesoriów** – m.in. oświetlenie, zabezpieczenia, bagażniki
- **Przeglądy sezonowe** – przygotowanie roweru na wiosnę i zimę

### Cele strony

1. Zwiększyć liczbę rezerwacji serwisowych składanych online.
2. Skrócić drogę klienta do zakupu akcesoriów i części.
3. Zbudować zaufanie przez jawny cennik i opinie klientów.

---

## 2. Persony

### Persona 1 – Jan, 35 lat (dojeżdża do pracy)

| | |
|---|---|
| **Urządzenie** | Smartfon |
| **Cel** | Szybko umówić serwis roweru |
| **Problem** | Nie wie, ile kosztuje naprawa |
| **Potrzeby** | Orientacyjny cennik, wolne terminy, prosty formularz do wypełnienia w kilka minut |
| **Obawy** | Nieprzewidziany koszt, długi czas oczekiwania, brak roweru na dojazdy |
| **CTA** | **„Umów serwis”** |

**Jak strona mu pomaga:** cennik usług widoczny na stronie „Serwis rowerów”, przycisk „Umów serwis” przyklejony na górze ekranu mobilnego, formularz rezerwacji z wyborem terminu, informacja o czasie realizacji.

### Persona 2 – Anna, 28 lat (rekreacyjnie, kupuje akcesoria)

| | |
|---|---|
| **Urządzenie** | Laptop |
| **Cel** | Kupić nowe oświetlenie rowerowe |
| **Problem** | Nie zna dostępnych modeli |
| **Potrzeby** | Filtrowanie i porównywanie produktów, opisy, zdjęcia, opinie, jasna cena i dostępność |
| **Obawy** | Zły dobór modelu, niezgodność z rowerem, koszty dostawy |
| **CTA** | **„Zobacz ofertę”** |

**Jak strona jej pomaga:** kategoria „Akcesoria”, filtry (typ, cena, zasilanie), porównywarka, poradnik na blogu „Jak wybrać oświetlenie rowerowe”.

---

## 3. Mapa strony

```text
Strona główna
├── O nas
├── Usługi
│   ├── Serwis rowerów
│   └── Przeglądy sezonowe
├── Sklep
│   ├── Akcesoria
│   └── Części
├── Blog
├── Kontakt
└── Polityka prywatności
```

### Rola poszczególnych podstron

| Podstrona | Cel | Główne CTA | Persona |
|---|---|---|---|
| Strona główna | Pokazać ofertę i kierować do kluczowych działań | Umów serwis / Zobacz ofertę | Jan, Anna |
| O nas | Zbudować zaufanie (zespół, doświadczenie, lokalizacja) | Skontaktuj się | Jan |
| Serwis rowerów | Cennik, zakres napraw, rezerwacja terminu | Umów serwis | Jan |
| Przeglądy sezonowe | Pakiety przeglądów i ich ceny | Umów przegląd | Jan |
| Akcesoria | Katalog z filtrami i porównaniem | Zobacz ofertę | Anna |
| Części | Katalog części z doborem do typu roweru | Dodaj do koszyka | Anna |
| Blog | Poradniki, SEO, pozyskiwanie ruchu | Zobacz powiązane produkty | Anna |
| Kontakt | Adres, mapa, godziny, telefon, formularz | Zadzwoń / Napisz | Jan |
| Polityka prywatności | Zgodność z RODO i regulacjami o cookies | – | Wszyscy |

---

## 4. Ścieżki użytkownika

**Jan (smartfon):**
Strona główna → „Umów serwis” → wybór rodzaju usługi i sprawdzenie ceny → wybór terminu → potwierdzenie rezerwacji.

**Anna (laptop):**
Strona główna → „Zobacz ofertę” → Sklep / Akcesoria → filtr „oświetlenie” → porównanie modeli → koszyk → płatność.

---

## 5. Dlaczego WordPress?

1. **Popularność i wsparcie** – według W3Techs WordPress jest najpopularniejszym systemem CMS na świecie, więc łatwo o dokumentację, społeczność i dostępnych specjalistów.
2. **Rozszerzalność** – darmowe motywy i wtyczki pozwalają dodać potrzebne funkcje bez pisania kodu, np. rezerwacje terminów, sklep (WooCommerce), SEO i formularze.
3. **Koszty** – dla małej firmy jest tańszy w starcie i utrzymaniu niż rozwiązania abonamentowe.
4. **Elastyczność** – większa swoboda niż w Shopify (szablony, wtyczki, hosting), a jednocześnie prostszy w obsłudze niż Drupal.
5. **Samodzielność właściciela** – edycja treści, cen i wpisów blogowych bez udziału programisty.

### Porównanie z alternatywami

| Kryterium | WordPress | Shopify | Drupal |
|---|---|---|---|
| Koszt startu | Niski | Średni (abonament) | Średni–wysoki |
| Elastyczność | Wysoka | Ograniczona do platformy | Bardzo wysoka |
| Łatwość obsługi | Wysoka | Wysoka | Niska |
| Sklep i rezerwacje | WooCommerce + wtyczki | Wbudowany sklep, rezerwacje przez aplikacje | Wymaga konfiguracji |
| Dobór do FastBike | **Najlepszy** | Dobry dla samego sklepu | Zbyt rozbudowany |

## 6. Użycie AI
- **Tekst** - Persony, Mapa strony, część tekstu wstawionego w stronach, generalne redagowanie tekstu
- **Technologiczne** - Poprawa pliku .yml, rozwiązanie problemu z bazą danych - każda strona oprócz głównej była przekierowana na localhost (zakładanie nowego codespace nie pomagało) 
- **Planowanie** - Używane do odbijania pomysłów