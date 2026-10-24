# Tarcza

Narzędzie na ladę hurtowni. Wklejam SMS klienta i dostaję szkic odpowiedzi, tabelę zamówienia (8 pól) i zdanie „co wisi”. Nic nie leci do klienta samo: zatwierdzam, poprawiam albo odrzucam.

Przy kasie nie ma czasu na „uprzejmie informuję”. Ma być szkic prawie do wysłania, w tonie tej osoby. Wysyłka idzie ręcznie — WhatsApp, SMS, telefon.

## Zasady

- Model nie wymyśla cen, stanów magazynowych, godzin, telefonów ani adresów. Jak nie ma tego w wątku: „—” albo „sprawdzę”.
- Zakaz korpo-fraz: „Szanowny Kliencie”, „Uprzejmie informuję”.
- Podpis tylko Rafał.
- Pytanie uzupełniające nie zrzuca na klienta roboty, którą operator policzy sam.

## Co jest w środku

Jeden ekran. Sprawa żyje w SQLite, nie w przeglądarce — drugi SMS tej samej osoby widzi wątek. Testy odpalam bez żywego modelu, na zaślepce.

Jest też workflow n8n z człowiekiem w pętli: wklejka → draft → zatwierdzenie.

## Stack

React, TypeScript, Express, SQLite, Gemini, Vitest, n8n

Własny projekt. Na spotkaniu odpalę i pokażę, bez slajdów.
