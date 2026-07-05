---
id: klasyfikacja-priorytetyzacja-i-obsluga-bledow
title: System klasyfikacji, priorytetyzacji i obsługi błędów dostępności. Załącznik nr 4
description: Jednolity model klasyfikacji, priorytetyzacji i obsługi błędów dostępności cyfrowej w cyklu życia usług i produktów cyfrowych
sidebar_label: Klasyfikacja i obsługa błędów
sidebar_position: 4
keywords: [rozwiązanie systemowe, cykl życia TIK]
tags: [rozwiązanie systemowe, cykl życia TIK]
opracowanie: Paulina Wysakowska
data_zgloszenia: 16 czerwca 2026
data_aktualizacji: 16 czerwca 2026
wersja_robocza: true
---

**Załącznik nr 4 do Zalecenia w sprawie systemowego rozwiązywania problemów dostępności cyfrowej**

## 1. Cel

Zalecenie nadrzędne Systemowe rozwiązywanie problemów dostępności cyfrowej ustanawia zasadę, że każda wykryta lub zgłoszona niezgodność uruchamia proces naprawczy realizowany w ramach standardowych procesów wytwarzania i utrzymania systemów. Niniejszy załącznik dostarcza jednolity model, według którego niezgodności są klasyfikowane, priorytetyzowane, rejestrowane oraz raportowane.
Celem jest zapewnienie, że poziom krytyczności błędu, termin jego naprawy oraz sposób jego dokumentowania są ustalane w sposób powtarzalny i niezależny od osoby dokonującej oceny, a dane o stanie dostępności są porównywalne w czasie i między systemami.

## 2. Poziomy krytyczności błędów

Stosowany jest jednolity, trzystopniowy model krytyczności, spójny z klasyfikacją przyjętą w zaleceniu nadrzędnym. Poziom krytyczności wynika z wpływu błędu na możliwość skorzystania z usługi lub zrozumienia treści, a nie z kategorii treści, w której błąd wystąpił.

| Poziom | Definicja | Przykłady |
| :--- | :--- | :--- |
| Krytyczny | Uniemożliwia skorzystanie z usługi lub dostęp do treści przez część użytkowników. Brak skutecznej drogi alternatywnej. | Brak obsługi klawiaturą, pułapka klawiaturowa, brak etykiet w formularzu logowania lub wniosku, treść niedostępna dla technologii asystującej w kluczowym procesie. |
| Istotny | Znacznie utrudnia korzystanie z usługi lub zrozumienie treści, lecz istnieje trudniejsza droga alternatywna. | Błędy wpływające na nawigację, interakcję lub zrozumienie treści, niepoprawna kolejność fokusu, mylące lub zbędne komunikaty. |
| Niski | Nie wpływa na możliwość skorzystania z usługi ani na zrozumienie treści. | Drobne nieprawidłowości w kodzie niedostrzegalne dla użytkownika. |

Poziom krytyczności ustalany jest na podstawie wpływu błędu na użytkownika: czy uniemożliwia korzystanie z usługi lub dostęp do treści, znacznie je utrudnia, czy pozostaje bez wpływu.

Powiązanie błędu z konkretnym wymaganiem dostępności następuje przez odniesienie do kryteriów ujętych w Podstawie testowania zgodności. Klasyfikacja krytyczności jest niezależna od tego odniesienia: to samo wymaganie może w różnych kontekstach skutkować błędem o różnym poziomie krytyczności.

<!-- OTWARTA KWESTIA (liczba poziomów): na razie zachowano model trzystopniowy, zgodny z sekcją 3 zalecenia nadrzędnego. Docelowo preferowane jest rozszerzenie liczby poziomów: 4 poziomy sprawdzają się dobrze, 5 jest optymalne. Propozycja zostanie przygotowana po uzgodnieniu kierunku. -->
<!-- OTWARTA KWESTIA (umiejscowienie klasyfikacji): klasyfikacja i priorytety ujęte w sekcji 3 zalecenia nadrzędnego wydają się w nim nadmiarowe i powinny zostać przeniesione do niniejszego dokumentu. Na razie pozostawiono je w dokumencie nadrzędnym bez zmian. -->

