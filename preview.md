### Wstęp 
Internet jest już znany na całym świecie, natomiast przeciętnemu użytkownikowi
kojarzy się on z siecią komputerów, które są ze sobą połączone. Dziś internet
oznacza dużo więcej niż tylko komputery, przy których siedzą ludzie. Coraz częściej
to również urządzenia i maszyny, z których każdy na co dzień korzysta. Takie
połączenia miliardów różnych czujników, komputerów i urządzeń uruchamiających,
stanowią dużą zmianę w życiu nas wszystkich, dlatego też często mówi się o tym
jako o kolejnej rewolucji internetowej.
Termin „Internet rzeczy” z ang. „Internet of Things”, w skrócie IoT, to koncepcja
stworzona prze Kevina Ashtona. Można ja tłumaczyć na wiele różnych sposobów,
natomiast według nas najlepiej określa się ją jako ekosystem, w którym przedmioty,
dzięki wyposażeniu w sensory komunikują się z komputerami. Dla wielu ludzi to
nadal coś niewyobrażalnego, ale niedługo w jedną sieć będzie połączone ze sobą
praktycznie wszystko. Wiele nowych możliwości staje otworem dla ludzi, którzy
zajmują się marketingiem i komunikacją, ale nie tylko.
Tematem naszej pracy jest Internet rzeczy i
kierunki jego wykorzystania. Został przez nas
wybrany, ponieważ wszyscy się nim
interesujemy i staramy się go wprowadzać do
naszego życia prywatnego. Przykładamy takiego
wprowadzenia jest oświetlenie na listwach
ledowych w całym domu, sterowane aplikacją
zainstalowaną w telefonie komórkowym, a także
nawadnianie ogrodu dzięki czujnikom
wilgotności, zamontowanymi na całym terenie
przeznaczonym do podlania. Rozwiązanie to jest
możliwe w oparciu o Raspberry Pi, które działa
pod kontrolą systemów operacyjnych opartych
na Linuksie oraz RISC OS, a najnowszy model
Raspberry Pi 2 B, działa również pod kontrolą
Windowsa 10.

