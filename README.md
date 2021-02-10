# Rozpoznanie domeny działania szkrzynkomatów z Big Picture EventStorming | #DomainExplorers

## Motywacja
Obsługa procesu odbioru paczek w skrzynkomatach. 

## Domena
- Paczka - przesyłka o zdefiniowanej długości, szerokości, wysokości oraz wagi.
- Skrzynkomat - urządzenie składające się ze skrytek różnej wielkości, która przechowuje paczki
- Skrytka - miejsce do przechowywania paczki o określonej długości, szerokości, wysokości oraz możliwości utrzymania ciężaru tej paczki
- Kurier - osoba umieszająca lub odbierająca paczkę w paczkomacie
- Nadawca - osoba zlecająca wysyłkę paczki
- Klient - osoba, który odbiera paczkę

## Big Picture EventStorming
- Event  - pomarańczowa karteczka, która określa zdarzenie biznesowe, której stan powinien być zapisany.
- HotSpot - różowa karteczka, która określa problem (wątpliwość), który trzeba w późniejszym procesie rozwiązać.

## Procesy do przeanalizowania
1. Odbiorca odbiera paczkę za pomocą desktopu w paczkomacie
2. Odbiorca odbiera paczkę za pomocą skanera QR
3. Odbiorca odbiera paczkę za pomocą aplikacji mobilnej
