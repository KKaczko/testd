# Mela — Character Bible

> Status dokumentu: `DRAFT`
> Wersja: `0.1.0`
> Status projektu postaci: `DRAFT`
> Status projektu wizualnego: `NOT LOCKED`
> Canonical path: `characters/mela/character-bible.md`

---

## 1. Cel i zakres

Ten dokument definiuje rolę, zachowanie, sposób komunikacji oraz proces
projektowania wizualnego Meli. Jest roboczym rejestrem decyzji potrzebnym do
przygotowania i zatwierdzenia projektu `Mela Master v1`.

Dokument nie zatwierdza jeszcze finalnego wyglądu postaci. Wszystkie dokładne
cechy wizualne pozostają `DRAFT`, `CANDIDATE` albo `OPEN`, dopóki nie zostaną
potwierdzone przez porównawcze rendery, test spójności i świadomą akceptację
człowieka.

Poza zakresem tego dokumentu pozostają:

- Piko Character Bible,
- World Bible i Style Bible,
- storyboardy i treść odcinków,
- wybór dostawcy generowania obrazów,
- automatyzacja produkcji,
- n8n, Remotion i JSON Schema.

## 2. Źródła prawdy i hierarchia autorytetu

Zasady produktu, grupy docelowej, edukacji, języka, tempa i ogólnego stylu
pochodzą z [Product Bible](../../docs/product_bible.md). Ten dokument odwołuje
się do nich i nie powiela ich pełnej treści.

Hierarchia autorytetu jest następująca:

1. Zasady bezpieczeństwa, edukacji i produktu z `AGENTS.md` oraz Product Bible.
2. Dla wyglądu postaci — zatwierdzony canonical visual reference pack Meli.
3. Dla roli, zachowania i rejestru decyzji — niniejszy Character Bible.
4. Canonical Prompt Template i negative constraints jako narzędzia pomocnicze.

Jeżeli opis tekstowy wyglądu będzie sprzeczny z zatwierdzonym reference packiem,
reference pack ma pierwszeństwo. Sprzeczny zapis w Character Bible należy wtedy
zaktualizować, zamiast próbować korygować wygląd samym promptem.

Canonical Prompt Template nigdy nie jest samodzielnym źródłem prawdy o wyglądzie
Meli.

## 3. Znaczenie statusów

| Status | Znaczenie w tym dokumencie |
|---|---|
| `LOCKED` | Świadomie zatwierdzone i kanoniczne. Zmiana wymaga jawnej decyzji człowieka. |
| `CANDIDATE` | Preferowany kierunek, który musi zostać sprawdzony. |
| `DRAFT` | Robocza hipoteza pomagająca przeprowadzić eksplorację. |
| `OPEN` | Decyzja nie została jeszcze podjęta. |

Status dokumentu `DRAFT` nie obniża statusu wpisów później oznaczonych jako
`LOCKED`, ale w wersji `0.1.0` nie istnieją jeszcze wizualne identity locks Meli.

Statusu cechy nie wolno podnosić tylko dlatego, że wystąpiła w promptach albo
dobrze wyglądała w pojedynczym renderze.

## 4. Rejestr decyzji

| Obszar | Aktualna decyzja | Status | Podstawa | Walidacja |
|---|---|---:|---|---|
| Rdzeń postaci | Mela jest małym, sympatycznym liskiem. | `CANDIDATE` | Product Bible i Project Context | Ocena roli oraz visual exploration |
| Funkcja w serialu | Reprezentuje ciekawość dziecka i współodkrywa świat; nie jest nauczycielką. | `CANDIDATE` | Product Bible | Przegląd scenariuszy i test zachowania |
| Podstawowe działania | Zauważa, pyta, obserwuje, próbuje i cieszy się z odkrycia. | `CANDIDATE` | Product Bible i Project Context | Pose/expression test |
| Sposób mówienia | Bardzo krótkie, naturalne wypowiedzi; charakterystyczne „Ooo!”. | `CANDIDATE` | Product Bible i Project Context | Próby dialogowe i odsłuch |
| Relacje | Mela działa po stronie dziecka; narrator objaśnia, a przyszły Piko demonstruje. | `DRAFT` | Role opisane w Product Bible | Test scen i późniejszy Piko Bible |
| Ogólny styl | Miękkie, stylizowane 2.5D/3D, zaokrąglone formy, matowe materiały, ograniczony detal. | `CANDIDATE` | Product Bible | Porównawcze rendery |
| Chustka | Obecność chustki jako wyróżnika Meli. | `CANDIDATE` | Zatwierdzony plan Mela Bible | Test sylwetki i detalu |
| Dokładna anatomia | Proporcje i kształty wszystkich części ciała. | `OPEN` | Brak renderów | Visual exploration i turnaround |
| Paleta | Funkcjonalna robocza rodzina kolorów, bez zatwierdzonych wartości. | `DRAFT` | Potrzeba eksploracji | Kontrolowany color test |
| Materiały | Miękkie, matowe i uproszczone; dokładny sposób przedstawienia futra jest nieustalony. | `DRAFT` | Kierunek produktu | Material test |
| Ekspresje i gesty | Spokojny podstawowy zestaw wspierający obserwację i pytanie. | `DRAFT` | Rola Meli | Expression/pose test |
| Canonical Prompt Template | Struktura pomocnicza zależna od reference packu. | `DRAFT` | Strategia spójności | Test generowania z referencjami |
| Identity locks wyglądu | Brak. | `OPEN` | Mela visual design nie jest zatwierdzony | Akceptacja Mela Master v1 |