Rysunek 2 IoT, źródło:
http://www.computerworld.com/article/2488136/internet
Celem niniejszej pracy jest, dla tych którzy nie wiedzieli czym jest Internet of Things,
-4- things-to- do-now- to-get- ready-for- the-internet- of-
things.html, data pobrania: 20.05.2016
możliwością poznania go. Dla osób, które już go doskonale znają, możliwością
lepszego zrozumienia, w jaki sposób zmienia on krajobraz sieci komputerowych oraz
komunikacji.
Podstawą do napisania pracy stanowiła literatura podmiotu. Jednym z głównych
źródeł była książka Michaela Millera pt. „The Internet of Things: How Smart TVs,
Smart Cars, Smart Homes, and Smart Cities Are Changing the World”, z której
dowiedzieliśmy się co jest realne, a co nie, w jaki sposób połączone urządzenia
mogą poprawić nasze życie prywatne, a także prowadzony biznes, co się dzieje z
danymi gromadzonymi w siedzi, czy można dzięki niemu zdrowiej żyć czy
oszczędzać energię, oraz jakie zagrożenia niesie za sobą IoT. Ważna rolę w
przygotowaniu do pracy dał nam raport „Internet Rzeczy w Polsce” oraz ksiażka
„Internet rzeczy, Bezpieczeństwo w Smart City”, wydawnictwa C.H. Beck.
Praca składa się ze wstępu, trzech rozdziałów merytorycznych oraz zakończenia.
Wstęp zawiera ogólny opis problematyki pracy, jej cel oraz powód jej napisania.
Pierwszy rozdział to bardziej szczegółowy opis terminu „Internet of Things”, jego
korzyści i wyzwania oraz prywatność w Internecie Rzeczy. Drugi rozdział to opis
zastosowań IoT w różnych dziedzinach życia oraz jego rozwiązania. W trzecim
rozdziale przedstawimy kierunki rozwoju Internetu Rzeczy oraz zagrożenia, które za
sobą niesie.
### Rozdział I 
Żyjąc w XXI wieku jesteśmy świadkami wielu cyfrowych rewolucji. Internet Rzeczy to coś, co
otwiera przed nami wiele nowych dróg i ścieżek komunikacji z konsumentem. Są one
szybsze, łatwiejsze i jeszcze bardziej efektywne niż były dotychczas. Pewna część ludzi widzi
w IoT szanse, inni boją się, że postępująca cyfryzacja za bardzo rozpowszechnia się w
naszym życiu. Mimo wszystko, liczba urządzeń podłączonych do internetu wzrasta w bardzo
szybkim tempie.
Ilość urządzeń IoT w latach w bln
30
25
20
15
10
5
0
Wykres 1 Ilość urządzeń IoT , źródło: Gartner, listopad 2014r.
Internet rzeczy dotyczy przedmiotów, które gromadzą i przetwarzają dane, pośrednio
bądź bezpośrednio, dzięki sieci komputerowej. Możemy do nich zaliczyć smartfony i
laptopy, a także samochody, sprzęty, biura, fabryki, a nawet całe miasta, gospodarkę
wodną czy systemy obronne. IoT wpływa między innymi na projektowanie i serwis, a
także na zarządzanie zasobami ludzkimi, dzięki czemu stwarza ogromne szanse na
„lepsze jutro” w dziedzinie biznesu.
Jak już wcześniej powiedzieliśmy, Internet Rzeczy może być rozumiany jako
ekosystem, w którym komunikacja występuje z udziałem człowieka, lub bez niego.
Aby móc wymienić informacje między dwoma przedmiotami, należy spełnić
określone warunki.
Pierwszą ważną rzeczą jest to, iż przedmiot, który ma wysyłać informacje, musi być
wyposażony w sensor. Dzięki niemu jest w stanie zebrać potrzebne dane z
otoczenia, aby móc je przekazać odbiory. Jako nadajniki mogą posłużyć smartfony,
2013201420152020
czujniki wilgotności, temperatury czy ruchu. Różnica między tymi czujnikami a
smartfonem jest taka, iż ze smartfona dane są wysyłane dzięki akcji, którą wyzwala
człowiek. Przykładami ostatnio bardzo modnymi mogą być opaski mierzące tętno,
czy liczące ilość wykonanych kroków w ciągu dnia, a także mniej popularne jeszcze
w Polsce prześcieradła z czujnikami ruchu.
Kolejnym warunkiem, jaki musi być spełniony jest to, że przedmiot, który będzie
odbierał sygnał przesłany przez nadawcę, musi być w stanie go odebrać,
przetworzyć i wywołać odpowiednią relacje. Przy takich odbiornikach jak komputer
czy telefon, informacja przesłana wyświetli się na ekranie. Mogą to być także
urządzenia, które wykonają określona czynność, a nie wyświetlą samą informacje.
Na przykład układ nawadniania, który automatycznie włączy wodę, czy też rolety,
które zasłonią się lub odsłonią o odpowiedniej porze. Bardziej abstrakcyjnymi
przykładami mogą być książki, które wyświetlą datę zwrotu do biblioteki, czy też
lodówki pokazujące braki w zaopatrzeniu domowej spiżarni.
Trzecia rzeczą potrzebną do stworzenia takiej relacji jest środek komunikacji, czyli to
w jaki sposób dane zostaną przesłane od nadawcy do odbiorcy. Najbardziej
popularne w dzisiejszych czasach to WiFi czy Bluetooh, a mniej znane dla
przeciętnego użytkownika internetu NFC czy Z-WAVE, które wykorzystywane są w
systemach budynków.
Rysunek 3 Źródło: Opracowanie własne
Kierunki rozwoju szerzej omówione zostaną w rozdziale trzecim, natomiast tutaj
krótko powiemy tylko, że głównym kierunkiem jest zwiększenie relacji pomiędzy
człowiekiem, a przedmiotem, a to wywołuje potrzebę analizy coraz większej ilości
danych.
Jest wiele korzyści wynikających z korzystania z rozwiązań IoT. Bardzo często są to
korzyści finansowe, czyli redukcja kosztów i lepsza alokacja kapitału. Następną
korzyścią jest zwiększenie produktywności i bezpieczeństwa kadry pracowniczej oraz
poprawa relacji z klientem, dzięki zwiększonej komunikacji. Do korzyści płynących z
realizacji ekosystemu IoT zalicza się również oszczędność zużycia energii, Lepszą
kondycję fizyczną oraz zdrowie własne i bliskich. Ważną rzeczą jest też większe
poczucie kontroli nad urządzeniami i sprzętami.
Są trzy poziomy dojrzałości,
dzięki którym możemy zauważyć
bezpośrednie korzyści
biznesowe.
Pierwszy poziom „Data to
Discovery”, mówi o bazie nowych
danych i ich wykorzystaniu, w
celu dowiedzenia się o rzeczach,
o których nie było wiadomo
dotychczas. Przykładem może
być odnalezienie nowych
wzorców choroby dzięki informacji
z maszyn medycznych.
Rysunek 4 Źródło: http://www.letechworld.com/blog-iot- smart-living- but-
safety-first/, data pobrania: 20.05.2016
Drugim poziomem dojrzałości jest „Data to Decisions”, w którym mowa o tym, że na
bazie odpowiednich danych można podjąć autonomicznie akcje, na przykład
awaryjne wyłączenie urządzenia w momencie awarii.
Ostatnim poziomem jest „Data To Dollors-Dividents”, gdzie widać korzyść finansową
dla firmy bądź szanse jej rozwoju, gdy połączy się dwa wcześniejsze poziomy ze
sobą oraz wprowadzi usługi i produkty innowacyjne.
Kiedy powstały media społecznościowe, wpłynęły znacząco na to, jak zaczęto
organizować swoje życie, oraz zmieniły one modele biznesowe. Tak samo Internet
rzeczy znalazł już swoje miejsce. Można powiedzieć, że jest on etapem rewolucji
informacyjnej. Dostarczamy techniki i narzędzia, dzięki którym możemy budować
wiedzę. Na dużych i szybkich strumieniach danych, nowoczesne urządzenia są w
stanie podejmować odpowiednie decyzje. Sukcesu można się spodziewać, jeżeli
wprowadzi się innowacyjne zastosowania w nowej przestrzeni.
Wiele rzeczy wpłynęło na rozwój IoT. Jedną z nich i najważniejszą jest
miniaturyzacja. Dzięki niej możmy wszędzie umieścić mikroelementy (czujniki,
komputery). Ważną rolę odegrała też technologia mobilna, która ciągle się rozwija.
Ostatnia ważną rzeczą, bez której IoT by nie istniało jest bezprzewodowa sieć
internetowa.
Niestety istnieje kilka barier rozwojowych dla tematu IoT. Pierwszą ważną rzeczą jest
problem zasilania. Każde urządzenie, nawet to, w którym jest bardzo mocna bateria,
wymagać będzie w końcu podłączenia do prądu. Kolejną barierą jest ilość tylko 4 mld
urządzeń, które mogą posiadać adres IPv4. Aby rozwiązać ten problem należy
używać adresu IPv6, który ma dużo więcej kombinacji ze względu na to, że jest
dłuższy od wersji czwartej. Ostatnią barierą, o której wspomnę to bezpieczeństwo
danych i prywatność. Przekonanie ludzi, że informacje są chronione jest bardzo
trudne, ale możliwe. Przykładem tego zjawiska są banki. Jeżeli dane między
urządzeniami będą tak samo zabezpieczone jak środki na internetowym rachunku
bankowym to Internet of Things stanie się rzeczywisty.

