<img align="right" src="https://raw.githubusercontent.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/main/nabu.png" width="425" alt="Windows 11 Running On A Xiaomi Pad 5">

# Востановление из режима EDL на Xiaomi Pad 5

## Восстановление устройства в режиме EDL
> Это делается в крайнем случае, когда ваше устройство либо самостоятельно загружается только в режиме EDL, либо если вы не можете восстановить его другими способами

### Prerequisites
- Крипто-кошелек с 3 долларами USDT

- [Учетная запись в Telegram](https://telegram.org)

- [MiFlash HXRU Auth Tool](https://hxrutool.com)

- [Стандартный ПЗУ для fastboot](http://xmfirmwareupdater.com/miui/nabu/)

### Настройка инструмента HXRU
- Создайте учетную запись HRXU [тут](https://dashboard.hxrutool.com/Register)
- Загрузите **MiFlash HXRU Auth Tool** с домашней страницы
- Внутри **MiFlash_HXRU.rar** вы найдёте папку с файлом **PASS123.rar**, откройте его с паролем `123`
- Внутри этого защищенного архива находится папка с **MiFlash_HXRU.zip**. Извлеките ее содержимое куда-нибудь

### Покупка кредитов
> Свяжитесь с [@hxruofficial](https://t.me/hxruofficial) в Telegram, чтобы купить кредиты
> 
> Для перепрошивки вашего устройства с помощью этого инструмента вам понадобится **5** кредитов, что обойдётся примерно в **3$**

### Загрузка в режим EDL
> [!Note]
> Если вы уже находитесь в режиме EDL, пропустите этот шаг и перейдите к разделу «Перепрошивка устройства»
- Если ваш загрузчик разблокирован и у вас есть доступ к режиму fastboot, запустите ```fastboot oem edl``` для загрузки в режиме EDL

> Если ваш загрузчик заблокирован или Android не загружается и вы не можете получить доступ к режиму быстрой загрузки, вам нужно будет либо снять заднюю панель устройства, чтобы замкнуть контрольные точки EDL, либо использовать кабель EDL
>
> (Не все кабели EDL работают, и вы можете рискнуть и потратить деньги на тот, который не подойдёт, но это всё равно лучше, чем разбирать устройство)
- Ищите кабель с пометкой **V2** в названии, например **Hydra V2 EDL Cable** или **V2 EDL Pro Cable**. Убедитесь, что он предназначен для устройств с разъёмом USB-C
- Вставьте кабель в устройство, затем нажмите кнопку на кабеле, которая может выглядеть [так](https://t.me/nabuwoa/204867)
- Теперь вы должны перейти в режим EDL

### Установка драйверов EDL
> Если устройство в **Диспетчере устройств** называется **QUSB_BULK_CID** или имеет жёлтый треугольник с предупреждением / вопросительный знак ⚠️ и находится в любой другой категории (например, **Другие устройства**), сначала необходимо установить драйверы EDL
- Чтобы установить драйверы EDL, извлеките содержимое [QUD.zip](https://github.com/n00b69/woa-betalm/releases/download/Qfil/QUD.zip) куда-нибудь, щёлкните правой кнопкой мыши по **QUSB_BULK_CID**, выберите «Обновить драйвер» и «Найти драйверы на компьютере», затем найдите и выберите папку **QUD**.

### Перепрошивка устройста
- Откройте **XiaoMiFlash.exe** и предоставьте права администратора (просто запустите эту программу от имени администратора).
- Скачайте стандартный образ fastboot для вашего устройства (он должен иметь расширение .tgz) и откройте его. Внутри должен быть файл .tar. Извлеките содержимое этого файла .tar в любую папку).
- Нажмите кнопку **select** в **XiaoMiFlash** и выберите эту папку.
- Нажмите **flash**.
- Если вы получили сообщение об ошибке «write time out», удерживайте кнопку **питания** + **уменьшения громкости** в течение +- 30 секунд, чтобы перезагрузить EDL. После этого снова нажмите кнопку **flash**.
- Через несколько секунд должно появиться всплывающее окно для входа в систему. Введите здесь данные своей учётной записи HRXU и нажмите **Request Auth Flashing**.
- После того как появится надпись « **flash done** », перезагрузите устройство, удерживая кнопку **питания** +- 14 секунд.

### Перепрошивка вашего ПЗУ с помощью MiFlash
> [!Important]
> Этот инструмент позволяет установить прошивку только в один слот. Если ваше устройство когда-либо переключится между слотами, оно снова загрузится в EDL.
- Перезагрузитесь в режим fastboot.
- Во второй раз обновите прошивку fastboot с помощью **MiFlash** или файла **flash_all.bat** в прошивке.
- Перезагрузитесь после того, как прошивка закончится.

## Готово!