## 3. Powiązanie z ryzykiem prawnym i użytkowym

Poziom krytyczności odzwierciedla jednocześnie ryzyko użytkowe (rzeczywiste wykluczenie części użytkowników z dostępu do usługi publicznej) oraz ryzyko prawne (niewykonanie obowiązków wynikających z przepisów o dostępności cyfrowej).

| Poziom | Ryzyko użytkowe | Ryzyko prawne |
| :--- | :--- | :--- |
| Krytyczny | Część użytkowników zostaje pozbawiona dostępu do usługi lub treści. | Najwyższe. Brak dostępu do kluczowej funkcji może stanowić naruszenie obowiązków ustawowych i podstawę żądania zapewnienia dostępności oraz skargi. |
| Istotny | Korzystanie z usługi jest znacznie utrudnione, choć możliwe. | Podwyższone. Utrwalanie błędu zwiększa ekspozycję na żądania i skargi. |
| Niski | Brak rzeczywistego wpływu na użytkownika. | Ograniczone. |

W przypadku błędu krytycznego, którego naprawa nie jest możliwa niezwłocznie, zapewnia się tymczasowy alternatywny sposób dostępu do usługi lub treści, zgodnie z obowiązkiem wynikającym z przepisów o dostępności cyfrowej, do czasu usunięcia niezgodności.

Błędy ujęte w deklaracji dostępności są powiązane z odpowiednim wpisem w rejestrze, posiadają przypisany plan naprawczy oraz termin usunięcia. Po naprawie treść deklaracji jest niezwłocznie aktualizowana, aby odzwierciedlała stan faktyczny.

## 4. Zasady nadawania terminów naprawy
Termin naprawy ustalany jest na podstawie poziomu krytyczności, nie wyłącznie złożoności technicznej naprawy ani kategorii treści. Im wyższe ryzyko użytkowe i prawne, tym krótszy maksymalny czas naprawy.

| Poziom | Ryzyko użytkowe | Ryzyko prawne |
| :--- | :--- | :--- |
| **Krytyczny** | Część użytkowników zostaje pozbawiona dostępu do usługi lub treści. | Najwyższe. Brak dostępu do kluczowej funkcji może stanowić naruszenie obowiązków ustawowych i podstawę żądania zapewnienia dostępności oraz skargi. |
| **Istotny** | Korzystanie z usługi jest znacznie utrudnione, choć możliwe. | Podwyższone. Utrwalanie błędu zwiększa ekspozycję na żądania i skargi. |
| **Niski** | Brak rzeczywistego wpływu na użytkownika. | Ograniczone. |

Konkretne wartości maksymalnych czasów naprawy określa podmiot, uwzględniając wpływ na użytkownika końcowego oraz posiadaną zdolność naprawczą. Dla napraw realizowanych przez wykonawców zewnętrznych czasy te są elementem umowy oraz uzgodnionego poziomu usług (SLA, ang. Service Level Agreement), zgodnie z Wzorcowymi zapisami w umowie serwisowej.

Zasady różnicowania terminów opierają się na pilności i poziomie ryzyka, nie zaś na rodzaju treści, w której wystąpił błąd. Ten sam typ niezgodności w usłudze kluczowej i w treści pobocznej skutkuje różnymi terminami naprawy ze względu na różny poziom krytyczności.

<!-- OTWARTA KWESTIA: czy w dokumencie podać konkretne, wiążące wartości maksymalnych czasów naprawy (np. dni robocze dla poziomu krytycznego), czy pozostawić je do określenia przez podmiot i w umowie/SLA, jak w sekcji 3 zalecenia nadrzędnego. Na razie podano jedynie wartości odniesienia opisowe. -->

## 5. Obsługa i kierowanie błędów do naprawy
Jeśli podmiot posiada rejestr błędów, wtedy błędy dostępności są obsługiwane w ramach tego samego procesu, co pozostałe błędy oprogramowania, bez tworzenia odrębnych ścieżek obsługi dla błędów dostępności.

