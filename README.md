# Rozpoznanie domeny działania skrzynkomatów z Big Picture EventStorming | #DomainExplorers

## Motywacja
Obsługa procesu odbioru paczek w skrzynkomacie. 

## Wiedza o działaniu biznesu
https://www.youtube.com/watch?v=LqIF_pGI3wk&feature=emb_logo

Paczka w skrzynkomacie dostępna jest do obioru w ciągu 48h
1. Klient odbiera paczkę za pomocą ekranu w skrzynkomacie. Wymagany jest numer telefonu oraz kod
2. Klient odbiera paczkę za pomocą skanera QR w skrzynkomacie. Z maila bądź aplikacji wyświetlić na telefonie kod QR. Nie każdy skrzynkomat ma skaner
3. Klient odbiera paczkę za pomocą aplikacji mobilnej. Musi mieć włączony GPS. Maksymalna odległość od skrzynkomatu to 15m. Jeżeli jest kilku klientów przy szkrzynkomacie i odbierają paczki. Wszystkie zlecenia otwarcia skrzynek się kolejkują nie otworzą się równlogle. Skrzynki co 5 sekund będą się otwierały w kolejności wysłania żądania otwarcia.
Informacja rząd i kolumna jest znana. W aplikacji wyświetla się układ szkynkomatu wiadomo po której stronie szukać skrytki.
4. Kurier skanuje paczkę następnie umieszcza ją w skrzynkomacie
*Każdy może odebrać paczkę co zna kod i numer telefonu.

Kod może być udostępniony przez SMS, email, lub w aplikacji mobilnej.

## Domena
- Paczka - przesyłka o zdefiniowanej długości, szerokości, wysokości oraz wagi.
- Skrzynkomat - urządzenie składające się z wielu skrytek różnej wielkości, która przechowuje paczki. Posiada swoją lokalizację.
- Skrytka - miejsce do przechowywania paczki o określonej długości, szerokości, wysokości oraz możliwości utrzymania ciężaru tej paczki
- Kurier - osoba umieszająca lub odbierająca paczkę w skrzynkomacie
- Nadawca - osoba zlecająca wysyłkę paczki w skrzynkomacie
- Klient - osoba, który odbiera paczkę w skrzynkomacie



## Model
### Legenda - Big Picture EventStorming
- Event  - pomarańczowa karteczka, która określa zdarzenie biznesowe, której stan powinien być zapisany.
- HotSpot - różowa karteczka, która określa problem (wątpliwość)

Projekt:
https://miro.com/app/board/o9J_lVkc4VY=/

Zrzut:
