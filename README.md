# GTA SA for Hitmans' Agency

Как скачать: Кликайте на архив справа, в разделе Release

Готовая "сборка" для только вступивших агентов, ещё не познавших всю прелесть симулятора ожидания aka Агентства Наёмных убийц на GalaxY RPG. Здесь собрано всё, что нужно хитману для комфортной работы. Рассчитано на мониторы с разрешением 1920х1080, если у вас другое - нужно будет немного настроить под себя.

ВНИМАНИЕ: Использование скриптов, связанных с работой хитманов, будучи кикнутыми из Агентства - приведут к бану вашего аккаунта.

# Что нужно для запуска?

Microsoft Visual C++ Redistributable: 
- для 32bit систем -  https://aka.ms/vs/16/release/vc_redist.x86.exe
- для 64bit систем -  https://aka.ms/vs/16/release/vc_redist.x64.exe

# Что внутри?

- Чистый образ GTA SA с форума GalaxY-RPG
- GTA_SA.exe 1.0 US
- Cleo 4.4.0
- SAMPFUNCS 5.4.1
- Moonloader 027.0-preview3

## CLEO:
- Car Speed FPS Fix.cs (Необходим для FPS Unlock'а, возвращает корректное ускорение и торможение транспорта)
- HUDfix.cs (Убирает нули у $ в hud'е)
- memory.cs (Увеличивает буфер памяти, используемый игрой, настройки хранятся в memory.ini)
- OffRadio.cs (Отключает игровое радио в транспорте)
- SniperZoom.cs (Позволяет включить увеличенный зум у снайперской винтовки. По умолчанию Y - зум+, H - зум-, настройки хранятся в sniperZoom.ini)

## SF:
- Chatlog.sf (Сохраняет чат-логи по датам в папку \Documents\GTA San Andreas User Files\SAMP\chatlog)
- sampfuncs-settings.ini (Запускает игру в оконном режиме, оптимизировано для работы с твинка в отсутствие детективов, не перекрывает другие окна и приложения, пока находится вне фокуса)

## LUA:
- BetterPortable_v1.2.1.luac - Моя замена списка /portable (**/ptb** - Включение/выключение замены списка, по умолчанию включено)
> Показывает фракцию и ранг игрока; ник светится зелёным, если находится в зоне стрима; кнопка переключения страниц перенесена на первую строку; выделяет цветом заказы на сумму выше 10.000$; показывает, если игрок был убит, когда вы открыли список
- BufferCleanerAuto.lua - Автоматически очищает буфер памяти при достижении 80% из доступной
- BulletTrack.luac - Трассера пуль, как своих, так и игроков (**/btrack** - настройки скрипта)
- camhackww.lua - Камхак с обходом варнингов (**/camhackww** - настройки скрипта)
> По умолчанию включение на **Z+1**, выключение на **Z+2**, клавиши можно переназначить в настройках
- Checker.luac - Чекер игроков от Dima_Fax (**/checker** - настройки скрипта)
> Настроено 3 из 5 доступных списков: Хитманы, Детективы, Чёрный список; **/cadd [номер списка] [ID]** - добавить игрока в указанный список; **/crem [номер списка] [ID]** - удалить игрока из указанного списка (Пример: /cadd 1 123)
- Checker_All_Online.lua
- comfortableAiming.lua
- Contract_Position_with_lines.lua
- EnterToChat.lua
- fuck_clouds.luac
- fogdist.lua
- Hitman_Manager-prot.luac
- InputHelper.lua
- PM Manager.luac
- reload_all.lua
- SA_Bind-prot.luac
- sensfix.luac
- setWeather_Time
- SplitString.lua
- TimerDrugs.luac
- WeaponHandFix.lua

## ASI:
- anticrasher037.asi
- FPSUnlockRXByDarkP1xel.asi
- Fastmap.asi
- mousefix.asi
- radarrect.asi
- Screenshot.asi
- Swim FPS Fix.asi

## По мелочи:
- HQ иконки оружия и радара
- Удалена крыша у Infernus и Sultan
- 
