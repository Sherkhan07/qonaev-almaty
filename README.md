# Қонаев және Алматы — цифрлық шежіре

Дінмұхамед Қонаев пен Алматы тарихына арналған интерактивті сайт: уақыт сызығы, OpenStreetMap деректерінен салынған Алматының 3D картасы, нақты фотолар бойынша жасалған 3D модельдер, «кеше және бүгін» фото салыстыруы, фотомұрағат, викторина.

**Сайт:** https://qonaev-almaty.vercel.app/

## Жоба туралы

- **Орындаған:** Абибулла Айсара Жанабайқызы
- **Ғылыми жетекшісі:** Ауылбай Нұржан
- **Мектеп:** Шоқан Уалиханов атындағы №12 мамандандырылған лицей, Алматы
- **Секция:** Қазақстан тарихы, 2026

## Құрылымы

| Файл | Мазмұны |
|---|---|
| `index.html` | Сайттың өзі (HTML, CSS, JavaScript) |
| `img/` | Wikimedia Commons-тан алынған фотолар |
| `almaty-map.js`, `almaty-map.json` | 3D картаға арналған OpenStreetMap деректері (ғимараттар, көшелер, өзендер, саябақтар, метро) |

Сайт Three.js (r128) кітапханасын cdnjs.cloudflare.com арқылы жүктейді. Компьютерде қарау үшін қалтада жергілікті сервер іске қосыңыз (мысалы, `python3 -m http.server`), себебі карта деректері `file://` арқылы ашылмауы мүмкін.

## Дереккөздер мен лицензиялар

