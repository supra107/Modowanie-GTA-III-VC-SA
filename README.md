# Modowanie GTA III/VC/SA

## 1. Wstęp

Ten poradnik ma na celu zebranie wszystkich najważniejszych linków potrzebnych do zmodowania gier GTA bazujących na silniki RenderWare w miarę prosty oraz przejrzysty sposób.

Poradnik ten skupia się na wersjach gry z platformy Steam, zatem może być on nietrafny w przypadku wersji z Rockstar Games Social Club, czy też wersji pudełkowych.

## 2. Downgrade

Pierwszym etapem modowania jest zdowngradeowanie gier do wersji 1.0. Wymagane jest to, ponieważ wersje Steam nie są kompatybilne z wieloma modami które są tu zebrane. Do tego wersja Steam San Andreas ma wyciętą muzykę, także downgrade jest tu jak najbardziej wskazany.

Poniżej znajdziecie linki do odpowiednich downgrade'erów, oraz instrukcje jak je zastosować:

[Downgrade III](exe/gta3.exe?raw=true) - Zamień plik .exe w folderze instalacji

[Downgrade VC](exe/gta-vc.exe?raw=true) - Zamień plik .exe w folderze instalacji

[Downgrade SA](https://services.rockstarnexus.com/sadowngrade/latest.exe) - Uruchom, a następnie postępuj zgodnie ze wskazówkami, nie zaznaczaj opcjonalnych modów, ponieważ zainstalujemy je ręcznie, aby upewnić się, że instalujemy najnowszą wersję.

## 3. Modowanie

Na sam początek modowania potrzebujemy loadera skryptów ASI. Są to skrypty które głęboko modyfikują działanie gry, co pozwala na wprowadzanie różnych poprawek jak i funkcji.

Do III i Vice City potrzebny jest [Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader/releases/). Należy pobrać archiwum pod tytułem "Ultimate-ASI-Loader.zip".

Do San Andreas wymagany jest [Silent's ASI Loader](https://www.gtagarage.com/mods/show.php?id=21709).

Następnie należy utworzyć folder "scripts" w folderze instalacyjnym gry. To w nim należy umieścić wszystkie pliki. asi oraz .ini.

Dodatkowym, zalecanym krokiem jest zainstalowanie skryptu [Modloader](https://github.com/thelink2012/modloader/releases), pozwalającego na instalację modów takich jak samochody, broń, tekstury itp. bez modyfikowania plików gry.

Indywidualne mody należy umieszczać w pojedynczych folder znajdujących się w folderze "modloader".

Przydatna jest również [biblioteka CLEO](https://cleo.li/), pozwalająca na instalację skryptów modyfikujących działanie gry. Skrypty te można spokojnie instalować poprzez wyżej wymieniony Modloader.

### 3.1. Najważniejsze poprawki błędów, trzeba zainstalować

[[ASI] SilentPatch (III/VC/SA)](https://gtaforums.com/topic/669045-silentpatch/) - Najważniejsze poprawki błędów. Do III/VC należy pobrać również "DDraw Component"

[[ASI] Widescreen Fix (III/VC/SA)](https://thirteenag.github.io/wfp) - Poprawki interfejsu dla ekranów 16:9

[[ASI] Framerate Vigilante (III/VC/SA)](https://www.mixmods.com.br/2019/06/framerate-vigilante.html) - Unikanie błędów związanych ze zbyt wysokimi/niskimi klatkami na sekundę

[[ASI] RunDLL32.exe Fix (III/VC/SA)](https://www.mixmods.com.br/2016/02/rundll32exe-fix-corrigir-jogo-nao-abrindo.html) - Poprawka błędu związanego z plikiem RunDLL32.exe

[[ASI] NoDEP (III/VC/SA)](https://www.mixmods.com.br/2015/03/nodep-desativar-dep.html) - Poprawka błędu "Data Execution Prevention"

[Largeaddress Patch (II/VC/SA)](https://www.mixmods.com.br/2016/09/largeaddress-reconhecer-4-gb-ram.html) - Patch dla pliku .exe do obsługi większej ilości pamięci, wymagany w bardziej wymagających modach

### 3.2. Mody graficzne:

[[ASI] SkyGFX (III/VC/SA)](https://gtaforums.com/topic/750681-skygfx-ps2-xbox-and-mobile-graphics-for-pc/) - Efekty graficzne z wersji na PS2, Xbox, oraz Android

[[ASI] 2DFX (III/VC/SA)](https://thirteenag.github.io/p2dfx) - Polepszone pole widzenia oraz efekty w dali

[[ASI] SharpTrails (III/VC)](https://gtaforums.com/topic/819550-sharptrails/) - Efekty "Trails", czyli efekty rozmycia ruchu

[[ASI] ParticleEx (III/VC)](https://gtaforums.com/topic/913903-particleex/) - Poprawione efekty cząsteczkowe

[[ASI] Real Skybox (SA)](https://www.mixmods.com.br/2020/06/real-skybox-ceu-realista.html) - Realistycznie niebo i chmury

[[ASI] Real Linear Graphics (SA)](https://www.mixmods.com.br/2019/05/real-linear-graphics.html) - Realistyczne oświetlenie (wymagany [24H Timecyle](https://www.mixmods.com.br/2017/08/24h-timecycle-timecycdat-de-24-horas.html))

[[ASI] GraphicsTweaker (SA)](https://www.mixmods.com.br/2020/06/graphicstweaker-melhorar-graficos.html) - Poprawka kontrastu grafiki

[[ASI] SkyGrad (SA)](https://www.mixmods.com.br/2015/03/sky-gradient-fix-corrigir-linhas.html) - Polepszony gradient nieba

[[Modloader] RoSA + SRt3 + AI Upscale (SA)](https://www.mixmods.com.br/2020/04/rosa-srt3-ai-upscale-pack-texturas-hd.html) - Tekstury HD (wymagany patch Largeadress, ustawienie "StreamMemory = 1024" w MixSets oraz Load Whole Map)

[[ASI] Shadow Settings Extender (SA)](https://www.mixmods.com.br/2020/03/shadows-settings-extender.html) - Ulepszone cienie obiektów

### 3.3. Mniejsze poprawki błędów:

[[ASI] MixSets (SA)](https://www.mixmods.com.br/2019/08/mod-mixsets.html) - Duży zbiór wielu poprawek z możliwością konfiguracji

[[ASI] MixSets (VC)](https://www.mixmods.com.br/2019/02/VC-MixSets.html) - Wersja MixSets dla Vice City

[[ASI] Rosenberg's Audio Fix (VC)](https://www.gtagarage.com/mods/show.php?id=22234) - Przywraca dialogi Rosenberga przy wyjściu z więzienia

[[CLEO] Gangster Walk Fix (III/VC/SA)](https://www.mixmods.com.br/2019/02/gangster-walk-fix.html) - Poprawka animacji chodzenia z bronią NPCtów

[[Modloader] Animation Fix (SA)](https://www.mixmods.com.br/2017/10/animation-fix-corrigir-bugs-de-animacoes.html) - Poprawka wielu animacji postaci

### 3.4. Pozostałe mody:

[[ASI] GInput (III/VC/SA)](https://gtaforums.com/topic/562765-ginput/) - Usprawnienia dla graczy korzystających z pada PS/Xbox

[[ASI] SkyUI (SA)](https://gtaforums.com/topic/899738-skyui/) - Interfejs z PS2 dla PC

[[ASI] Mod Updater (III/VC/SA)](https://github.com/ThirteenAG/modupdater/releases) - Automatyczna aktualizacja modów

[[ASI] Windowed Mode (III/VC/SA)](https://github.com/ThirteenAG/III.VC.SA.WindowedMode/releases) - Możliwość grania w trybie okienkowym

[[ASI] Improved Fast Loader (SA)](https://gtaforums.com/topic/686694-improved-fast-loader/) - Przyśpieszone ładowanie gry

[[ASI] Mouse Wheel Radio Changer (III/VC)](https://www.gtagarage.com/mods/show.php?id=22492) - Zmiana radiostacji za pomocą kółka myszy jak w San Andreas, wymaga GInput

[[ASI] Classic Axis (III/VC)](https://gtaforums.com/topic/896122-classic-axis-visual-camera-improvements/) - Zachowanie kamery jak w San Andreas

[[ASI] Money Messages (III/VC)](https://www.gtagarage.com/mods/show.php?id=26361) - Informacje o zdobytych pieniądzach w stylu GTA 2

[[ASI] Destroyable AirTrain (III/VC)](https://www.gtagarage.com/mods/show.php?id=26526) - Możliwość zniszczenia samolotu na lotnisku

[[Modloader] Atmosphere Interface Pack (SA)](https://sharemods.com/afu7eik3tmzj/Atmosphere_Interface_Pack.7z.html) - Interfejs wysokiej rozdzielczości

[[ASI/Modloader/CLEO] PS2 Features to PC (SA)](https://gtaforums.com/topic/749193-san-andreas-ps2-features-to-pc/) - Zbiór modów przywracających elementy z wersji PS2 do PC

[[Modloader] Uncompressed SFX Pack (SA)](https://www.mixmods.com.br/2020/07/Uncompressed-SFX%20Pack.html) - Lepszej jakości efekty dźwiękowe

[[Modloader] Improved Default Armory (SA)](https://www.mixmods.com.br/2019/08/remastered-weapons-armas-melhoradas.html) - Polepszony wygląd standardowych broni

[[ASI] Load Whole Map (SA)](https://www.mixmods.com.br/2016/03/load-whole-map-carregar-todo-o-mapa.html) - Ładowanie całej mapy na raz zamiast oryginalnego ładowania "w locie"

[[ASI] ImprovedMove (SA)](https://www.mixmods.com.br/2019/10/Improved-Move.html) - Kontrola chodzenia w stylu GTA V

[[ASI] FullSprint (SA)](https://www.mixmods.com.br/2019/10/sprinthook.html) - Bieganie pełną prędkością poprzez przytrzymanie klawisza sprintu

[[CLEO] Faster Clothes Change (SA)](https://www.mixmods.com.br/2020/08/faster-clothes-changes-trocar-de-roupa.html) - Szybsza zmiana ubrań

[[ASI] Debug Menu (III/VC/SA)](https://www.mixmods.com.br/2020/03/shadows-settings-extender.html) - Menu debugowania z wieloma użytecznymi funkcjami

### 3.5. Dodatkowe źródła modów

[GTAForums](https://gtaforums.com/forum/311-mod-showroom/)

[GTAInside](https://gtaforums.com/forum/311-mod-showroom/)

[GTAGarage](https://www.gtagarage.com/mods/index.php)

[MixMods.com.br](https://translate.google.com/translate?hl=&sl=pt&tl=en&u=https%3A%2F%2Fwww.mixmods.com.br%2F) (Strona po portugalsku, załączony link z tłumaczem, większość linków pobierania działa jedynie [na nietłumaczonej wersji](https://www.mixmods.com.br/))