Błąd, który może zostać usunięty zasobami własnymi podmiotu, jest naprawiany wewnętrznie. Jeżeli usunięcie błędu wymaga zmiany w oprogramowaniu utrzymywanym przez wykonawcę zewnętrznego, błąd jest przekazywany temu wykonawcy do naprawy na podstawie umowy. Rejestr umożliwia przypisanie każdego błędu do strony właściwej do jego naprawy oraz śledzenie statusu niezależnie od miejsca realizacji.

## 6. Rejestr błędów dostępności

<!-- Punkt opracowany na podstawie sekcji 3 zalecenia nadrzędnego (Priorytety i czasy naprawy, SLA): https://siec-dostepnosci-cyfrowej.github.io/sdc/docs/cykltik/systemowe-rozwiazywanie-problemow-dostepnosci-cyfrowej/systemowe-rozwiazywanie-problemow-dostepnosci-cyfrowej#3-priorytety-i-czasy-naprawy-sla -->
<!-- OTWARTA KWESTIA: czy, biorąc pod uwagę, że urząd sam nie wytwarza oprogramowania, sekcja 4 zalecenia nadrzędnego (Źródła identyfikacji problemów) jest aktualna i powinna obejmować testy manualne czy monitoring automatyczny? -->

Wszystkie błędy dostępności, niezależnie od źródła ich identyfikacji, są rejestrowane w jednym rejestrze błędów prowadzonym przez podmiot. Jeżeli podmiot nie prowadzi rejestru błędów oprogramowania, tworzy go na potrzeby błędów dostępności.

Formę tego rejestru określa on samodzielnie; może na przykład wykorzystać dedykowane oprogramowanie do śledzenia zgłoszeń lub wybrać inną formę dokumentacji zgodnie z przyjętym standardem pracy.

<!-- OTWARTA KWESTIA: czy potrzeba opis flow na potrzeby sytuacji, w której nie maja wcale rejestru błędów, czy to juz nadmiarowe? -->


Rejestr obejmuje błędy pochodzące z następujących źródeł:

* monitoring automatyczny,
* testy manualne,
* przeglądy i audyty,
* zgłoszenia użytkowników (w trybie żądania zapewnienia dostępności lub opinii),
* zgłoszenia pracowników,
* dane z deklaracji dostępności.

Pojedynczy wpis w rejestrze będów zawiera co najmniej:

- unikalny identyfikator zgłoszenia,
- datę samodzielnego wykrycia lub otrzymania zgłoszenia,
- pochodzenie zgłoszenia (na przykład test własny, monitoring automatyczny, zgłoszenie użytkownika, przegląd, dane z deklaracji dostępności),
- lokalizację umożliwiającą odnalezienie błędu (adres URL, nazwa widoku, ekranu, komponentu lub szablonu),
- krótki opis błędu,
- kroki reprodukcji,
- środowisko (przeglądarka, system, urządzenie, technologia asystująca),
- powiązane wymaganie dostępności (kryterium według Podstawy testowania zgodności),
- poziom krytyczności,
- zasięg (pojedynczy widok, komponent wielokrotnego użytku, usługa kluczowa),
- osobę lub zespół odpowiedzialny za naprawę,
- datę przekazania błędu wykonawcy zewnętrznemu lub wewnętrznemu działowi odpowiedzialnemu za naprawę,
- termin naprawy:
  - wynikający z SLA (umowy),
  - faktyczny,
- status obsługi błędu (według cyklu statusów określonego poniżej),
- sposób weryfikacji naprawy (na przykład ponowny test automatyczny lub manualny potwierdzający usunięcie błędu),
- datę udostępnienia naprawy użytkownikom końcowym,
- datę zamknięcia wpisu po potwierdzeniu usunięcia błędu,
- oznaczenie powiązania z deklaracją dostępności.

Wpis uznaje się za kompletny, gdy umożliwia odtworzenie błędu, jego jednoznaczną lokalizację oraz przypisanie odpowiedzialności i terminu. Niekompletne zgłoszenia są uzupełniane przed zakwalifikowaniem do naprawy.