---

## 5. Rola Meli w serialu — `CANDIDATE`

Mela jest punktem wejścia dziecka w odkrycie. Zauważa zjawisko, kieruje na nie
uwagę, zadaje proste pytanie, obserwuje odpowiedź świata i pokazuje spokojną
satysfakcję z poznania czegoś nowego.

Mela:

- modeluje ciekawość i uważną obserwację,
- może czegoś nie wiedzieć i bez skrępowania zapytać,
- może spróbować prostego działania i sprawdzić rezultat,
- pomaga dziecku skupić wzrok na najważniejszym obiekcie,
- może powtórzyć kluczowe słowo,
- daje dziecku przestrzeń na własną odpowiedź,
- nie podaje długich wyjaśnień,
- nie zastępuje narratora ani Piko.

Jej niewiedza nie jest przedstawiana jako wada ani źródło zawstydzenia. Błąd lub
niepewność prowadzą do spokojnego sprawdzenia, nie do ośmieszania postaci.

## 6. Osobowość — `CANDIDATE` / `DRAFT`

### 6.1. Rdzeń — `CANDIDATE`

- ciekawska,
- przyjazna,
- uważna,
- otwarta na próbowanie,
- szczerze zadowolona z małych odkryć.

### 6.2. Rozwinięcie robocze — `DRAFT`

- Jej ciekawość jest spokojna, a nie impulsywna.
- Potrafi przez chwilę patrzeć i słuchać bez dodatkowej aktywności.
- Nie musi reagować entuzjazmem na każdą rzecz.
- Łagodna niepewność jest dozwolona, ale nie powinna przechodzić w panikę.
- Humor wynika z naturalnej reakcji lub drobnego zaskoczenia, nie z chaosu,
  upadków ani zawstydzania.
- Mela jest wytrwała w prosty sposób: może poprosić „Jeszcze raz!”, ale nie
  forsuje działania i nie rywalizuje z dzieckiem.

## 7. Sposób zachowania — `CANDIDATE` / `DRAFT`

Domyślny przebieg reakcji Meli:

1. zauważa bodziec,
2. kieruje na niego wzrok,
3. zatrzymuje się na krótką obserwację,
4. pyta lub wskazuje,
5. słucha narratora albo obserwuje demonstrację,
6. próbuje jednego prostego działania,
7. reaguje na odkrycie,
8. wraca do spokojnego stanu.

Nie każda scena musi zawierać cały przebieg. W jednym ujęciu powinna dominować
jedna czytelna intencja.

Mela nie powinna:

- zachowywać się jak prowadząca lekcję,
- stale patrzeć w kamerę,
- przerywać narratorowi,
- wykonywać serii przypadkowych gestów,
- rozwiązywać skomplikowanych problemów poza możliwościami małego dziecka,
- używać slapsticku jako głównego sposobu budowania humoru,
- reagować krzykiem, gwałtownym skakaniem lub ciągłym machaniem ogonem.

## 8. Sposób mówienia

### 8.1. Zasady — `CANDIDATE`

- Mela zwykle mówi pojedynczym słowem albo bardzo krótką frazą.
- Jej wypowiedzi są konkretne i odnoszą się do tego, co widać lub słychać.
- Najbardziej charakterystyczną reakcją jest łagodne „Ooo!”.
- Mela częściej pyta, zauważa i powtarza niż wyjaśnia.
- Nie używa definicji, żargonu ani długich monologów.

Typowe funkcje wypowiedzi:

| Funkcja | Przykład |
|---|---|
| Zauważenie | „Ooo!” |
| Pytanie | „Co to?” |
| Wspólna uwaga | „Popatrz!” |
| Sprawdzenie miejsca | „Tutaj?” |
| Powtórzenie nazwy | „Chmura!” |
| Prośba o powtórkę | „Jeszcze raz!” |

### 8.2. Robocze ograniczenie długości — `DRAFT`

Preferowany zakres Meli to 1–5 słów, z możliwością użycia prostego zdania do
limitu określonego w Product Bible. Liczba nie jest jeszcze parametrem `LOCKED`;
ważniejsze są naturalność, zrozumiałość i rytm sceny.

### 8.3. Głos — `OPEN`

Nie ustalono jeszcze:

- wieku brzmiącego głosu,
- barwy i wysokości,
- aktorki głosowej albo technologii wykonania,
- dokładnego tempa, melodii zdań i poziomu ekspresji.

Głos będzie wymagał osobnej próby i akceptacji człowieka. Nie może być piskliwy,
krzykliwy ani przesadnie teatralny.

## 9. Relacja z dzieckiem — `DRAFT`

Mela jest współodkrywczynią, a nie dorosłym autorytetem. Powinna sprawiać
wrażenie, że patrzy na zjawisko razem z dzieckiem.

- Kieruje uwagę dziecka, ale nie wydaje serii poleceń.
- Może spojrzeć w stronę widza przy pytaniu lub wspólnym odkryciu.
- Po pytaniu zachowuje spokojną pauzę i nie uprzedza natychmiast odpowiedzi.
- Reakcją może potwierdzić odpowiedź, ale nie ocenia dziecka i nie zawstydza go.
- Nie używa nadmiernych pochwał niezwiązanych z działaniem.
- Jej gest i wzrok powinny jednoznacznie wskazywać przedmiot edukacyjny.

