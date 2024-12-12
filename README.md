in short, the general design has been slightly changed, the background in the direct connect tab, some localizations have been added


the list of changes was compiled crookedly for myself, so to speak

------------
locales-ru(en) "BeamMP-development\mp_locales\ru_RU.json" - line 4 added localization "ui.mainmenu.mod" above the multiplayer button, line 91 added localization "ui.multiplayer.add.favorite" save to favorites, line 106 added localization "ui.multiplayer.patreon.message.user"
line 107 added localization "ui.multiplayer.patreon.
button.user"


styles for the server menu - "BeamMP-development\ui\modModules\multiplayer\multiplayer.css" - lines 10-11, 16-17, 36-68 - more transparent style..


"direct connection" tab - "BeamMP-development\ui\modModules\multiplayer\multiplayer.css" - lines 50-64 - transparent background, auto width of the "paste from clipboard" button
line 157-
161 changed the width of the “connect” button from 425px to 400px, line 163-167 changed the width of the “save to favorites” button to auto

"BeamMP-development\ui\modModules\multiplayer\direct.partial.html" - line 2 (class "direct-connect" added, style removed), 6 (class "paste-from-clipboard-but" added, class "servers" removed -
button" and "button" styles from these classes are added to "paste-from-clipboard-but")
line 11 changed "translate" from "{{:: 'ui.multiplayer.favorite' | translate}}" to "{{:: 'ui.multiplayer.add.favorite' | translate}}"


"BeamMP-development\ui\modModules\multiplayer\login.partial.html" - line 1 background color changed
lines 11,12,
13 added classes "multiplayer-login-btn", "multiplayer-play-guest-btn", "multiplayer-register-btn"
line 11 - style removed (margin-left0)
line 13 - style removed (margin-right0)
line 10 - added the "login-button-block" class, removed the styles and moved them to "multiplayer.css"
"BeamMP-development\ui\modModules\multiplayer\multiplayer.css" -
added appropriate styles, lines 34-46
lines 48-53 moved styles ----- the total width of the buttons is equal to the width of the text



ssd















----------------------------



ru


locales-ru(en) "BeamMP-development\mp_locales\ru_RU.json" - строка 4 добавлена локализация "ui.mainmenu.mod" над кнопкой мультиплеера, строка 91 добавлена локализация "ui.multiplayer.add.favorite" созранить в избранное, строка 106 добавлена локализация "ui.multiplayer.patreon.message.user"
строка 107 добавлена локализация "ui.multiplayer.patreon.button.user"


стили для меню серверов - "BeamMP-development\ui\modModules\multiplayer\multiplayer.css" - строки 10-11, 16-17, 36-68 - более прозрачный стиль ..


вкладка "прямое подключение" - "BeamMP-development\ui\modModules\multiplayer\multiplayer.css" - строки 50-64 - прозрачный фон, авто ширина кнопки "вставить из буфера обмена"
строка 157-161 изменена ширина кнопки "подключится" с 425px на 400px, строка 163-167 изменена ширина кнопки "сохранить в избранное" на авто

"BeamMP-development\ui\modModules\multiplayer\direct.partial.html" - строка 2(добавлен класс "direct-connect" убран стиль), 6(добавлен класс "paste-from-clipboard-but", убран класс "servers-button" и "button" стили из этих классов добавлены в "paste-from-clipboard-but")
строка 11 изменена "translate" с "{{:: 'ui.multiplayer.favorite' | translate}}" на "{{:: 'ui.multiplayer.add.favorite' | translate}}"


"BeamMP-development\ui\modModules\multiplayer\login.partial.html" - строка 1 изменен цвет фона
строки 11,12,13 добавленны классы "multiplayer-login-btn", "multiplayer-play-guest-btn", "multiplayer-register-btn"
строка 11 - убран стиль(margin-left0)
строка 13 - убран стиль(margin-right0)
строка 10 - добавлен класс "login-button-block" убраны стили и перемешенны в "multiplayer.css"
"BeamMP-development\ui\modModules\multiplayer\multiplayer.css" - добавленны соответствующие стили, строки 34-46
строки 48-53 перемещенные стили ----- итог ширина кнопок равна ширине такста



ssd
