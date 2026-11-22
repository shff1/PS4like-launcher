# PS4 Launcher

**Лаунчер игр для Windows в стиле PS4** · **A PS4-style game launcher for Windows**

[Русский](#русский) · [English](#english)

**Статус:** это витрина проекта — исходный код пока не опубликован. · **Status:** this is a project showcase — the source code is not public yet.

> **Это не эмулятор PS4.** Лаунчер запускает обычные Windows-игры.
> **Not a PS4 emulator.** It launches regular Windows games.

![Домашний экран PS4 Launcher с волной PS4 7.00](screenshots/wave-home-2026-11-22.jpg)

## Волна PS4 7.00 — 1:1 · The wave, recreated 1:1

**Русский.** Фон лаунчера собран из оригинальных ресурсов PS4 7.00: сетка на 9 664 вершины и 17 458 треугольников, 96 костей, позы и траектория камеры, палитры Boot/Login и Home/System. Рендер — WebGL2: фон, depth-prepass и два прохода прозрачности; полный цикл — 266,67 секунды. Волна просыпается под чёрной заставкой, живёт на приветствии и в библиотеке и замирает в игре.

**English.** The background is built from the original PS4 7.00 assets: a 9,664-vertex, 17,458-triangle mesh, 96 bones, poses and a camera path, plus the Boot/Login and Home/System palettes. Rendering is WebGL2 with a background pass, a depth prepass and two transparency passes; the full loop is 266.67 seconds. The wave wakes up under the black splash screen, lives on the welcome screen and in the library, and pauses in game.

| Приветствие · Welcome | Движение · Motion |
|:---:|:---:|
| ![Волна на экране приветствия](screenshots/wave-welcome-2026-11-22.jpg) | [![Смотреть волну](screenshots/ps4-wave-poster-2026-11-22.jpg)](screenshots/ps4-wave-2026-11-22.mp4) |

*Клик по кадру — короткий ролик волны, 12 секунд без звука. · Click the frame for a 12-second silent wave clip.*

## Скриншоты / Screenshots

**Заставка и волна · Boot & wave**

| Заставка · Boot splash | Волна на приветствии · Welcome wave |
|:---:|:---:|
| ![Заставка](screenshots/09-boot.png) | ![Волна](screenshots/wave-welcome-2026-11-22.jpg) |

**Страница игры · Game page**

| The Last of Us™ Part II | The Last of Us Remastered |
|:---:|:---:|
| ![Страница игры](screenshots/11-game-page-tlou2.jpg) | ![Страница игры](screenshots/12-game-page-tlou1.jpg) |

**Меню Options · Options menu**

| Меню Options |
|:---:|
| ![Меню Options](screenshots/13-options-menu.jpg) |

**Добавление игры · Adding a game**

| Выбор файла · File browser | Поиск издания · Edition search |
|:---:|:---:|
| ![Выбор файла](screenshots/14-add-game-file.jpg) | ![Поиск издания](screenshots/15-add-game-edition.jpg) |

| Экран поиска · Search screen | Экран добавления · Adding |
|:---:|:---:|
| ![Экран поиска](screenshots/16-add-game-search.jpg) | ![Экран добавления](screenshots/17-add-game-loading.jpg) |

**Обложки и фоны · Covers & backgrounds**

| Источник обложки · Cover source | Галерея обложек · Cover picker |
|:---:|:---:|
| ![Источник обложки](screenshots/18-cover-source.jpg) | ![Галерея обложек](screenshots/19-cover-picker.jpg) |

| Источник фона · Background source | Галерея фонов · Background picker |
|:---:|:---:|
| ![Источник фона](screenshots/20-background-source.jpg) | ![Галерея фонов](screenshots/21-background-picker.jpg) |

**Уведомления · Notifications**

| История · History | Всплывающая плашка · Toast |
|:---:|:---:|
| ![Уведомления](screenshots/22-notifications.jpg) | ![Плашка](screenshots/23-notification-toast.jpg) |

| Верхний ряд функций · Function row |
|:---:|
| ![Верхний ряд](screenshots/24-function-row.jpg) |

**Профиль и контроллер · Profile & controller**

| Профиль · Profile | Аватары · Avatars |
|:---:|:---:|
| ![Профиль](screenshots/25-profile.jpg) | ![Аватары](screenshots/26-avatar-picker.jpg) |

| Меню профиля и контроллера · Profile & controller menu |
|:---:|
| ![Меню профиля](screenshots/27-profile-menu.jpg) |

**Системные страницы · System pages**

| Звук · Sound | Дисплей · Displays |
|:---:|:---:|
| ![Звук](screenshots/28-sound.jpg) | ![Дисплей](screenshots/29-display.jpg) |

| Запуск · Startup | Питание · Power |
|:---:|:---:|
| ![Запуск](screenshots/30-startup.jpg) | ![Питание](screenshots/31-power.jpg) |

**Темы · Themes**

| Выбор темы · Theme picker |
|:---:|
| ![Выбор темы](screenshots/32-themes-2026.jpg) |

**«Что нового» · What's New**

| Лента · Feed | Хаб новинки · Release hub |
|:---:|:---:|
| ![Что нового](screenshots/04-whats-new-2026.jpg) | ![Хаб новинки](screenshots/05-whats-new-hub.jpg) |

| Просмотр скриншотов · Screenshot viewer |
|:---:|
| ![Просмотр скриншотов](screenshots/06-screenshot-viewer.jpg) |

---

## Русский

### О проекте

PS4 Launcher — личный проект: домашний экран PlayStation для Windows-игр. Это не эмулятор и не замена консоли — просто уютная оболочка, в которой игры запускаются с геймпада, с обложками, описаниями и знакомыми звуками. Хочется включить компьютер, сесть на диван и на пару секунд поверить, что это та самая приставка.

За последнее время лаунчер вырос из ленты обложек в полноценную оболочку: у игр появились страницы со сведениями и статистикой, добавились профиль, уведомления, темы, звук, дисплеи и настройки Windows — всё в стиле PS4.

Интерфейс и описания — на русском.

### Что нового

**22 ноября 2026 — волна 1:1**

- **Волна из оригинальных данных PS4 7.00.** Геометрия, 96 костей, позы, камера и палитры Boot/Login и Home/System — 1:1. Рендер — WebGL2 с depth-prepass и двумя проходами прозрачности.
- **Плавный запуск и пауза.** Первый кадр готовится под чёрной заставкой, движение включается с раскрытием; на приветствии и в библиотеке волна живёт, в игре замирает.
- **Свежая «Что нового».** Лента переведена на PSN: новинки, хиты и карточки игр.

**20 ноября 2026**

- **Добавление игры внутри лаунчера.** Файловый браузер по дискам, поиск издания в PS Store (с резервным IGDB для PC-игр), выбор источника метаданных и системный экран ожидания в стиле PS4. Название, обложка, фон и описание подтягиваются автоматически.
- **Кеш при добавлении игры.** Миниатюры изданий в результатах поиска — только HTTP-кеш, на диск не сохраняются. Выбранные обложка и фон скачиваются один раз в версионированный кеш, из которого готовятся производные под экран; повторные открытия и выборы переиспользуют готовые файлы, а невостребованное убирает управляемый сборщик мусора.
- **Новая страница игры.** Разделы «Обзор» и «Сведения», жанры, разработчик и издатель, переведённые описания, время в игре и дата последнего запуска.
- **Меню Options на главном экране.** Избранное, переименование, выбор обложки, выбор фона, параметры запуска и удаление из библиотеки.
- **Обложки и фоны из двух источников.** PS Store и IGDB, галереи с отметкой «Установлен».
- **Уведомления.** Всплывающие плашки, история, счётчик непрочитанных и звуки — в том числе для добавления игры и подключения геймпада.
- **Профиль.** Имя, аватар и пять последних аватаров; добавление картинки с компьютера и собственная экранная клавиатура.
- **Системные страницы в стиле PS4.** «Звук» (музыка и звуки интерфейса, устройство вывода Windows), «Дисплей» (режим отображения и монитор лаунчера), «Запуск» (автозапуск с Windows и экспериментальное глушение проводника: explorer.exe временно завершается, отдельный сторож возвращает рабочий стол и панель задач) и «Питание» (выключение, перезапуск, сон, выход).
- **Верхний ряд функций.** «Добавить игру», «Уведомления», «Звук», «Дисплей», «Профиль», «Темы», «Запуск» и «Питание» — как на домашнем экране PS4.
- **Геймпады.** Подключение и отключение на лету, Xbox-совместимые геймпады и виртуальные DualShock 4, вход по кнопке PS/Home на экране приветствия. Мой контроллер подключается через мою отдельную внешнюю программу — встроенного моста в лаунчере нет.
- **Только клавиатура и геймпад.** Мышь, тачпад и касания намеренно не управляют интерфейсом — так сохраняется консольное ощущение.
- **Переходы и списки.** Кроссфейды страниц, кадент автоповтора прокрутки, рамка фокуса строки с коротким следом, вуаль у обеих кромок списка и кроссфейд каталогов при входе в папку.
- **Темы.** Страница выбора в стиле PS4 с JPEG-превью карточек и плавным переключением; видео всегда без звука.

### Что умеет

- **Знакомое начало.** Чёрная заставка с логотипом, экран «С возвращением в PlayStation», живая волна на фоне, музыка и вход по кнопке PS — или с клавиатуры.
- **Библиотека.** Горизонтальная лента обложек; выбранная игра плавно увеличивается. Любимые игры можно поднять в начало, а новые — добавить прямо из лаунчера.
- **Добавление игры.** Лаунчер открывает собственный файловый браузер, показывает диски и папки, принимает EXE-файл и предлагает издания из PS Store или IGDB. Дальше — экран ожидания, автоматический подбор обложки, фона и описания, уведомление и место в библиотеке.
- **Кеширование изображений.** Миниатюры в результатах поиска изданий показываются из HTTP-кеша и на диск не сохраняются. После подтверждения обложка и фон скачиваются один раз и попадают в версионированный кеш: оригинал хранится по SHA-256, а из него готовятся производные под экран — обложка 512 px, фон до 2560 px, при необходимости 1080p/1440p/4K. Повторный выбор и открытие страниц берут готовый файл без новой загрузки и перекодирования; у игры одна сохранённая обложка, а ручной выбор никогда не перезаписывается автоматическим. Незавершённая запись восстанавливается по журналу транзакций, а невостребованные ресурсы после смены фона или удаления игры удаляет управляемый сборщик мусора — с задержкой 10 минут и только внутри собственного каталога кеша.
- **Страница игры.** Обложка, арт, описание, жанры, разработчик, издатель и дата выхода; время в игре и последний запуск. Кнопка «Запуск» и меню Options — рядом.
- **Меню Options.** Добавить в избранное, переименовать, выбрать обложку, выбрать фон, настроить параметры запуска (EXE, аргументы, рабочая папка, фильтр папок) или удалить игру из библиотеки.
- **Обложки и фоны.** Два каталога источников — PS Store и IGDB; выбранный вариант помечается «Установлен» и сохраняется.
- **«Что нового».** Обновления ваших игр, хиты месяца и то, что скоро выйдет. У каждой новинки — описание, детали и скриншоты, которые открываются на весь экран.
- **Уведомления.** Плашки о добавлении игры, подключении и отключении контроллера и системных событиях; отдельный экран истории и голубой счётчик непрочитанных.
- **Профиль.** Экран с именем и аватаром. Хранятся пять последних аватаров: шестой вытесняет самый старый, а изображение остаётся в профиле даже после удаления исходного файла.
- **Темы.** Положите видео в папку `themes` — оно появится в каталоге с превью. Заставка и приветствие остаются с волной: тема включается при входе в библиотеку. Видео всегда без звука.
- **Звук.** Отдельные уровни для музыки и звуков интерфейса, выбор устройства вывода Windows. Некоторые запущенные игры могут потребовать перезапуска после смены устройства.
- **Дисплеи.** Режимы «Только основной», «Дублировать», «Расширить» и «Только второй», а также выбор конкретного монитора для лаунчера. Выбор сохраняется после перезапуска.
- **Запуск.** Автозапуск при входе в Windows и экспериментальное скрытие рабочего стола: лаунчер временно завершает только процесс оболочки explorer.exe (открытые окна папок перед этим закрываются), а отдельный процесс-сторож автоматически возвращает рабочий стол и панель задач после выхода, падения или зависания лаунчера. Dirty-маркер переживает двойной сбой, и тогда рабочий стол возвращается вручную через диспетчер задач. Реестр и политики Windows не меняются; замена системной оболочки пока недоступна — возможность изучается.
- **Питание.** Выключение, перезапуск, спящий режим и выход из лаунчера на рабочий стол Windows.
- **Запуск и возврат.** Лаунчер запускает игру, находит её окно и возвращает фокус после выхода; время игры считается само, а музыка на старте становится тише.
- **Управление.** Геймпады подключаются и отключаются на лету; поддерживаются Xbox-совместимые геймпады и виртуальные DualShock 4 от отдельной внешней программы для моего контроллера — встроенного моста в лаунчере нет. Подсказки внизу подстраиваются под клавиатуру или геймпад; мышь и касания намеренно не управляют интерфейсом.
- **Переходы.** Открытие страниц и системных экранов — PS4-кроссфейды; вертикальные списки листаются в каденте, строки гаснут у обеих кромок, а рамка фокуса остаётся на строке.
- **Волна.** Фон из оригинальных ресурсов PS4 7.00: 9 664 вершины, 96 костей, палитры Boot/Login и Home/System. Волна живёт на приветствии и в библиотеке и замирает в игре.

### Технологии

Python и pywebview (WebView2), интерфейс — HTML/CSS/JS. Волна — WebGL2 на оригинальных данных PS4 7.00 (openPS4-shell, MIT). Метаданные и изображения — PS Store, IGDB, Steam и SteamGridDB. Windows 10/11.

### Статус

Личный некоммерческий проект. Исходный код пока не опубликован: здесь только витрина со скриншотами и рассказом о том, что уже работает. Интерфейс на русском.

### В планах

- Замена системной оболочки Windows — возможность изучается.
- Поддержка разных разрешений и масштабирования Windows.
- Отдельная сборка с установщиком.
- Дальнейшая полировка переходов и работа с большими библиотеками.

### Дисклеймер

Проект не связан с Sony Interactive Entertainment и не одобрен ею. PlayStation — торговая марка Sony. Это не эмулятор PS4. Обложки, арты и звуки принадлежат их правообладателям и используются только для оформления личного некоммерческого проекта. Перед публикацией готовой сборки права на эти материалы нужно проверить отдельно.

---

## English

### About

PS4 Launcher is a personal project: a PlayStation home screen for Windows games. It is not an emulator or a console replacement — just a cozy shell where games launch with a gamepad, covers, descriptions and familiar sounds. The idea is to turn on the PC, sit back on the couch and, for a second, believe it is the real thing.

The launcher has grown from a row of covers into a full shell: games now have pages with details and play stats, and there is a profile, notifications, themes, sound, displays and Windows settings — all in the PS4 spirit.

The interface and descriptions are in Russian.

### What's new

**November 22, 2026 — the 1:1 wave**

- **The wave from the original PS4 7.00 assets.** Geometry, 96 bones, poses, camera and the Boot/Login and Home/System palettes — 1:1. Rendering is WebGL2 with a depth prepass and two transparency passes.
- **A smooth start and a pause.** The first frame is prepared under the black splash screen and motion begins with the reveal; the wave lives on the welcome screen and in the library and pauses in game.
- **A fresh What's New.** The feed now runs on PSN: new releases, hits and game pages.

**November 20, 2026**

- **Adding games inside the launcher.** A file browser across drives, edition search in the PS Store (with IGDB fallback for PC games), a metadata source choice and a PS4-style system loading screen. Title, cover, background and description are picked up automatically.
- **Image caching.** Edition thumbnails in search results come from the HTTP cache and are never written to disk. Once you confirm, the cover and background are downloaded once into a versioned cache: the original is stored by SHA-256 and derivatives are prepared for the screen; reopening pages and picking again reuse the prepared files, and unused assets are cleaned up by a managed garbage collector.
- **A new game page.** "Overview" and "Details" sections, genres, developer and publisher, translated descriptions, play time and last launch date.
- **Options menu on the home screen.** Favorite, rename, choose cover, choose background, launch options and remove from library.
- **Covers and backgrounds from two sources.** PS Store and IGDB galleries, with the selected item marked "Installed".
- **Notifications.** Toasts, history, an unread counter and sounds — including for game additions and controller connections.
- **Profile.** Name, avatar and the five most recent avatars; add an image from your computer using the built-in on-screen keyboard.
- **PS4-style system pages.** "Sound" (music and interface volume, Windows output device), "Displays" (display mode and the launcher's monitor), "Startup" (start with Windows and an experimental Explorer shutdown: explorer.exe is terminated temporarily while a separate guard brings the desktop and taskbar back) and "Power" (shut down, restart, sleep, exit).
- **Top function row.** "Add game", "Notifications", "Sound", "Displays", "Profile", "Themes", "Startup" and "Power" — like the PS4 home screen.
- **Gamepads.** Connect and disconnect on the fly, Xbox-compatible pads and virtual DualShock 4 pads, and PS/Home button entry on the welcome screen. My controller connects through my own separate external program — the launcher has no built-in bridge.
- **Keyboard and gamepad only.** Mouse, touchpad and touch input deliberately do not control the interface — it keeps the console feel.
- **Transitions and lists.** Page crossfades, scroll auto-repeat cadence, a focus frame with a short trail, edge fades on both sides of a list and catalog crossfades when entering a folder.
- **Themes.** A PS4-style theme picker with JPEG previews and smooth switching; videos are always muted.

### What it does

- **A familiar welcome.** Black boot splash with the logo, a "Welcome back to PlayStation" screen, a living wave in the background, music and the PS button to enter — or just use the keyboard.
- **Library.** A horizontal row of covers; the selected game grows smoothly. Favorites can be moved to the front, and new games can be added right from the launcher.
- **Adding a game.** The launcher opens its own file browser, shows drives and folders, accepts an EXE file and offers editions from PS Store or IGDB. Then comes the loading screen, automatic cover, background and description selection, a notification and a spot in the library.
- **Image caching.** Thumbnails in edition search results are served from the HTTP cache and never saved to disk. Once confirmed, the cover and background are downloaded once into a versioned cache: the original is stored by SHA-256 and derivatives are prepared for the screen — a 512 px cover, a background up to 2560 px and, when needed, 1080p/1440p/4K. Reopening pages or picking again reuses the prepared files with no re-download or re-encode; each game keeps one saved cover, and a manual choice is never overwritten by an automatic one. An interrupted write is restored from the transaction journal, and unused assets after a background change or game removal are cleaned up by a managed garbage collector — with a 10-minute grace and only inside its own cache folder.
- **Game page.** Cover, art, description, genres, developer, publisher and release date; play time and the last launch. The "Launch" button and the Options menu are right here.
- **Options menu.** Add to favorites, rename, choose a cover, choose a background, set launch options (EXE, arguments, working directory, folder filter) or remove the game from the library.
- **Covers and backgrounds.** Two source catalogs — PS Store and IGDB; the chosen option is marked "Installed" and saved.
- **What's New.** Updates for your games, recent hits and upcoming releases. Each release has its own page with details and screenshots that open full screen.
- **Notifications.** Toasts for game additions, controller connections and disconnections and system events; a separate history screen and a blue unread counter.
- **Profile.** A screen with a name and an avatar. The five most recent avatars are kept: the sixth replaces the oldest, and the image stays in the profile even if the source file is deleted.
- **Themes.** Drop a video into the `themes` folder and it appears in the catalog with a preview. The splash and welcome screen stay with the wave; your theme starts when you enter the library. Videos are always muted.
- **Sound.** Separate levels for music and interface sounds, plus a Windows output device choice. Some running games may need a restart after switching the device.
- **Displays.** "Primary only", "Duplicate", "Extend" and "Second only" modes, plus choosing a specific monitor for the launcher. The choice survives a restart.
- **Startup.** Start with Windows, and an experimental desktop-hide mode: the launcher temporarily terminates only the explorer.exe shell (open folder windows are closed first), while a separate guard process automatically brings the desktop and taskbar back after the launcher exits, crashes or hangs. A dirty marker covers a double failure, with a manual explorer.exe start from Task Manager. The Windows registry and policies are not modified; replacing the system shell is not available yet — it is being explored.
- **Power.** Shut down, restart, sleep and exit the launcher to the Windows desktop.
- **Launch and return.** The launcher starts the game, finds its window and restores focus after you exit; play time is tracked automatically, and the music gets quieter on launch.
- **Controls.** Gamepads connect and disconnect on the fly; Xbox-compatible pads and virtual DualShock 4 pads from a separate external program for my controller are supported — there is no built-in bridge in the launcher. Hints at the bottom follow the keyboard or gamepad; mouse and touch deliberately do not control the interface.
- **Transitions.** Pages and system screens open with PS4 crossfades; vertical lists scroll at a cadence, rows fade at both edges, and the focus frame stays on its row.
- **The wave.** A background built from the original PS4 7.00 assets: a 9,664-vertex mesh, 96 bones and the Boot/Login and Home/System palettes. It lives on the welcome screen and in the library, and pauses in game.

### Tech

Python and pywebview (WebView2); the interface is HTML/CSS/JS. The wave is WebGL2 running on the original PS4 7.00 assets (openPS4-shell, MIT). Metadata and images come from PS Store, IGDB, Steam and SteamGridDB. Windows 10/11.

### Status

Personal non-commercial project. Source code is not public yet: this is just a showcase with screenshots and a story about what already works. The interface is in Russian.

### Roadmap

- Replacing the Windows system shell — being explored.
- Support for different resolutions and Windows scaling.
- A separate build with an installer.
- Further polish for transitions and work with large libraries.

### Disclaimer

This project is not affiliated with or endorsed by Sony Interactive Entertainment. PlayStation is a trademark of Sony. It is not a PS4 emulator. Game artwork and audio belong to their respective owners and are used only for this personal, non-commercial project. Before any build is published, the rights to these materials need to be checked separately.