Dokładna częstotliwość kontaktu wzrokowego z kamerą pozostaje `OPEN` i zostanie
sprawdzona w pilocie.

## 10. Relacja z narratorem — `DRAFT`

Narrator jest głównym źródłem nazywania i wyjaśniania. Mela inicjuje odkrycie,
reaguje, słucha, pokazuje prostą czynność i może powtórzyć najważniejsze słowo.

Domyślna współpraca:

1. Mela zauważa lub pyta.
2. Narrator nazywa albo daje prostą wskazówkę.
3. Mela patrzy, sprawdza lub powtarza.
4. Narrator podaje krótką informację.
5. Mela pokazuje, że odkrycie zostało zrozumiane.

Narrator nie powinien ośmieszać niewiedzy Meli, mówić za nią ani stale opisywać
każdego jej ruchu.

## 11. Relacja z przyszłym Piko — `DRAFT`

Do czasu powstania Piko Character Bible relacja może być określona tylko na
poziomie funkcji:

- Mela przede wszystkim pyta i obserwuje.
- Piko przede wszystkim demonstruje i porównuje.
- Oboje pozostają spokojni, życzliwi i ciekawi wyniku.
- Piko nie jest nauczycielem oceniającym Melę.
- Mela nie jest chaotycznym przeciwieństwem „rozsądnego” Piko.
- Żadne z nich nie dominuje drugiego ani nie pełni roli komicznej ofiary.

Dokładna bliskość, historia znajomości, rytm dialogu, wspólne gesty oraz skala
wizualna pozostają `OPEN` do czasu zaprojektowania Piko.

---

## 12. Ogólny kierunek wizualny

### 12.1. Kierunek produktu — `CANDIDATE`

Mela powinna pasować do miękkiego, stylizowanego świata 2.5D/3D opisanego w
Product Bible:

- zaokrąglone i czytelne formy,
- matowe powierzchnie,
- miękkie światło,
- uproszczona geometria,
- ograniczony detal,
- wygląd niefotorealistyczny,
- czytelność jak w przestrzennej książce obrazkowej.

Te cechy opisują kierunek do przetestowania, a nie zatwierdzony model Meli.

### 12.2. Hipoteza startowa — `DRAFT`

Pierwsza runda eksploracji powinna sprawdzić zwartą, miękką sylwetkę o czytelnej
głowie, uszach i ogonie. Forma ma wyglądać przyjaźnie i umożliwiać spokojne,
jednoznaczne gesty bez nadmiernego uczłowieczania.

## 13. Sylwetka — `DRAFT` / `OPEN`

Kryteria sylwetki:

- rozpoznawalna jako Mela i jako lisek bez pomocy tekstu,
- czytelna w całości i w małej skali,
- odróżnialna w widoku przód, 3/4, profil i tył,
- nieagresywna i pozbawiona ostrych, drapieżnych akcentów,
- zdolna do wyraźnego pokazania kierunku wzroku i gestu,
- chustka zauważalna, lecz nie dominująca.

`OPEN` pozostają stopień antropomorfizacji, podstawowa postawa, sposób
poruszania się oraz dokładny kontur ciała.

## 14. Proporcje — `DRAFT` / `OPEN`

Proporcje powinny wspierać:

- dziecięcą łagodność bez skrajnej infantylizacji,
- stabilną pozę neutralną,
- możliwość patrzenia, wskazywania i manipulacji prostym obiektem,
- czytelność twarzy w typowym kadrze,
- spójność między widokami i pozami.

Do porównania w exploration trafiają proporcja głowy do ciała, długość tułowia,
długość kończyn, wielkość stóp lub tylnych łap oraz masa ogona. Nie ustala się
jeszcze wartości liczbowych ani liczby head-units.

## 15. Głowa — `DRAFT` / `OPEN`

Kierunek roboczy zakłada uproszczoną, miękką bryłę głowy, która zachowuje
czytelność w wielu kątach i nie zmienia objętości między ujęciami.

`OPEN`:

- dokładny obrys,
- szerokość i wysokość,
- relacja czaszki do pyszczka,
- obecność i forma policzków,
- ewentualne oznaczenia futra.

## 16. Pyszczek — `DRAFT` / `OPEN`

Hipotezą do sprawdzenia jest pyszczek krótki, miękki i wyraźnie liski, ale nie
spiczasty ani realistycznie drapieżny. Musi pozwalać na czytelne, subtelne
ułożenie ust w profilu i widoku 3/4.

`OPEN` pozostają długość, szerokość, kształt nosa, linia ust, rozwiązanie policzków
oraz sposób otwierania ust podczas mowy.

Widoczne ostre zęby nie są częścią kierunku. Jeżeli uzębienie okaże się potrzebne
przy mowie lub uśmiechu, wymaga osobnej decyzji i testu.

## 17. Oczy — `DRAFT` / `OPEN`

Oczy mają komunikować kierunek uwagi i łagodne emocje bez nadmiernej wielkości,
szklistego połysku ani hiperrealizmu.

Do przetestowania pozostają:

- wielkość i rozstaw,
- kształt otwarcia oka,
- obecność i wielkość tęczówki oraz źrenicy,
- sposób budowania brwi lub ich odpowiednika,
- ilość blików,
- rozwiązanie powiek.