### Rozdział II

2.1. Wstęp
Przygodę z internetem rzeczy możemy zacząć od kupienia gotowych rozwiązań np. inteligentna
żarówka. Dzięki niej możemy za pomocą modułu Bluetooth 4.0 sterować żarówką – włączać,
wyłączać, zmieniać intensywność światła, a nawet jego kolor. Ale co jeśli nam to nie wystarcza?
Albo po prostu lubimy majsterkować i chcielibyśmy pójść o krok dalej. Na przykład sprawić by
żarówka świeciła się gdy wykryje ruch w pokoju? Tu właśnie pojawia się płytka Arduino.
Projekt Arduino powstał w 2005 roku we Włoszech. Jest to układ scalony który składa się z 8­
bitowego mikrokontrolera Atmel AVR. Płytka posiada ustandaryzowany rozkład wyjścia/wejścia
co umożliwia stosowanie gotowych rozwiązań rozszerzających możliwości układu np. Ethernet
shield – moduł dający możliwość połączenia płytki bezpośrednio z internetem.
Dzięki swej prostocie i ogromnym możliwościom Arduino jest jednym z najpopularniejszych
urządzeń stosowanych przy budowaniu projektów DIY (do it yourself).
Jest to idealne środowisko dla programistów którzy nie lubią bawić się lutownicą, a także chcieliby
rozpocząć przygodę z internetem rzeczy. Do napisania pierwszego programu i uruchomieniu go na
naszej płytce nie potrzebujemy żadnych dodatkowych kontrolerów, modułów. Wystarczy nam
sama płytka, ma ona wbudowane diody którymi możemy sterować.

