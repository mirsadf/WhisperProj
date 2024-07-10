# WhisperDesktop na Bosanskom

Ovo je modifikovana verzija projekta WhisperDesktop, prevedena i prilagođena za potrebe novinara [Radio Televizije Novi Pazar](https://rtvnp.rs). Zahvaljujemo se originalnom autoru, Const-me, na izvrsnom radu.

## Namjena Projekta

Projekat WhisperDesktop je namijenjen za prepoznavanje govora i pretvaranje istog u tekst. Ova verzija je prevedena na bosanski jezik i prilagođena za lakše korištenje od strane novinara.

## Upustvo za kompajliranje

1. Učitajte `WhisperProj.sln` u Visual Studio 2022.
2. Na solution-u u "Configuration Manager" promenite "Active solution configuration" na "Release" (obavezno).
3. Desnim tasterom kliknite na Solution i izaberite "Build Solution".
4. U `x64\Release` direktorijumu će se pojaviti kompajlirani fajlovi.

Potrebni fajlovi za rad su:
- `Whisper.dll`
- `WhisperDesktop.exe`

Ili mozete preuzeti [zip](https://github.com/mirsadf/WhisperProj/releases/download/v1.0.0/WhisperDesktop.zip) sa kompajliranim fajlovima.

### Preuzimanje Modela

Potrebno je preuzeti model V2 sa sledećeg linka: [ggml-large-v2.bin](https://huggingface.co/ggerganov/whisper.cpp/blob/main/ggml-large-v2.bin). Ovaj fajl sadrži pretrenirani model koji se koristi za prepoznavanje govora.
Model V3 nije kompatibilan sa ovom verzijom WhisperDesktop.

## Informacije o Autoru

Mirsad Fijuljanin, IT Administrator u [Radio Televiziji Novi Pazar](https://rtvnp.rs).

## Originalni Autor

Originalni projekat je kreirao Const-me i licenciran je pod Mozilla Public License 2.0.

## Licenca

Ovaj projekat je licenciran pod Mozilla Public License 2.0. Pogledajte LICENSE fajl za više detalja.