Spojrzenie musi pozostawać stabilne: oba oczy powinny skupiać się na tym samym
punkcie, chyba że scena świadomie wymaga inaczej.

## 18. Uszy — `DRAFT` / `OPEN`

Uszy powinny wzmacniać rozpoznawalność liska i wspierać ekspresję jako ruch
drugorzędny.

`OPEN` pozostają wielkość, proporcje, zaokrąglenie końcówek, osadzenie, kolor
wnętrza oraz zakres ruchu. Uszy nie powinny stale drgać ani zmieniać kształtu
między ujęciami.

## 19. Przednie łapki — `DRAFT` / `OPEN`

Łapki muszą umożliwiać co najmniej:

- wskazanie obiektu lub kierunku,
- delikatne dotknięcie,
- przytrzymanie prostego, lekkiego przedmiotu,
- gest zaproszenia do wspólnego patrzenia.

Nie ustalono jeszcze stopnia podobieństwa do dłoni, liczby widocznych palców,
budowy poduszek ani sposobu chwytu. Należy unikać realistycznych ludzkich dłoni,
ostrych pazurów oraz zmiennej liczby palców między renderami.

## 20. Nogi i stopy — `DRAFT` / `OPEN`

Nogi powinny zapewniać stabilną, spokojną pozę i prosty chód bez wrażenia
niestabilności. Sylwetka musi pozostać czytelna również wtedy, gdy Mela siedzi,
pochyla się lub sięga po przedmiot.

`OPEN` pozostają długość, anatomia, sposób stawiania stóp lub tylnych łap,
sposób podparcia (np. stopochodny albo palcochodny) oraz zakres stylizacji.

## 21. Ogon — `DRAFT` / `OPEN`

Ogon jest ważnym elementem lisiej sylwetki i może subtelnie wspierać emocję oraz
równowagę pozy.

Powinien:

- zachowywać stałą długość, objętość i ewentualne oznaczenia,
- poruszać się spokojnie jako secondary motion,
- nie zasłaniać głównego obiektu ani gestu,
- nie działać jak stale aktywna, niezależna postać.

Dokładna długość, puszystość, kształt, końcówka i spoczynkowe ułożenie pozostają
`OPEN`.

## 22. Chustka

### 22.1. Obecność — `CANDIDATE`

Chustka jest preferowanym elementem rozpoznawczym Meli i ma występować we
wszystkich wariantach pierwszej rundy. Jej obecność nie jest jeszcze `LOCKED` i
może zostać odrzucona tylko przez świadomą decyzję po visual exploration.

### 22.2. Wymagania funkcjonalne — `DRAFT`

- czytelna w podstawowych widokach,
- nie zasłania twarzy ani kierunku gestu,
- zachowuje spójną konstrukcję i stronę wiązania,
- porusza się subtelnie i przewidywalnie,
- nie ma długich, chaotycznie latających końców,
- kontrastuje z futrem bez agresywnej intensywności.

### 22.3. Elementy `OPEN`

- kolor,
- materiał,
- wielkość,
- szerokość,
- sposób i strona wiązania,
- długość końców,
- obecność wzoru lub jego brak,
- zachowanie podczas ruchu.

W ramach testu spójności wybranego kandydata znikająca albo samoczynnie
zmieniająca się chustka jest błędem generowania. Nie oznacza to automatycznego
podniesienia samej cechy do `LOCKED`.

## 23. Robocza paleta kolorów — `DRAFT`

Poniższa paleta jest hipotezą startową do porównania, nie paletą kanoniczną:

| Funkcja koloru | Roboczy kierunek | Status |
|---|---|---:|
| Futro dominujące | Ciepły, przygaszony pomarańczowo-bursztynowy zakres | `DRAFT` |
| Jaśniejsze partie | Ciepły krem lub złamana biel | `DRAFT` |
| Nos, źrenice i ciemne detale | Głęboki, ciepły brąz zamiast czystej czerni | `DRAFT` |
| Chustka | Przygaszony chłodny turkus lub niebieskozielony akcent | `DRAFT` |
| Wnętrze uszu / subtelny akcent | Bardzo łagodny ciepły róż lub ton pochodny futra | `DRAFT` |

Należy sprawdzić co najmniej dwa alternatywne warianty tej rodziny. Dokładne
wartości sRGB, relacje jasności, nasycenie oraz rozmieszczenie oznaczeń pozostają
`OPEN` do chwili zatwierdzenia color sheetu w reference packu.

Paleta musi zachować czytelność twarzy i chustki w miękkim oświetleniu oraz nie
może konkurować z przyszłym obiektem edukacyjnym.

## 24. Materiały i renderowanie — `CANDIDATE` / `DRAFT`

### 24.1. Stały kierunek testu — `CANDIDATE`

- stylizowane miękkie 2.5D/3D,
- matowe lub bardzo delikatnie satynowe powierzchnie,
- uproszczony detal,
- miękkie, szerokie światło,
- brak fotorealizmu i kinowej złożoności materiałów.

### 24.2. Warianty do porównania — `DRAFT`

1. bardzo delikatna, krótka powierzchnia futra bez pojedynczych włosów,
2. miękki wygląd przypominający filc lub welur,
3. gładka, ilustracyjna powierzchnia z minimalną sugestią futra.

Chustka powinna być odczytywana jako miękka tkanina poprzez duże, proste fałdy,
bez mikrowzoru i ostrego połysku.

