# HistoryChat

Czat z 24 postaciami historycznymi. Wybierasz Kopernika, Curie albo Teslę i pytasz. On nie ma „pamiętać z internetu”. Czyta swoje pliki i z tych kawałków składa odpowiedź. Jak w źródle cisza — ma się zamknąć, nie zmyślać życiorysu.

Jest też tryb jak w sądzie: jedna postać oskarża, druga broni, trzecia pyta. Chciałem zobaczyć, czy model da się utrzymać na smyczy, gdy temat jest ciekawy i łatwo mu odlecieć.

## Jak to działa

1. Lokalna baza `.txt` na postać (chunkowanie).
2. Embeddingi (`sentence-transformers`) + FAISS. Jak padnie embedder — dopasowanie słów.
3. Prompt: styl postaci + historia rozmowy + znalezione fragmenty.
4. Odpowiedź: OpenAI, a jak brak klucza — Gemini.
5. Opcjonalnie TTS i awatar.

Sam RAG nie potrzebuje klucza API. Klucz jest do tekstu odpowiedzi i głosu.

## Stack

React, TypeScript, Vite, Flask, sentence-transformers, FAISS, OpenAI, Gemini, pytest

Własny projekt. Na spotkaniu odpalę i pokażę.
