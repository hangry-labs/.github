<p align="center">
  <img src="./assets/hangrylabs_logo_horizontal.webp" alt="Hangry Labs: użyteczne systemy bez tajemnic" width="100%">
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.nb.md">Norsk bokmål</a> ·
  <strong>Polski</strong> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.zh.md">简体中文</a> ·
  <a href="README.es.md">Español</a>
</p>

# 🧪 Hangry Labs

**Lokalne AI i otwarte oprogramowanie, przygotowane do działania na sprzęcie pod Twoją kontrolą. Dla ludzkości i potęgi nuggetsów.**

Hangry Labs tworzy praktyczne systemy AI do samodzielnego hostowania, automatyzacje, panele, standardy i narzędzia kreatywne. Pakujemy trudne elementy, dostarczamy użyteczne interfejsy i uczciwie wyjaśniamy kompromisy, aby zaawansowane oprogramowanie łatwiej było uruchamiać, rozumieć, łączyć i zachowywać.

Odwiedź [katalog oprogramowania Hangry Labs](https://hangrylabs.app/pl/software), aby znaleźć przewodniki po produktach, rzeczywiste przykłady i pomoc w instalacji.

Bo czasami po prostu chcesz, żeby to działało.  
Bez przywoływania dwunastu demonów zależności i składania weekendu w ofierze środowiskom Pythona.

---

## ⚡ Wybierz narzędzie i zacznij działać

[Katalog oprogramowania](https://hangrylabs.app/pl/software) prezentuje aplikacje, które korzystają już z nowego interfejsu Hangry Labs i odświeżonego sposobu pakowania. Możesz je porównać i posłuchać rzeczywistych przykładów głosu przed pobraniem czegokolwiek.

Dla narzędzi głosowych opartych na Dockerze każdy przewodnik instalacyjny zadaje sześć krótkich pytań o system operacyjny, sprzęt, rozmiar pobierania, kanał wydań, rejestr obrazów i dostęp sieciowy. Następnie tworzy jedno dokładne polecenie i wyjaśnia każdy krok prostym językiem. Odpowiedzi pozostają w przeglądarce i nie są wysyłane na serwer.

Wybierz projekt, otwórz **Pomoc w instalacji** i pozwól kreatorowi zająć się poboczną misją budowania polecenia.

---

## 🌍 Dlaczego istnieje Hangry Labs

Nowoczesne narzędzia AI są potężne, ale wiele z nich zależy od usług zdalnych, ukrytej infrastruktury, znikających odnośników do modeli, skomplikowanych rytuałów konfiguracji lub zewnętrznych kont.

Hangry Labs wybiera bardziej niezależne podejście:

- uruchamiaj narzędzia lokalnie lub na infrastrukturze, którą kontrolujesz
- zachowuj prywatność poleceń, głosów, transkrypcji, dokumentów i obrazów
- korzystaj z jasnych poleceń Dockera i rozsądnych ustawień domyślnych
- otrzymuj modele i zależności w pakiecie, gdy jest to praktyczne
- używaj interfejsów przeglądarkowych i udokumentowanych API dla aplikacji
- poznawaj uczciwe wymagania sprzętowe, pomiary i ograniczenia
- zachowuj informacje o projektach źródłowych, licencjach i odnośnikach

Idealne pierwsze uruchomienie powinno wyglądać tak:

```text
docker run ...
```

i po prostu działać.

Może nie zawsze idealnie. Nadal walczymy z pożarami zależności. Ale właśnie w tym kierunku zmierzamy.

---

## 🧰 Aplikacje

To, co zaczęło się od lokalnych narzędzi głosowych, rozrosło się w szerszy zestaw oprogramowania do AI, zarządzania i pracy twórczej.

| Projekt | Obszar | Co oferuje |
|---|---|---|
| [**KokoroTTS**](https://github.com/hangry-labs/kokoroTTS) | Szybka lokalna mowa | 173 głosy w 11 językach, pięć niezależnie zarządzanych pakietów modeli, strumieniowanie, dialog SSML, natywne i zgodne z OpenAI API oraz opcjonalne narzędzia MCP. |
| [**MeloTTS**](https://github.com/hangry-labs/MeloTTS) | Mowa wielojęzyczna | Osiem modeli w sześciu językach, zarządzanie modelami w przeglądarce, sześć formatów wyjściowych, strumieniowanie MP3 i PCM zdanie po zdaniu oraz natywne i zgodne z OpenAI API. |
| [**OmniVoiceTTS**](https://github.com/hangry-labs/OmniVoiceTTS) | Laboratorium głosu | Mowa w ponad 600 językach, projektowanie głosu, klonowanie z mikrofonu i nagrania wzorcowego, profile wielokrotnego użytku, dialog SSML-H, strumieniowanie i API zgodne z OpenAI. |
| [**VoxCPMTTS**](https://github.com/hangry-labs/VoxCPMTTS) | Kreatywna mowa | Generowanie w 30 językach napędzane przez Nano-vLLM, naturalne projektowanie głosu, klonowanie na podstawie nagrania i transkrypcji, profile wielokrotnego użytku, progresywne strumieniowanie i API HTTP. |
| [**Qwen3-ASR-STT**](https://github.com/hangry-labs/Qwen3-ASR-STT) | Mowa na tekst | Lokalna transkrypcja w 30 językach, sesje mikrofonowe na żywo, znaczniki czasu i napisy, klienci zgodni z OpenAI oraz opcjonalna transkrypcja MCP plików i adresów URL. |
| [**llama.nodrama**](https://github.com/hangry-labs/llama.nodrama) | Obsługa LLM | Lekki panel dla slotów llama.cpp, kolejek, przepustowości, zachowania pamięci podręcznej KV, osi czasu żądań i szczegółów operacyjnych ukrytych za lokalnym punktem końcowym LLM. |
| [**see-through**](https://github.com/hangry-labs/see-through) | Narzędzia dla twórców | Prywatne, lokalne rozdzielanie postaci anime na warstwy z eksportem warstwowego PSD, interaktywnym podglądem głębi, ręcznym porządkowaniem, selektywną regeneracją i odzyskiwaniem szczegółów źródła. |

Różne silniki i narzędzia mają różne mocne strony. Pakujemy je zgodnie z tym, w czym naprawdę są dobre, zamiast udawać, że jeden model powinien rozwiązać wszystko.

Różne nuggetsy na różne katastrofy.

### Standardy i podstawowe komponenty

| Projekt | Rola | Aktualny kierunek |
|---|---|---|
| [**Faster Qwen3-TTS**](https://github.com/hangry-labs/faster-qwen3-tts-studio) | Wydajne środowisko uruchomieniowe | Strumieniowe i niestrumieniowe wnioskowanie Qwen3-TTS w czasie rzeczywistym z akceleracją CUDA Graph, serwerem zgodnym z OpenAI i eksperymentalnym silnikiem GGML dla CUDA oraz Apple Silicon. |
| [**Specyfikacja SSML-H**](https://github.com/hangry-labs/ssml-h-spec) | Znaczniki syntezy mowy | Normatywne źródło niezależnego profilu rozszerzeń Hangry Labs dla W3C SSML 1.1, obejmującego dynamiczne deklaracje głosów i instrukcje dla poszczególnych wypowiedzi. |
| [**SSML-H Tools**](https://github.com/hangry-labs/ssml-h-tools) | Biblioteka referencyjna | Niezależny od silnika parser, walidator i konstruktor w Pythonie, który kompiluje SSML i SSML-H do niezmiennych planów syntezy. |

---

## 🛠️ Jak budujemy

### Lokalnie i prywatnie od początku

Twoje dane powinny pozostawać blisko Ciebie. Projekty Hangry Labs mają działać na Twoim komputerze lub serwerze bez wysyłania poufnych danych do cudzej chmury.

### Gotowe obrazy, gdy ma to sens

Pełne obrazy Dockera mogą zawierać modele, zależności środowiska uruchomieniowego i samą aplikację. Gdy pełny obraz byłby niepraktyczny, projekt może dostarczyć mniejszy obraz wspierany przez stabilny, trwały wolumin danych.

Celem jest niezawodność, a nie wygranie konkursu na najmniejszy obraz. Większy obraz, który nadal działa za rok, jest często bardziej użyteczny niż mały obraz, który psuje się po zmianie pakietu lub zniknięciu odnośnika do modelu.

### Otwarte interfejsy

Ludzie powinni otrzymać przejrzysty interfejs przeglądarkowy. Aplikacje i automatyzacje powinny mieć udokumentowane API HTTP, użyteczne punkty końcowe stanu i przewidywalne zachowanie.

Tam, gdzie API zgodne z OpenAI mają sens, używamy ich jako praktycznej podstawy zgodności, zachowując jednocześnie przydatne funkcje właściwe dla danego produktu.

### Uczciwe ograniczenia

Szybkie modele mogą mieć węższe możliwości. Potężne modele mogą wymagać więcej pamięci i cierpliwości. Testy wydajności powinny podawać sprzęt i ustawienia, a wskazówki dotyczące zgodności jasno określać, co rzeczywiście zmierzono.

Bez magicznego dymu. Tylko lekko dramatyczna rzeczywistość inżynierii.

### Szacunek dla pracy projektów źródłowych

Wiele projektów Hangry Labs opiera się na znakomitych badaniach i otwartym oprogramowaniu. Zachowujemy widoczne informacje o autorach i licencjach, wyjaśniamy, co pochodzi z projektów źródłowych, oraz dokumentujemy wkład Hangry Labs w pakowanie, interfejsy, wdrażanie i walidację.

---

## 🚀 Kierunek długoterminowy

Hangry Labs nadal jest laboratorium przydatnych misji pobocznych. Szerszy kierunek obejmuje lokalne narzędzia do:

- towarzyszy AI i interfejsów głosowych
- systemów pamięci i wiedzy
- samodzielnie hostowanych paneli
- prywatnej automatyzacji
- narzędzi dla twórców
- narzędzi do gier i transmisji
- obsługi modeli i obserwowalności
- znaczników mowy i współdziałania
- szybkiego, powtarzalnego wnioskowania AI

Celem jest kolekcja narzędzi, które można uruchamiać, rozumieć, modyfikować, łączyć i zachowywać.

Nie wszystko musi być subskrypcją chmurową. Niektóre rzeczy powinny po prostu należeć do ludzi, którzy z nich korzystają.

---

## 🧃 Dla ludzkości i potęgi nuggetsów

Budujemy dla ludzi, którzy chcą uruchamiać wszystko samodzielnie.

Dla tych, którzy budują.<br>
Dla twórców.<br>
Dla prywatności.<br>
Dla dziwnych eksperymentów.<br>
Dla małych poprawek, które stają się ogromnymi projektami.<br>
Dla ludzkości.

I oczywiście dla potęgi nuggetsów.

Przypięte repozytoria poniżej pokazują projekty, którym poświęcamy obecnie najwięcej uwagi.