`OPEN` pozostają technika wykonania, renderer, dokładna szorstkość, sposób
modelowania futra, poziom subsurface scattering i parametry światła. Te wartości
nie będą definiowane przed wyborem kandydata wizualnego i powstaniem Style Bible.

---

## 25. Zestaw podstawowych ekspresji — `DRAFT`

| Ekspresja | Funkcja | Kierunek wykonania |
|---|---|---|
| Neutralna, spokojna | Stan bazowy i punkt odniesienia | Rozluźniona twarz i ciało, skupione spojrzenie |
| Ciekawość | Zauważenie obiektu | Kierunek wzroku, lekki skłon głowy, mała zmiana uszu |
| Pytanie / łagodna niepewność | „Co to?”, „Tutaj?” | Czytelne spojrzenie i subtelna asymetria pozy, bez bezradności |
| Skupiona obserwacja | Oglądanie zmiany lub demonstracji | Więcej bezruchu, wzrok na obiekcie, zamknięta lub neutralna buzia |
| Łagodne „Ooo!” | Małe zaskoczenie i odkrycie | Niewielkie otwarcie ust i oczu, bez gwałtownego odchylenia |
| Spokojna radość | Potwierdzenie odkrycia | Delikatny uśmiech i otwarta postawa, bez skakania |

Expression sheet powinien pokazywać te ekspresje przy niezmienionej geometrii
głowy, pyszczka, oczu i uszu. Ekstremalny strach, wściekłość, krzyk i przesadna
euforia nie należą do podstawowego zestawu.

Dokładny zakres ruchu oczu, powiek, ust i uszu pozostaje `OPEN` do testu riggu lub
kontrolowanych wariantów renderów.

## 26. Język ciała — `DRAFT`

- Wzrok prowadzi gest: Mela najpierw patrzy, potem obraca głowę lub ciało, a na
  końcu wskazuje.
- Postawa powinna mieć jedną dominującą intencję.
- Kontakt wzrokowy z widzem jest używany celowo przy pytaniu lub zaproszeniu do
  wspólnej uwagi.
- Przy słuchaniu Mela może pozostać prawie nieruchoma.
- Ogon i uszy wspierają emocję subtelnie, z niewielkim opóźnieniem.
- Gest kończy się czytelną pozą, którą można utrzymać podczas pauzy dla dziecka.
- Radość z odkrycia jest widoczna, ale nie przejmuje całego kadru.

Unikać:

- stałego kołysania i podskakiwania,
- jednoczesnego machania łapkami, uszami i ogonem,
- gwałtownego naruszania przestrzeni kamery,
- póz agresywnych, dominujących lub teatralnie bohaterskich,
- nadmiernego pozowania niezwiązanego z edukacyjnym punktem uwagi.

## 27. Zasady animacji — `DRAFT`

1. Jedna główna akcja lub intencja w danym momencie.
2. Czytelna antycypacja może wystąpić, lecz ma być subtelna.
3. Ruch zaczyna się i kończy spokojnie; bez gwałtownych snapów.
4. Po ważnym geście lub pytaniu należy utrzymać pozę wystarczająco długo, by
   dziecko mogło ją odczytać.
5. Idle obejmuje najwyżej subtelny oddech, rzadkie mrugnięcie i minimalny ruch
   uszu lub ogona.
6. Secondary motion chustki, uszu i ogona nie może konkurować z akcją główną.
7. Proporcje, objętości, liczba elementów anatomicznych i konstrukcja chustki
   pozostają stałe w całym ruchu.
8. Squash and stretch, jeśli zostanie użyty, ma być niewielki i wymaga testu.
9. Mela nie wykonuje ciągłych podskoków, obrotów, biegu w miejscu ani serii
   kreskówkowych reakcji.
10. Dokładne timing charts i parametry riggu pozostają `OPEN` do etapu animacji
    testowej.

---

## 28. Identity locks

### 28.1. Aktualny stan

**Brak wizualnych identity locks Meli.**

Żaden kształt, kolor, materiał, proporcja ani detal chustki opisany w tej wersji
nie jest `LOCKED`.

`LOCKED` są zasady procesu:

- finalny wygląd wymaga jawnej akceptacji człowieka,
- pojedynczy render nie może stać się wzorcem kanonicznym,
- zatwierdzony reference pack ma pierwszeństwo nad promptem tekstowym,
- cecha `OPEN`, `DRAFT` lub `CANDIDATE` nie może zostać podniesiona automatycznie.

### 28.2. Docelowy rejestr po akceptacji Mela Master v1

Po zatwierdzeniu należy uzupełnić identity locks co najmniej o:

- zatwierdzoną sylwetkę i proporcje,
- budowę głowy, pyszczka, oczu i uszu,
- budowę łap, nóg i ogona,
- rozmieszczenie wszystkich oznaczeń,
- dokładną paletę sRGB,
- konstrukcję i kolor chustki,
- materiały,
- skalę wewnętrzną,
- wersję canonical reference packu.

Każdy lock musi wskazywać wizualną referencję i zapis akceptacji.

## 29. Niedozwolony character drift

Poniższe zjawiska są błędem w obrębie wybranego kandydata lub późniejszego
Mela Master:

