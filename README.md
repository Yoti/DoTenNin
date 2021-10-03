# DoTenNin
DoTenNin -- однокнопочная утилита для создания своих сборок кастома для N Switch

***Основные возможности:***
* Автоматическая загрузка последней релизной версии [hekate](https://github.com/CTCaer/hekate)
* Копирование настроенного файла `hekate_ipl.ini` из папки с программой
* Создание из `hekate.bin` файлов `boot.dat` и `payload.bin` для консолей с чипом
* Автоматическая загрузка последней релизной версии [Lockpick_RCM](https://github.com/shchmue/Lockpick_RCM)
* Опциональная загрузка последней релизной версии [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer)
* Автоматическая загрузка последней релизной версии [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)
* Автоматическая загрузка последней доступной версии [sig. patches](https://github.com/ITotalJustice/patches)
* Автоматическая загрузка последней релизной версии [DBI](https://github.com/rashevskyv/dbi)

***Дополнительные возможности:***
* Отдельная папка с уникальным именем, состоящим из даты и времени, для каждой новой сборки
* Создание набора выбранных файлов (из `hekate`, `Lockpick_RCM` и `TegraExplorer`) для RCMloader
* Создание текстового документа (под именем `readme.txt`) со всеми версиями загруженных файлов

***Внешний вид текущей версии:***

![image.png](image.png?raw=true "image.png")

***Список изменений (changelog):***
* Изменена координата появления окна программы
* Удаление пустых папок из папки RCMloader
* Исправлена обработка минимальной высоты окна
* Копирование reboot_payload.bin как fusee.bin
* Добавление пользовательских файлов поверх:
  * bootloader\ini\*.ini
  * bootloader\res\*.bmp