Statusy wpisu (stanu błędu) odzwierciedlają obieg obsługi przyjęty przez podmiot oraz możliwości wykorzystywanego narzędzia. Przykładowy cykl obejmuje: nowe, w analizie, zakwalifikowane do naprawy, w naprawie, w weryfikacji, zamknięte, a także odrzucone (z udokumentowanym uzasadnieniem) oraz oczekujące (na przykład gdy naprawa zależy od wykonawcy zewnętrznego). 
Niezależnie od przyjętych statusów, zamknięcie wpisu następuje po potwierdzeniu poprawności naprawy oraz braku regresji w elementach, które działały poprawnie przed zmianą.


## 6. Raportowanie do kierownictwa

Dane z rejestru są podstawą okresowego raportowania do kierownictwa, które sprawuje nadzór nad funkcjonowaniem systemu zarządzania problemami dostępności. Raportowanie służy podejmowaniu decyzji o zasobach, budżecie oraz działaniach usprawniających, a nie wyłącznie sprawozdawczości.

Raport okresowy obejmuje co najmniej:

- liczbę otwartych błędów w podziale na poziomy krytyczności,
- trend długu dostępności (zmianę liczby otwartych błędów krytycznych w czasie),
- dotrzymanie terminów naprawy względem przyjętych zasad oraz SLA,
- błędy powtarzalne i systemowe (na przykład w szablonach lub komponentach wielokrotnego użytku),
- ryzyka prawne i użytkowe wynikające z otwartych błędów,
- rekomendacje działań (zasoby, budżet, działania zapobiegawcze).

Raportowanie odbywa się okresowo, w cyklu ustalonym przez podmiot (na przykład kwartalnie). Błędy krytyczne nieusunięte w wyznaczonym terminie podlegają niezwłocznej eskalacji do kierownictwa, niezależnie od cyklu raportowania.

## 7. Minimalne wymagania

Podmiot spełnia co najmniej:

- stosowanie jednolitego modelu krytyczności zgodnego z zaleceniem nadrzędnym,
- prowadzenie jednego rejestru błędów dostępności obejmującego wszystkie źródła,
- przypisywanie terminów naprawy według poziomu krytyczności,
- powiązanie błędów ujętych w deklaracji dostępności z wpisami w rejestrze,
- okresowe raportowanie stanu błędów do kierownictwa wraz ze ścieżką eskalacji błędów krytycznych.

## Uzasadnienie

W wielu podmiotach publicznych błędy dostępności są identyfikowane, lecz oceniane i obsługiwane niejednolicie: bez powtarzalnych kryteriów krytyczności, bez spójnych zasad nadawania terminów oraz bez jednego rejestru. Skutkuje to nieporównywalnością danych, utrwalaniem niezgodności o najwyższym ryzyku oraz brakiem informacji zarządczej.

Niniejszy załącznik wprowadza jednolity model klasyfikacji, priorytetyzacji i obsługi błędów obejmujący cały cykl życia usług i produktów cyfrowych. Powiązanie poziomu krytyczności z ryzykiem prawnym i użytkowym, jednoznaczne zasady nadawania terminów, jeden rejestr oraz raportowanie do kierownictwa pozwalają usuwać bariery w sposób uporządkowany i mierzalny, a dostępność czynią elementem bieżącego zarządzania jakością usług cyfrowych.


## Podstawy prawne

- [Ustawa z dnia 4 kwietnia 2019 r. o dostępności cyfrowej stron internetowych i aplikacji mobilnych podmiotów publicznych](https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU20190000848) (Dz.U. 2019 poz. 848 z późn. zm.).

## Źródła

- [Norma EN 301 549 (wersja w języku angielskim)](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf), Wymagania dotyczące dostępności produktów i usług ICT.
- [W3C Accessibility Guidelines Evaluation Methodology (WCAG-EM) 2.0](https://www.w3.org/TR/wcag-em-2/).
- [Podstawa testowania zgodności TIK z EN 301 549](../podstawy-testowania-zgodnosci/podstawa-testowania-zgodnosci.md).
- [Wzorcowa procedura testowa](../podstawy-testowania-zgodnosci/wzorcowa-procedura-testowa.md).
- [Model dojrzałości monitoringu](../podstawy-testowania-zgodnosci/model-dojrzalosci-monitoringu.md).

## Dokument nadrzędny

- [Systemowe rozwiązywanie problemów dostępności cyfrowej](./systemowe-rozwiazywanie-problemow.md).