2.2 „Hello World!”
Przykład typowego programu od którego zaczynamy przygodę z Arduino ­ mruganie diodą.
// kod
#define DIODA 13 (1)
void setup() { (2)
pinMode (DIODA, OUTPUT);
}
void loop() { (3)
digitalWrite (DIODA, HIGH);
delay (500);
digitalWrite (DIODA, LOW);
delay (500);
}
// koniec kodu
Osoby mające wcześniej styczność z językiem C nie powinny mieć problemów ze zrozumieniem
jak działa powyższy program. Dzieli on się na dwie części: setup() oraz loop().
Przed samym programem zdefiniowaliśmy zmienną której będziemy używać w programie. (1)
Pierwsza część (2) wywoływana jest tylko raz, przy uruchomieniu programu. Służy ona do
ładowania ustawień na płytkę.
W Naszym przypadku ustawiamy wcześniej zdefiniowaną zmienną która sygnalizuje 13 pin na
płytce.
Następnie mamy funkcję (3) która wykonywana jest wielokrotnie, przez cały czas działania czyli
do momentu aż odłączymy zasilanie od układu.

2.3 Przykładowe projekty

2.3.1 Stacja Meteorologiczna
Jednym z najprostszych a dającym najwięcej satysfakcji projektów jest stacja meteorologiczna
zbudowana przy pomocy Arduino oraz kilku czujników. Poziom zaawansowania zależy tutaj od
budującego taką stacje. Możemy po prostu mierzyć temperaturę oraz wilgotności za pomocą
czujnika – np. DHT11. Do zbudowania takiej stacji wystarczy nam tylko jeden czujnik.
Jednak internet rzeczy nie polega na tym by tworzyć przedmioty które już istnieją. Chodzi o to by
pójść krok dalej i stworzyć coś co za pomocą internetu ułatwi nam życie.
Do wspomnianego projektu stacji możemy dołączyć kilka czujników i zrobić z niej całkiem fajne
narzędzie do analizowania pogody. Dorzucając takie funkcjonalności jak: wykrywanie burzy,
pomiar ciśnienia, sprawdzanie prędkości oraz kierunku wiatru. Jednocześnie wysyłając wszystkie
dane do sieci tak aby mieć podgląd do ich historii. Możemy wykorzystać naszą stacje jako centrum
informacji np. o wiatrach, kierunku i ich sile. Przydaje się to osobom uprawiającym sporty w
których wiatr odgrywa ważną role np. Windsurfing, Kitesurfing.

2.3.2 Sterowanie oświetleniem
Za pomocą Arduino jesteśmy w stanie sterować oświetleniem w całym mieszkaniu. Wystarczy, że
odpowiednio podłączymy moduły z przekaźnikiem do sterownika. Możliwości tego rozwiązania są
ogromne. Możemy napisać aplikacje która umożliwi sterowanie oświetleniem przez stronę
internetową. Plusem takiego rozwiązania jest to, że możemy symulować naszą obecność w domu
poprzez włączanie/wyłączanie świateł gdy jesteśmy na wczasach. Jest też druga strona medalu –
możemy paść ofiarą hackera który będzie sterował naszym oświetleniem bez naszej zgody.
Zdarzają się również przypadki całkowicie odmienne. W ubiegłym roku jeden z użytkowników
postanowił udostępnić sterowanie swoim oświetleniem świątecznym. Na stronie gdzie można było
włączać, wyłączać oświetlenie był jednocześnie podgląd on­line. Projekt ten cieszył się sporym
zainteresowaniem.