- zmiana gatunku albo utrata czytelności liska,
- samoczynna zmiana proporcji między ujęciami,
- zmiana kształtu głowy, pyszczka, oczu lub uszu bez celowej eksploracji,
- dodatkowe lub brakujące kończyny, palce, uszy albo ogony,
- ludzkie, realistyczne dłonie lub widoczne ostre pazury,
- niestabilny kierunek spojrzenia lub oczy skupione na różnych punktach,
- zmiana długości, objętości albo oznaczeń ogona,
- znikanie, pojawianie się lub przebudowa chustki w obrębie jednego wariantu,
- losowa zmiana palety, materiałów lub rozkładu umaszczenia,
- dodatkowe ubrania, biżuteria, fryzura, makijaż lub przypadkowe akcesoria,
- fotorealistyczne futro, drapieżna anatomia, widoczne ostre zęby,
- plastikowy połysk, neonowa kolorystyka lub nadmiar mikrotekstur,
- agresywna, przerażająca albo skrajnie hiperaktywna ekspresja,
- przesadna infantylizacja, np. oczy dominujące całą twarz,
- zmiana postaci w efektowne ujęcie kinowe kosztem czytelności i spójności.

Odmienny wariant cechy oznaczonej `OPEN` nie jest sam w sobie driftem, jeśli jest
świadomie testowany, opisany jako osobny kandydat i nie zostaje zmieszany z
innymi wariantami w jednym zestawie.

## 30. Canonical Prompt Template — `DRAFT`

Szablon ma porządkować generowanie i zawsze działać razem z wizualnymi
referencjami, gdy tylko takie referencje istnieją. Pola to zmienne, nie zgoda na
improwizowanie wyglądu.

```text
[REFERENCE AUTHORITY]
Use the attached Mela canonical visual reference pack as the primary authority
for character appearance.
Reference pack version: <VERSION>
Reference pack status: <CANDIDATE | LOCKED>
Visual candidate ID: <CANDIDATE_ID>
Do not reinterpret or redesign identity features shown in the references.

[CHARACTER IDENTITY]
Mela is a small, friendly fox and a calm child-perspective co-discoverer.
Use only identity details explicitly approved for <CANDIDATE_ID>.
Scarf status and approved construction: <SCARF_DECISION>

[ACTION AND EXPRESSION]
Primary action: <ONE_PRIMARY_ACTION>
Expression: <APPROVED_EXPRESSION>
Gaze target: <GAZE_TARGET>
Body-language intention: <ONE_CLEAR_INTENTION>

[SCENE VARIABLES]
Educational point of attention: <PRIMARY_OBJECT>
Environment: <ENVIRONMENT>
Camera and framing: <CAMERA>
Lighting: <SOFT_LIGHTING_SETUP>

[STYLE]
Soft stylized 2.5D/3D children's picture-book look, rounded readable forms,
matte simplified materials, soft lighting, limited texture detail,
non-photorealistic, calm visual hierarchy.

[CONSISTENCY REQUIREMENTS]
Preserve the reference silhouette, proportions, anatomy, facial construction,
eye and ear shapes, tail construction, markings, palette, materials and scarf.
Keep one primary action and one primary point of attention.

[OUTPUT PURPOSE]
<EXPLORATION | REFERENCE_SHEET | CONSISTENCY_TEST | SCENE_ASSET>
```

Przed powstaniem reference packu pola dotyczące wyglądu muszą wskazywać jawnie
oznaczony `CANDIDATE`; nie wolno wypełniać ich niezatwierdzonymi szczegółami i
przedstawiać wyniku jako kanoniczny.

## 31. Negative constraints — `DRAFT`

### 31.1. Guardraile produktu, stosowane we wszystkich rundach

```text
no photorealistic fox, no predatory anatomy, no threatening gaze,
no sharp visible teeth, no sharp claws, no horror, no aggression,
no screaming, no panic, no extreme cartoon reaction, no slapstick pose,
no neon colors, no high-gloss plastic, no dense micro-detail,
no busy patterns, no dramatic cinematic distortion, no visual clutter,
no text, logo or watermark
```

### 31.2. Ochrona tożsamości, stosowana po wyborze kandydata

```text
no redesign of the attached character, no proportion changes,
no face-shape changes, no eye or ear changes, no anatomy inconsistency,
no extra or missing limbs, digits, ears or tails, no human hands,
no marking or palette changes, no tail-length changes,
no scarf removal or redesign, no extra clothes or accessories,
no material-style changes, no inconsistent gaze
```

Negative constraints nie mogą zastępować reference packu ani pełnić funkcji
listy cech kanonicznych. Ograniczenia dotyczące konkretnej tożsamości należy
stosować dopiero do jasno wskazanego kandydata.

---

## 32. Wymagany canonical visual reference pack

Reference pack najpierw otrzymuje status `CANDIDATE`. Może zostać oznaczony
`LOCKED — Mela Master v1` dopiero po przejściu testu spójności i jawnej
akceptacji.

Pack powinien znajdować się pod `characters/mela/references/` i zawierać:

### 32.1. Neutral hero render

- cała postać w widoku 3/4,
- neutralna, spokojna ekspresja,
- neutralne tło i miękkie oświetlenie,
- brak rekwizytów zasłaniających sylwetkę.

### 32.2. Turnaround

- przód,
- 3/4,
- lewy lub prawy profil,
- tył,
- ta sama neutralna poza, ekspresja, skala, światło i konstrukcja.

Widoki powinny minimalizować zniekształcenie perspektywiczne i pozwalać
porównać objętości, oznaczenia oraz konstrukcję chustki.

