<img align="right" src="https://raw.githubusercontent.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/main/nabu.png" width="425" alt="Windows 11 Running On A Xiaomi Pad 5">

# Запуск Windows на Xiaomi Pad 5

## Безпроблемне подвійне завантаження Android і Windows 

### Передумови 
- Мозок 
- Root права 
- Встановлена Windows на планшеті
- [UEFI image](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/tag/UEFI)
- [WoA Helper app](https://github.com/Marius586/WoA-Helper-update/releases/tag/WOA)
- [StA Installer](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/download/dualboot/StA_Installer_nabu.exe)

### Налаштування подвійного завантаження  
> У цьому посібнику передбачається, що ви маєте root права, якщо ні, дотримуйтесь інструкцій з [отримання root доступу](2-rootguide-uk.md).

### Налаштування у Android
> [!NOTE]
> Якщо ви не можете перемістити файли до папки Windows, це означає, що ви вимкнули Windows, а не перезавантажили її. Щоб вирішити цю проблему, завантажте Windows і скористайтеся перезапуском, а потім, коли він перезавантажиться, завантажте швидке завантаження та скористайтеся ним, щоб повернутися до Android. 

- Завантажте та встановіть додаток WoA Helper, а потім відкрийте його та надайте йому root доступ.
- Завантажте **UEFI image** and помістіть його в папку під назвою `UEFI` у вашій внутрішній пам'яті; якщо ця папка не існує, створіть її.
- Натисніть кнопку `МОНТУВАННЯ WINDOWS`, потім завантажте та перемістіть **StA_Installer_nabu.exe** у щойно створену папку `Windows` у вашій внутрішній пам’яті. 
- Поверніться до програми WoA Helper і натисніть `ШВИДКЕ ЗАВАНТАЖЕННЯ В WINDOWS`.

### Налаштування у Windows
- Перейдіть до `C:\StA_Installer_nabu.exe` та запустіть його. Якщо це не працює, переконайтеся, що будь-яке антивірусне програмне забезпечення вимкнено, оскільки воно, ймовірно, не дозволить запустити програму. 

#### Завантаження Android 
- Запустіть новий ярлик на робочому столі (ви також можете закріпити його в меню «Пуск»/панелі завдань для зручності доступу).

#### Завантаження Windows
- Натисніть `ШВИДКЕ ЗАВАНТАЖЕННЯ В WINDOWS` у програмі або скористайтеся новоствореним перемикачем на панелі швидких налаштувань.
  
## Готово!