### Rozdział III
Kierunki rozwoju Internetu Rzeczy
Dla przeciętnego człowieka internet to połączone w sieć komputery, które
wymieniają się danymi. Internet jest dla niego miejscem czerpania wiedzy i
rozrywki, komunikowania się ze znajomymi i wrażania swoich opinii. Jest to dla
niego otwarty, częściowo anonimowy wirtualny świat, zupełnie inny od tego w
którym żyje na co dzień. Początki internetu były bardzo skromne ale teraz jest to ogromna sieć
łącząca ze sobą już nie tylko komputery, ale też telefony czy nawet urządzenia gospodarstwa
domowego. Internet rozrasta się w tempie wykładniczym – jego rozwój niesie za sobą ogromne
korzyści, ale również poważne zagrożenia.
(Źródło: http://www.nsr.cm/news­resources/the­bottom­line/internet­of­things-
prime­time­for­satellite/)
Największym motorem napędowym ekspansji Internetu Rzeczy jest chęć ludzi do
ułatwiania sobie życia. Najlepszym tego przykładem jest koncepcja tzw.
„Inteligentnego Domu”. Już w tym momencie możemy ustawić pralkę, aby rozpoczęła swoją
pracę z opóźnieniem dzięki czemu możemy wrócić do domu akurat gdy pranie się skończy.
Możemy zainstalować przełączniki światła sterowane dźwiękiem, dzięki czemu możemy zgasić
lub zapalić światło nie wstając z łóżka. Mamy czasowe przełączniki, które symulują obecność
domowników podczas ich nieobecności, żelazka, które same się wyłączą po pewnym okresie
nieaktywności i tak dalej. Przykładów jest dużo więcej, a codziennie dochodzą nowe urządzenia,
które w mniejszym lub większym stopniu ułatwiają nam życie w domu. Jeśli połączymy te
wszystkie urządzenia w jedną sieć zarządzaną centralnie możemy mówić o inteligentnym domu.
Jest on inteligentny na swój sposób – jest zaprogramowany aby zachowywać się w określony
sposób lecz nie jest do końca autonomiczny. Co raz bardziej rozpędzający się postęp
technologiczny w połączeniu z nieograniczoną ludzką wyobraźnią tworzy mieszankę wybuchową
co wcale nie oznacza najgorszego. Wszak dynamit jest teraz kojarzony z bandytami napadającymi
na banki, został wynaleziony w celu ułatwienia wydobywania naturalnych zasobów Ziemi.
Internet Rzeczy rozwija się w wielu kierunkach, nawet w dziedzinach które w ogóle
nie kojarzą się z elektroniką. Doskonałym przykładem są tzw. „wearables”, czyli
przedmioty osobiste które użytkownik nosi na sobie. Są to na przykład smart
watch'e, które mają wbudowane moduły łączności bezprzewodowej. Takie
urządzenia mogą mieć dodatkowo wbudowane moduły GPS, co w teorii może
znacząco ułatwić wezwanie pomocy w odpowiednie miejsce. Jednak taki zegarek
może też przysporzyć wielu kłopotów – gdy osoba trzecia uzyska dostęp do danych
lokalizacyjnych może z łatwością śledzić użytkownika i wykorzystać tę wiedzę do
złych celów. Jeśli włamywacz ma absolutną pewność, że dana osoba znajduje się
setki kilometrów od domu to bez większego ryzyka nakrycia może ten dom okraść.
Na szczęście rynek wearables jeszcze raczkuje, a najwięcej urządzeń mogących
tworzyć Internet of Things powstaje w dziale RTV/AGD. Urządzenia domowe już
dawno przyćmiły swoich protoplastów swoją mocą obliczeniową i możliwościami. Współczesne
telewizory nie tylko są w stanie wyświetlać obraz nadawany z zewnętrznego urządzenia, ale same
potrafią rozkodować sygnał z anteny. Mają własne systemy operacyjne, które implementują
możliwości będące do niedawna ekskluzywną domeną komputerów osobistych. Posiadają
przeglądarki internetowe, komunikatory a nawet gry. Niektóre mają wbudowane kamerki
internetowe, a większość z nich obsługuje peryferyjne urządzenia rejestrujące. Tutaj znowu
pojawia się problem, ponieważ owszem te urządzenia wykorzystywane są do prowadzenia wideo-
rozmów ale gdy dostęp do nich uzyska niepowołana osoba stwarza to realne zagrożenie dla
domowników, nie mówiąc już o utracie jakiejkolwiek prywatności.
Udział sprzętu RTV/AGD w ekosystemie IoT przekracza 30% (przypis:
http://iab.org.pl/wp­content/uploads/2015/09/Raport­Internet­Rzeczy­w­Polsce.pdf
s.13). Nic w tym dziwnego, skoro cała idea Internetu Rzeczy zrodziła się właśnie w
urządzeniach tego typu. Są to na razie tradycyjne sprzęty użytku domowego, czyli
np. skanery, telewizory, urządzenia audio. Nowości na rynku sprzętu
elektronicznego, takie jak smart lodówki, stanowią znikomy ułamek całego udziału
sprzętu RTV/AGD w urządzeniach uważanych jako mogące być częścią IoT.
Zagrożenia
Urządzenia, z których korzystamy na co dzień są co raz bardziej złożone. Ma to na
celu oczywiście ułatwienie życia i umożliwienie dokonywania rzeczy które
wcześniej istniały tylko w sferze fantastyki.
Najbardziej niebezpieczne wydają się wspomniane wcześniej wearables. Z definicji
nosimy je zawsze przy sobie i to one stanowią największe niebezpieczeństwo dla
użytkownika oraz są najbardziej podatne na utratę prywatności. Przykładem
nasuwającym się od razu na myśl jest Google Glass.
To urządzenie może wkrótce zrewolucjonizować rynek urządzeń mobilnych. Jednak
niesie to za sobą poważne zagrożenia. Google Glass do komunikacji z siecią może
używać albo połączenia Bluetooth, albo Wi­Fi. W przypadku tego pierwszego
potrzebne jest dodatkowe urządzenie służące jako punkt dostępowy dla okularów od
internetowego giganta. Druga opcja jest bardziej przystępna, gdyż nie wymaga od
użytkownika posiadania przy sobie innego urządzenia mobilnego z dostępem do
sieci. Jednak jak zauważa Roberto Martinez, badacz z Kaspersky Lab, który
przyjrzał się sprawie bezpieczeństwa Google Glass, komunikacja Wi­Fi naraża
urządzenie na ataki hakerów. Martinez i Juan Andres Guerrero – kolega z zespołu
badawczego – przeprowadzili eksperyment w monitorowanej sieci. Odkryli, że tylko
część danych wymienianych między urządzeniem a punktem dostępowym była
szyfrowana. Badaczom udało się ustalić, że „ofiara” szukała połączeń lotniczych
oraz miejscowości turystycznych. Potencjalny haker prawdopodobnie mógłby
wyciągnąć jeszcze więcej informacji, gdyby tylko poświęcił na to więcej czasu.
“We admit that it is not a very damaging vulnerability, but even so, profiling via
meta data from Web traf ic exchange could become the first step of a more complex
attack against the device’s owner,” ­ Roberto Martinez (źródło:
http://newsroom.kaspersky.eu/en/texts/detail/article/wear­the­dager­kaspersky­lab-
experts­warn­of­security­risks­facing­wearable­connected­devices)
Kolejnym całkiem nowym na rynku urządzeniem które potencjalnie może
przysporzyć właścicielowi kłopotów jest Galaxy Gear 2 od Samsunga. Jest to tzw.
smartwatch – zegarek, który potrafi dużo więcej niż tylko wskazać godzinę.
Eksperci z Kaspersky Lab również przyjrzeli się temu akcesorium i zarówno jak i w
przypadku Google Glass jak i tutaj znaleźli potencjalne zagrożenia dla użytkownika.
Pierwszą rzeczą, na jaką zwrócili uwagę badacze był aparat. Samsung dobrze zdawał
sobie sprawę, że umieszczanie miniaturowego aparatu w bardzo małym,
niepozornym urządzeniu może narobić komuś szkody. Dlatego zegarek wydaje głośny dźwięk
za każdym razem gdy robione jest zdjęcie i nie umożliwia wyłączenia tej opcji w żaden sposób.
Ma to na celu ostrzeżenie ludzi dookoła, że potencjalnie zostało zrobione im zdjęcie. Jednak
pracownicy Kaspersky Lab znaleźli obejście tego zabezpieczenia. Wystarczy tylko uzyskać dostęp
administratora (tzw. root) co jest trywialnie proste mając fizyczny dostęp do urządzenia i użyć
ogólnodostępnego narządzia ODIN od Samsunga. Wyłączając dźwięk migawki nie tylko
umożliwiamy właścicielowi zegarka robienie tajnych zdjęć innym osobom, ale też umożliwiamy
hakerowi robienie zdjęć właścicielowi, tego co robi i gdzie jest – bez jego wiedzy.
Innym problemem Galaxy Gear 2 jest sposób, w jaki instalowane są aplikacje.
Używane jest do tego oficjalne oprogramowanie od Samsunga – Gear Manager –
jednak sposób w jaki aplikacja wgrywa inne programy do akcesorium pozostawia
duży potencjał hakerski. Na zegarku nie wyświetla się żadna informacja o instalowanym
oprogramowaniu, co umożliwia instalowanie złośliwych aplikacji bez wiedzy posiadacza. W
połączeniu z wiedzą jak ukrywać zainstalowane już aplikacje na systemie Android, na którym
Galaxy Gear 2 operuje, daje to nieograniczone możliwości dla hakerów.
Na szczęście są to urządzenia dosyć młode na rynku sprzętu elektronicznego i
zagrożenia związane z włamywaniem się na nie nie są aż tak powszechne. Jak
zaznacza Juan Andres Guerrero na chwilę obecną nie ma żadnych dowodów sugerujących, że
wearables są celem hakerów jednak to może się zmienić w przyszłości, gdy staną się bardziej
powszechne.
“At this time there is no evidence to suggest that wearables are currently being
targeted by professional APT actors. However there is a twofold appeal presented by
wearables that make them a likely future target if they are widely adopted by
consumers. In future the data collected by wearable devices is going to attract new
players to the cyber­espionage scene.” ­ Juan Andres Guerrero (źródło:
http://newsroom.kaspersky.eu/en/texts/detail/article/wear­the­danger­kaspersky­lab-
experts­warn­of­security­risks­facing­wearable­connected­devices/?
no_cache=1&cHash=3d466480a48adaf32ff6eafe640cd6e1)
Niebezpieczeństwa niesione przez IoT można rozpatrywać na dwa sposoby:
niebezpieczeństwa związane z informatyzacją świata konsumenckiego lub
optymalizacją sektora przemysłowego (źródło: http://www.komputerswiat.pl/sekcje-
specjalne/klikaj­bezpiecznie/zagrozenia/internet­rzeczy­czym­jest­i­jakie­nieie-
zagrozenia.aspx). W czasach rozpędzającego się rozwoju Internetu rzeczy ludzie
skazani są na informatyzację większości z dziedzin życia. Inteligentny sprzęt
gospodarstwa domowego, elektroniczne zamki do drzwi lub okien, liczniki energii,
itd. Wszystkie te sprzęty niosą za sobą spore niebezpieczeństwo, a ich przeciętni
użytkownicy nie zdają sobie z tego sprawy. Bo przecież dlaczego ktoś miałby się
bać swojej lodówki? Otóż wszystko wskazuje na to, że niedługo lodówki będą w
stanie gromadzić informacje na temat ich zawartości. Wiedza ta w niepowołanych
rękach może zaszkodzić użytkownikowi. Na pewno nie w bezpośredni sposób, bo
dieta ofiary nie może być wykorzystana np. do kradzieży z konta bankowego.
Jednak umożliwi tzw. profilowanie ofiary. Tak niepozorna wiedza jak to co kto je na
śniadanie, w połączeniu z innymi teoretycznie bezpiecznymi informacjami jak np.
godzina o której ofiara rano wstaje (wykradziona ze smartwatch'a) oraz np. ile
ciepłej wody zużywa ofiara (wiedza wykradziona z elektronicznych liczników
wody). Tak nagromadzona wiedza, pozornie nieprzydatna z punktu widzenia hakera,
pozwala na dokładną inwigilację ofiary; poznania jej nawyków oraz sposobu w jaki
żyje. Taka wiedza może narobić ofierze wielu problemów gdy znajdzie się w
niepowołanych rękach.