### 32.3. Expression sheet

Co najmniej sześć ekspresji z sekcji 25, pokazanych przy niezmienionej tożsamości
i porównywalnym kącie kamery.

### 32.4. Pose sheet

Co najmniej:

- neutralne stanie lub siedzenie,
- obserwowanie,
- słuchanie,
- wskazywanie,
- sięganie i trzymanie prostego obiektu,
- spokojna radość z odkrycia.

### 32.5. Scale and proportion sheet

- wewnętrzna siatka proporcji w head-units,
- linia podłoża i stała wysokość postaci,
- porównanie pozy neutralnej i siedzącej,
- bez wymyślania skali względem Piko lub niezatwierdzonego świata.

### 32.6. Color sheet

- próbki wszystkich zatwierdzonych kolorów,
- wartości sRGB w zapisie HEX i RGB,
- przypisanie koloru do obszaru postaci,
- neutralne oświetlenie referencyjne,
- rozróżnienie koloru materiału od efektu światła i cienia.

### 32.7. Material and detail sheet

- sposób przedstawienia futra lub powierzchni,
- nos, oczy, wnętrza uszu i łapki,
- przód i tył chustki,
- sposób wiązania oraz dopuszczalny zakres fałd,
- zbliżenia wystarczające do odtworzenia detalu bez dodawania nowych cech.

### 32.8. Metadane i akceptacja

- nazwa `Mela Master`,
- wersja packu,
- status,
- data akceptacji,
- osoba zatwierdzająca,
- identyfikatory plików uznanych za kanoniczne,
- informacja o narzędziu i ustawieniach, jeśli jest dostępna i pomaga w
  reprodukcji; metadane generowania nie stanowią części tożsamości postaci.

## 33. Procedura visual exploration — `DRAFT`

### Etap 0 — brief kontrolny

1. Zamrozić na czas rundy wymagania produktu i aktualny rejestr statusów.
2. Ustalić wspólną neutralną pozę, kadr, tło i oświetlenie.
3. Nadać każdemu wariantowi trwały identyfikator.
4. Zmieniać tylko opisane osie projektu.
5. Oceniać projekt postaci, nie atrakcyjność przypadkowej scenografii.

### Etap 1 — eksploracja sylwetki

Przygotować sześć prostych wariantów bez finalnej palety. Kontrolowanie badać:

- stopień antropomorfizacji i podstawową postawę,
- proporcję głowy do ciała,
- długość kończyn,
- masę i ułożenie ogona,
- czytelność głowy, uszu i pyszczka,
- obecność i widoczność chustki,
- możliwość wskazywania oraz trzymania obiektu.

Odrzucić warianty nieczytelne w miniaturze, niepokojące, zbyt realistyczne albo
uniemożliwiające podstawowe działania edukacyjne.

### Etap 2 — shortlista

Wybrać trzy rodziny kandydatów. Dla każdej przygotować porównywalny neutralny
render w widoku przód, 3/4 i profil.

Każdą rodzinę ocenić w skali 1–5 pod kątem:

- rozpoznawalności,
- sympatyczności,
- spokoju,
- czytelności sylwetki,
- możliwości wykonania gestów,
- zgodności z kierunkiem 2.5D/3D,
- potencjału utrzymania spójności między widokami.

### Etap 3 — kontrolowane warianty detalu

Dla kandydatów pozostających w grze testować osobno:

1. pyszczek,
2. oczy,
3. uszy,
4. przednie łapki,
5. nogi i stopy,
6. ogon,
7. konstrukcję chustki.

Nie zmieniać kilku obszarów naraz, jeżeli uniemożliwiłoby to wskazanie przyczyny
lepszego lub gorszego wyniku. Odrzucone warianty zachować wraz z krótkim powodem
odrzucenia; nie uzyskują statusu `DEPRECATED`, dopóki nie były wcześniej
kanoniczne.

### Etap 4 — kolor i materiał

Wybrać dwóch finalistów i dla każdego przygotować porównywalne warianty palety
oraz powierzchni. Zachować identyczne oświetlenie i zarządzanie kolorem.

Sprawdzić:

- kontrast oczu, pyszczka i chustki,
- czytelność oznaczeń,
- zachowanie koloru w jasnym i łagodnie zacienionym ujęciu,
- brak agresywnego nasycenia,
- brak fotorealistycznego detalu,
- czy postać nie konkuruje z prostym obiektem edukacyjnym.

### Etap 5 — Mela Master Candidate

Wybrać jeden kierunek i oznaczyć go `CANDIDATE — Mela Master`. Przygotować jego
prowizoryczny reference pack. Pojedynczy hero render nie wystarcza do zmiany
statusu na `LOCKED`.

### Etap 6 — reference pack i test spójności

Uzupełnić wymagane arkusze, a następnie wykonać test opisany w sekcji 34.

### Etap 7 — decyzja człowieka

Pozytywny test umożliwia, ale nie wymusza akceptacji. Osoba zatwierdzająca może:

- zaakceptować `Mela Master v1`,
- zlecić kontrolowaną korektę,
- wrócić do wcześniejszego kandydata,
- pozostawić projekt jako `CANDIDATE`.

## 34. Consistency test

Test przeprowadza się z użyciem prowizorycznego reference packu. Arkusze będące
częścią packu nie liczą się do minimum niezależnych wyników testowych.

