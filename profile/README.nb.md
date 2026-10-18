<p align="center">
  <img src="./assets/hangrylabs_logo_horizontal.webp" alt="Hangry Labs: nyttige systemer uten mystikk" width="100%">
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <strong>Norsk bokmål</strong> ·
  <a href="README.pl.md">Polski</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.zh.md">简体中文</a> ·
  <a href="README.es.md">Español</a>
</p>

# 🧪 Hangry Labs

**Lokalførst KI og åpen programvare, pakket for å kjøre på maskinvare du kontrollerer. For menneskeheten og nuggetenes kraft.**

Hangry Labs bygger praktiske KI-systemer for egen drift, automatisering, dashbord, standarder og kreative verktøy. Vi pakker de vanskelige delene, lager nyttige grensesnitt og forklarer de reelle avveiningene, slik at avansert programvare blir enklere å kjøre, forstå, koble sammen og bevare.

Utforsk [programvarekatalogen til Hangry Labs](https://hangrylabs.app/nb/software) for produktveiledninger, ekte eksempler og installasjonshjelp.

For noen ganger vil du bare at tingen skal virke.  
Ikke påkalle tolv avhengighetsdemoner og ofre helgen til Python-miljøer.

---

## ⚡ Velg et verktøy og kom i gang

[Programvarekatalogen](https://hangrylabs.app/nb/software) viser programmene som allerede har fått det nye Hangry Labs-grensesnittet og oppdatert pakking. Der kan du sammenligne dem og høre ekte stemmeeksempler før du laster ned noe.

For de Docker-baserte taleverktøyene stiller hver installasjonsveiledning seks korte spørsmål om operativsystem, maskinvare, nedlastingsstørrelse, utgivelsesspor, bilderegister og nettverkstilgang. Deretter lager den én nøyaktig kommando og forklarer hvert trinn på klart språk. Svarene dine blir i nettleseren og sendes ikke til serveren.

Velg et prosjekt, åpne **Installasjonshjelp**, og la veiviseren håndtere sideoppdraget med å bygge kommandoen.

---

## 🌍 Hvorfor Hangry Labs finnes

Moderne KI-verktøy er kraftige, men mange er avhengige av vertsbaserte tjenester, skjult infrastruktur, modell-lenker som forsvinner, kompliserte oppsettsritualer eller eksterne kontoer.

Hangry Labs velger en mer uavhengig retning:

- kjør verktøy lokalt eller på infrastruktur du kontrollerer
- hold ledetekster, stemmer, transkripsjoner, dokumenter og bilder private
- tilby tydelige Docker-kommandoer og fornuftige standardvalg
- inkluder modeller og avhengigheter når det er praktisk
- tilby nettlesergrensesnitt for mennesker og dokumenterte API-er for programmer
- publiser ærlig veiledning om maskinvare, målinger og begrensninger
- bevar kreditering, lisenser og lenker til oppstrømsprosjekter

Den ideelle første opplevelsen bør føles slik:

```text
docker run ...
```

og så virker det.

Kanskje ikke alltid perfekt. Vi kjemper fortsatt mot avhengighetsbrannene. Men det er retningen.

---

## 🧰 Programmer

Det som begynte med lokale taleverktøy, har vokst til en bredere samling av programvare for KI, drift og skapende arbeid.

| Prosjekt | Område | Dette får du |
|---|---|---|
| [**KokoroTTS**](https://github.com/hangry-labs/kokoroTTS) | Rask lokal tale | 173 stemmer på 11 språk, fem uavhengig administrerte modellpakker, strømming, SSML-dialog, egne og OpenAI-kompatible API-er samt valgfrie MCP-verktøy. |
| [**MeloTTS**](https://github.com/hangry-labs/MeloTTS) | Flerspråklig tale | Åtte modeller på seks språk, modelladministrasjon i nettleseren, seks utdataformater, setningsstrømmet MP3 og PCM samt egne og OpenAI-kompatible API-er. |
| [**OmniVoiceTTS**](https://github.com/hangry-labs/OmniVoiceTTS) | Stemmelaboratorium | Tale på over 600 språk med stemmedesign, kloning fra mikrofon og referanse, gjenbrukbare profiler, SSML-H-dialog, strømming og OpenAI-kompatible API-er. |
| [**VoxCPMTTS**](https://github.com/hangry-labs/VoxCPMTTS) | Kreativ tale | Nano-vLLM-drevet generering på 30 språk, naturlig stemmedesign, referanse- og transkripsjonsstyrt kloning, gjenbrukbare profiler, progressiv strømming og HTTP-API-er. |
| [**Qwen3-ASR-STT**](https://github.com/hangry-labs/Qwen3-ASR-STT) | Tale til tekst | Lokal transkripsjon på 30 språk, mikrofonøkter i sanntid, tidsstempler og undertekster, OpenAI-kompatible klienter og valgfri MCP-transkripsjon av filer og nettadresser. |
| [**llama.nodrama**](https://github.com/hangry-labs/llama.nodrama) | LLM-drift | Et lett dashbord for llama.cpp-spor, køer, gjennomstrømming, KV-bufferoppførsel, tidslinjer for forespørsler og driftsdetaljene som skjules bak et lokalt LLM-endepunkt. |
| [**see-through**](https://github.com/hangry-labs/see-through) | Skaperverktøy | Privat, lokal lagdeling av animefigurer med eksport til lagdelt PSD, interaktive dybdeforhåndsvisninger, manuell rekkefølge, selektiv regenerering og gjenoppretting av kildedetaljer. |

Ulike motorer og verktøy har ulike styrker. Vi pakker dem etter det de faktisk er gode til, i stedet for å late som én modell skal løse alt.

Ulike nuggets for ulike katastrofer.

### Standarder og byggesteiner

| Prosjekt | Rolle | Nåværende fokus |
|---|---|---|
| [**Faster Qwen3-TTS**](https://github.com/hangry-labs/faster-qwen3-tts-studio) | Ytelseskjøretid | Qwen3-TTS-inferens i sanntid med og uten strømming, CUDA Graph-akselerasjon, en OpenAI-kompatibel server og en eksperimentell GGML-motor for CUDA og Apple Silicon. |
| [**SSML-H-spesifikasjonen**](https://github.com/hangry-labs/ssml-h-spec) | Talemarkering | Det normative hjemmet til den uavhengige Hangry Labs-utvidelsesprofilen for W3C SSML 1.1, inkludert dynamiske stemmedeklarasjoner og instruksjoner per replikk. |
| [**SSML-H Tools**](https://github.com/hangry-labs/ssml-h-tools) | Referansebibliotek | En motornøytral Python-parser, validator og et byggeverktøy som kompilerer SSML og SSML-H til uforanderlige synteseplaner. |

---

## 🛠️ Slik bygger vi

### Lokalt først og privat som standard

Dataene dine bør holde seg i nærheten. Hangry Labs-prosjekter skal kunne kjøre på maskinen eller serveren din uten å sende følsomme inndata til andres skytjenester.

### Ferdigpakket når det er praktisk

Komplette Docker-bilder kan inneholde modellfiler, kjøretidsavhengigheter og selve programmet. Når et fullstendig ferdigpakket bilde blir upraktisk, kan prosjektene tilby et mindre bilde med et stabilt, vedvarende datavolum.

Målet er pålitelighet, ikke å vinne konkurransen om det minste bildet. Et større bilde som fortsatt virker neste år, er ofte mer nyttig enn et lite bilde som går i stykker når en pakke endres eller en modell-lenke forsvinner.

### Åpne grensesnitt

Mennesker bør ha et tydelig nettlesergrensesnitt. Programmer og automatiseringer bør ha dokumenterte HTTP-API-er, nyttige statusendepunkter og forutsigbar oppførsel.

Der OpenAI-kompatible API-er gir mening, bruker vi dem som en praktisk grunnlinje for kompatibilitet samtidig som nyttige, produktspesifikke funksjoner forblir tilgjengelige.

### Ærlige begrensninger

Raske modeller kan ha smalere evner. Kraftige modeller kan kreve mer minne og tålmodighet. Målinger bør oppgi maskinvare og innstillinger, og kompatibilitetsveiledning bør være tydelig om hva som faktisk ble målt.

Ingen magisk røyk. Bare mildt dramatisk ingeniørvirkelighet.

### Respekt for oppstrømsarbeid

Mange Hangry Labs-prosjekter bygger på fremragende forskning og åpen programvare. Vi gjør kreditering og lisenser synlige, forklarer hva som kommer fra oppstrømsprosjektene, og dokumenterer hva Hangry Labs legger til innen pakking, grensesnitt, distribusjon og validering.

---

## 🚀 Langsiktig retning

Hangry Labs er fortsatt et laboratorium for nyttige sideoppdrag. Den bredere retningen omfatter lokalførst-verktøy for:

- KI-ledsagere og stemmegrensesnitt
- minne- og kunnskapssystemer
- dashbord for egen drift
- privat automatisering
- skaperverktøy
- spill- og strømmeverktøy
- modellservering og observerbarhet
- talemarkering og samvirkning
- rask, reproduserbar KI-inferens

Målet er en samling verktøy som folk kan kjøre, forstå, endre, koble sammen og bevare.

Ikke alt trenger å være et skyabonnement. Noen ting bør ganske enkelt tilhøre menneskene som bruker dem.

---

## 🧃 For menneskeheten og nuggetenes kraft

Vi bygger for mennesker som ønsker å kjøre ting selv.

For byggere.<br>
For skapere.<br>
For personvern.<br>
For rare eksperimenter.<br>
For de små rettelsene som blir til enorme prosjekter.<br>
For menneskeheten.

Og naturligvis for nuggetenes kraft.

Se de festede repositoriene nedenfor for prosjektene som får mest oppmerksomhet akkurat nå.