**Карта деректері:** © [OpenStreetMap](https://www.openstreetmap.org/copyright) қатысушылары, ODbL лицензиясы.

**Фотолар** (Wikimedia Commons, әрқайсысы өз лицензиясымен):

| Файл | Сипаттамасы | Авторы | Лицензиясы | Түпнұсқа |
|---|---|---|---|---|
| `img/kunaev_inst.jpg` | Қонаев (сол жақта) Мәскеудегі түсті металдар және алтын институтында (1930-жж.) | Белгісіз автор | Қоғамдық домен | [Commons]() |
| `img/kunaev_1937.jpg` | Қонаев Балқаштағы Прибалхашстрой кенішінде (1937) | Белгісіз автор | Қоғамдық домен | [Commons]() |
| `img/kunaev_1952.jpg` | Д.А. Қонаев — ҚазКСР Ғылым академиясының президенті, Алма-Ата (1952) | Белгісіз автор | Қоғамдық домен | [Commons]() |
| `img/kunaev_1981.jpg` | Қазақстан Компартиясының XV съезі, ақпан 1981: Қонаев — бірінші қатарда солдан 7-ші (1981) | Липатова Е.А. | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Commons]() |
| `img/kbtu_1969.jpg` | Үкімет үйінің портигі (Commons атауы: «1969 ЦК Компартии Казахстана») (1970-жж.) | Andris Malygin | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0) | [Commons]() |
| `img/palace_1978.jpg` | Ленин сарайы: ДДСҰ мен ЮНИСЕФ-тің алғашқы медициналық-санитариялық көмек жөніндегі конференциясы (Алма-Ата декларациясы) (1978) | Wikimedia Commons | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) | [Commons]() |
| `img/kbtu_stamp.jpg` | КСРО маркасы: Қазақ КСР-і мен Қазақстан Компартиясының 60 жылдығы (суретші Т. Панченко) (1980) | КСРО поштасы | Қоғамдық домен | [Commons]() |
| `img/palace_stamp.jpg` | КСРО маркасы «Алма-Ата»: Ғылым академиясы, Үкімет үйі және Республика сарайы (1990) | КСРО поштасы | Қоғамдық домен | [Commons]() |
| `img/kbtu_1999.jpg` | Астана алаңы: сол кездегі қалалық парламент ғимараты, қазіргі КБТУ (1999) | Brian Harrington Spier | [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0) | [Commons]() |
| `img/hotel_cc0.jpg` | «Қазақстан» қонақүйі, Құрманғазы көшесінен көрініс (2025) | Dauren Nabijan | [CC0](http://creativecommons.org/publicdomain/zero/1.0/deed.en) | [Commons]() |
| `img/hotel_tyl.jpg` | «Қазақстан» қонақүйі, бүйір қасбеті (2018) | t_y_l | [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0) | [Commons]() |
| `img/kbtu_mb.jpg` | КБТУ ғимараты (бұрынғы Үкімет үйі), Төле би көшесі (2024) | Matti Blume | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en) | [Commons]() |
| `img/kbtu_2026.jpg` | КБТУ ғимараты, Төле би көшесінен (2026) | Nikolai Bulykin | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Commons]() |
| `img/palace_2022.jpg` | Республика сарайы (2022) | DS28 | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Commons]() |
| `img/tower_cc0.jpg` | Көктөбе телемұнарасы және Іле Алатауы (2020) | Gulim 8 | [CC0](http://creativecommons.org/publicdomain/zero/1.0/deed.en) | [Commons]() |
| `img/tower_grau.jpg` | Телемұнара мен таулар, қаладан көрініс (2012) | Michael Grau | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Commons]() |
| `img/medeu_dam.jpg` | Медеу шатқалындағы бөгет құрылысының жер жұмыстары (Commons атауында — 1969) (1960–70-жж.) | Andris Malygin | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0) | [Commons](https://commons.wikimedia.org/wiki/File:1969_-_panoramio_-_Andris_Malygin_(1).jpg) |
| `img/medeu_70s.jpg` | Медеу мұз айдыны, кеңестік кезең (Commons атауында — 1969) (1970-жж.) | Andris Malygin | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0) | [Commons](https://commons.wikimedia.org/wiki/File:1969_-_panoramio_-_Andris_Malygin_(2).jpg) |
| `img/memorial_70s.jpg` | Панфиловшылар саябағындағы Даңқ мемориалы мен Мәңгілік алау (Commons атауында — 1969) (1975 ж. кейін) | Andris Malygin | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0) | [Commons](https://commons.wikimedia.org/wiki/File:1969_-_panoramio_-_Andris_Malygin_(9).jpg) |
| `img/cathedral_70s.jpg` | Вознесенский (Зенков) соборы, кеңестік кезең (Commons атауында — 1969) (1970-жж.) | Andris Malygin | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0) | [Commons](https://commons.wikimedia.org/wiki/File:1969_-_panoramio_-_Andris_Malygin_(6).jpg) |
| `img/medeu_1982.jpg` | Медеу мұз айдыны мен шатқал, жоғарыдан көрініс (1982) | Mr Ptero | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Commons](https://commons.wikimedia.org/wiki/File:%D0%9C%D0%B5%D0%B4%D0%B5%D0%BE_1982.jpg) |
| `img/medeu_stamp.jpg` | КСРО маркасы: Медеудегі әйелдер арасындағы Еуропа чемпионаты (1974) | КСРО поштасы | Қоғамдық домен | [Commons](https://commons.wikimedia.org/wiki/File:1974_Speed_Skating_Women_Europe_Championship.jpg) |
| `img/panfilov_1982.jpg` | 28 панфиловшылар атындағы саябақ (1982) | SkySex | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Commons](https://commons.wikimedia.org/wiki/File:Park_named_after_Panfilov%E2%80%99s_28_guardsmen,_1982_year.jpg) |
| `img/gorky_1980.jpg` | Горький атындағы мәдениет және демалыс саябағы (1980) | SkySex | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Commons](https://commons.wikimedia.org/wiki/File:Gorky_park,_Almaty_city,_1980_year.jpg) |
| `img/medeu_2010.jpg` | Медеу мұз айдыны, бөгеттен көрініс (2010) | Igors Jefimovs | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0) | [Commons](https://commons.wikimedia.org/wiki/File:Medeu_skating_stadium_view_from_dam_-_panoramio.jpg) |
| `img/medeu_2022.jpg` | Медеу мұз айдынының қасбеті (2022) | Key2xanadu | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Commons](https://commons.wikimedia.org/wiki/File:Medeu_-_rink_at_sunset_-_2022-06-21.jpg) |
| `img/memorial_2017.jpg` | Даңқ мемориалы, Панфиловшылар саябағы (2017) | Radosław Botev | [CC BY 3.0 pl](https://creativecommons.org/licenses/by/3.0/pl/deed.en) | [Commons](https://commons.wikimedia.org/wiki/File:WWII_Monument_Almaty.jpg) |
| `img/memorial_2019.jpg` | Даңқ мемориалының орталық бөлігі (2019) | Мазур Владимир | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Commons](https://commons.wikimedia.org/wiki/File:%D0%9F%D0%B0%D1%80%D0%BA_28_%D0%BF%D0%B0%D0%BD%D1%84%D0%B8%D0%BB%D0%BE%D0%B2%D1%86%D0%B5%D0%B2._%D0%9C%D0%B5%D0%BC%D0%BE%D1%80%D0%B8%D0%B0%D0%BB_%D0%A1%D0%BB%D0%B0%D0%B2%D1%8B_2019_34.jpg) |
| `img/cathedral_now.jpg` | Вознесенский (Зенков) соборы бүгін (2019) | Rudolph.A.furtado | [CC0](http://creativecommons.org/publicdomain/zero/1.0/deed.en) | [Commons](https://commons.wikimedia.org/wiki/File:Ascension_Cathedral_in_Almaty_in_Kazakhstan.JPG) |

Тарихи деректердің толық тізімі сайттың «Әдіснама» бөлімінде берілген.