### 34.1. Minimalny zestaw 12 wyników

1. trzy niezależne reprodukcje neutralnego widoku 3/4,
2. cztery kontrolne widoki: przód, profil, tył i przeciwne 3/4,
3. trzy ekspresje/czynności: ciekawa obserwacja, pytanie/słuchanie oraz łagodne
   „Ooo!” ze spokojną radością,
4. dwa gesty funkcjonalne: wskazywanie oraz sięganie/trzymanie prostego obiektu.

Tło i światło powinny pozostać neutralne. Prosty obiekt testowy może wystąpić
tylko wtedy, gdy jest potrzebny do oceny gestu.

### 34.2. Twarde kontrole — wymagane 12/12

- ta sama rozpoznawalna postać,
- zgodny gatunek i sylwetka kandydata,
- stałe proporcje i objętości,
- poprawna liczba oraz konstrukcja części ciała,
- zgodna głowa, twarz, oczy i uszy,
- stabilny ogon i oznaczenia,
- zgodna chustka,
- zgodna paleta i rodzina materiałów,
- poprawny kierunek spojrzenia,
- brak elementów niepokojących lub nieodpowiednich dla dziecka,
- jedna czytelna intencja,
- brak niedozwolonego driftu.

Pojedyncza niezaliczona twarda kontrola blokuje akceptację i wymaga poprawki lub
powtórzenia rundy.

### 34.3. Ocena jakościowa

Osoba dokonująca przeglądu ocenia każdy wymiar w skali 1–5:

- rozpoznawalność,
- sympatyczność,
- spokój,
- czytelność pozy i emocji,
- spójność między wynikami.

Każdy wymiar musi uzyskać co najmniej 4/5. Oceny i uwagi należy zapisać wraz z
identyfikatorem badanego kandydata.

### 34.4. Test miniatury

Neutralna sylwetka oraz kluczowy gest powinny pozostać czytelne przy wysokości
postaci około 128 px, bez konieczności rozpoznawania drobnych tekstur.

## 35. Acceptance criteria — Mela Master v1

Projekt może otrzymać status `LOCKED — Mela Master v1` wyłącznie wtedy, gdy:

- istnieje jeden jednoznacznie wskazany kandydat,
- canonical reference pack jest kompletny i wewnętrznie zgodny,
- turnaround nie zawiera sprzecznych objętości ani oznaczeń,
- sylwetka jest czytelna także w miniaturze,
- wszystkie 12 wyników przechodzi twarde kontrole,
- każdy wymiar jakościowy uzyskuje co najmniej 4/5,
- podstawowe ekspresje są rozróżnialne bez przesadnej reakcji,
- Mela potrafi obserwować, słuchać, pytać, wskazywać, dotykać lub trzymać prosty
  obiekt i spokojnie reagować na odkrycie,
- paleta oraz materiały są zapisane w sposób umożliwiający odtworzenie,
- chustka i pozostałe elementy zachowują spójność w widokach oraz ruchu,
- nie występuje niedozwolony character drift,
- prompt został sprawdzony razem z referencjami, ale nie jest jedynym mechanizmem
  utrzymania tożsamości,
- człowiek jawnie zatwierdził wskazaną wersję i datę.

Po akceptacji należy świadomie:

1. oznaczyć reference pack jako `LOCKED — Mela Master v1`,
2. wpisać potwierdzone cechy do identity locks,
3. zastąpić robocze opisy palety i proporcji dokładnymi referencjami,
4. zaktualizować status oraz wersję Character Bible,
5. zachować wcześniejsze warianty jako historię eksploracji, nie jako równoległe
   źródła prawdy.

Brak któregokolwiek wymogu pozostawia projekt w statusie `CANDIDATE`.

## 36. Decyzje pozostające `OPEN`

- stopień antropomorfizacji,
- postawa i sposób poruszania się,
- dokładna sylwetka i wszystkie proporcje,
- liczba head-units,
- obrys i objętość głowy,
- budowa pyszczka, nosa, ust i ewentualnego uzębienia,
- kształt, rozstaw, tęczówki, źrenice, powieki i bliki oczu,
- wielkość, osadzenie, kolor i zakres ruchu uszu,
- anatomia przednich łapek, liczba widocznych palców i sposób chwytu,
- anatomia nóg, stóp i sposób stawiania łap,
- długość, objętość, oznaczenia i pozycja spoczynkowa ogona,
- rozmieszczenie umaszczenia i dodatkowych oznaczeń,
- dokładna paleta sRGB,
- kolor, materiał, rozmiar, wiązanie, wzór i zachowanie chustki,
- dokładny materiał futra lub powierzchni,
- technika renderowania i parametry materiałów,
- ostateczny zakres ekspresji oraz deformacji twarzy,
- dokładne zasady timingu, chodu, idle i squash and stretch,
- głos, obsada i wykonanie aktorskie,
- częstotliwość kontaktu wzrokowego z dzieckiem,
- szczegóły relacji i skala względem przyszłego Piko,
- skala względem świata,
- wszystkie przyszłe wizualne identity locks,
- finalna wersja i akceptacja canonical visual reference packu.

Każda z tych decyzji powinna pozostać jawnie `OPEN`, dopóki nie zostanie
rozstrzygnięta we właściwym etapie projektu. Brak decyzji nie upoważnia do
utrwalenia przypadkowego wyniku generowania.
