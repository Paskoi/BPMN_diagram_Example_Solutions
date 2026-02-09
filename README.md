Zadanie 1: Proces Reklamacji

Klient składa reklamację. System musi sprawdzić, czy produkt jest jeszcze na gwarancji. Jeśli nie – system automatycznie odrzuca reklamację i wysyła maila. Jeśli tak – uruchamiają się dwie równoległe ścieżki:
- Magazyn sprawdza dostępność części zamiennych.
- Dział techniczny wstępnie ocenia usterkę na podstawie zdjęć.
Dopiero gdy obie te czynności się zakończą, Kierownik Serwisu podejmuje decyzję o naprawie lub wymianie. Wymiana wymaga dodatkowej akceptacji Księgowości, jeśli koszt przekracza 1000 zł.

Zadanie 2: Wniosek Urlopowy

Pracownik składa wniosek urlopowy. Musi on zostać zaakceptowany przez Przełożonego LUB przez HR. Jeżeli nikt nie podejmie decyzji w ciągu 48 godzin, wniosek jest automatycznie akceptowany. Po akceptacji system wysyła powiadomienie do pracownika i aktualizuje kalendarz zespołu.

Zadanie 3: Przetwarzanie Zamówienia

Klient składa zamówienie. System próbuje obciążyć kartę kredytową. Jeśli płatność się nie uda, system wysyła prośbę o aktualizację danych i pozwala na ponowną próbę. Jeśli płatność nie uda się 3 razy, zamówienie jest anulowane. Po udanej płatności następuje kompletowanie zamówienia. Jeśli w trakcie kompletowania okaże się, że towar jest uszkodzony, proces musi zostać przekierowany do ścieżki "Zwrot środków".

Zadanie 4: Onboarding Pracownika

Zatrudniono nowego programistę. Proces onboardingu składa się z dwóch głównych bloków.
- Przygotowanie sprzętu: Zamówienie laptopa, instalacja IDE, konfiguracja VPN.
- Dostępy: Utworzenie konta mailowego, dodanie do repozytorium kodu, nadanie karty wejściowej.
Dopiero gdy wszystko jest gotowe, wysyłany jest "Pakiet Powitalny".
Uwaga: Konfiguracja VPN wymaga danych z etapu tworzenia konta mailowego.

Zadanie 5: Ocena Ryzyka Kredytowego

System bankowy ocenia wniosek kredytowy. Najpierw pobierany jest raport z BIK.
- Jeżeli scoring jest < 300: Odrzucenie natychmiastowe.
- Jeżeli scoring jest > 500: Automatyczna akceptacja.
- Jeżeli scoring jest pomiędzy 300 a 500: Wniosek trafia do Analityka. Analityk może poprosić o dodatkowe dokumenty lub podjąć ostateczną decyzję.
