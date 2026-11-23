---
title: DuPanel — Privacy Policy
---

# DuPanel — Политика конфиденциальности / Privacy Policy

Дата вступления в силу / Effective date: 24 ноября 2026 / November 24, 2026
Разработчик / Developer: Umed SAIDOV · Контакт / Contact: hotbynow@gmail.com

---

## Русский

**DuPanel** — двухпанельный файловый менеджер для Android. Эта политика объясняет, какие данные использует приложение.

### Какие данные мы собираем
**Никаких.** Приложение не собирает, не передаёт и не продаёт персональные данные. В нём нет рекламы, аналитики, отчётов о сбоях, проверки обновлений, учётных записей и сторонних SDK для сбора данных. Разработчик не получает никаких сведений о вас или ваших файлах.

### Файлы на устройстве
Приложение запрашивает разрешение **«Доступ ко всем файлам»** (MANAGE_EXTERNAL_STORAGE; на Android 10 и более ранних версиях — разрешения на чтение и запись памяти), потому что его основная функция — просмотр, копирование, перемещение, переименование, упаковка в ZIP и удаление файлов и папок во внутренней памяти, на SD-карте и USB-накопителях. Все действия выполняются на вашем устройстве и только по вашей команде. Файлы покидают устройство только когда вы сами копируете их на подключённый вами сервер или передаёте в другое приложение («Поделиться», «Открыть с помощью»). Разработчик их не получает.

### Сетевые подключения
Приложение выходит в сеть **только** для связи с серверами, которые вы сами указываете (SMB, FTP/FTPS, SFTP), — например, с вашим роутером, NAS или хостингом. Данные передаются напрямую между вашим устройством и этим сервером, без участия разработчика. Чтобы не вводить данные повторно, на устройстве сохраняются адрес сервера, порт, общая папка, имя пользователя и путь к файлу ключа SSH (если вы его указали), а также отпечатки ключей и сертификатов серверов, которым вы решили доверять. **Пароли и пароли ключей SSH не сохраняются**: они хранятся только в памяти, пока открыто соединение. Сам файл ключа SSH приложение не копирует — читает его по указанному пути при подключении. При обычном FTP (без TLS) пароль и файлы передаются без шифрования; для защищённой передачи используйте FTPS или SFTP.

### Другие приложения
Чтобы показать «Избранные приложения» и открыть файл в выбранной программе, DuPanel получает от Android список установленных приложений, которые можно запустить или которые умеют открывать файлы. Этот список не сохраняется и не покидает устройство; сохраняются только названия пакетов приложений, которые вы сами добавили в избранное, на панель или выбрали для открытия файлов. Разрешение на установку пакетов (REQUEST_INSTALL_PACKAGES) используется только тогда, когда вы сами открываете APK-файл, — чтобы передать его системному установщику Android.

### Хранение и удаление
Настройки хранятся в личной папке приложения на устройстве: оформление, колонки, панели и кнопки, избранные папки и приложения, открытые в панелях папки и сохранённая позиция, последние маски поиска и выделения, данные серверов (см. выше). Если в Android включено резервное копирование, система может сохранить эти настройки в вашем аккаунте Google; разработчик к ним доступа не имеет. Кнопки «Выход» и «Перезапуск» удаляют временные копии файлов и кеш приложения и очищают буфер обмена; история переходов по папкам хранится только в памяти и пропадает при закрытии. Все данные приложения удаляются при его удалении или через «Настройки Android → Приложения → DuPanel → Хранилище → Очистить хранилище». Ваши файлы в памяти устройства и на серверах при этом не затрагиваются.

### Дети
Приложение не предназначено для детей и не собирает данные детей.

### Изменения
При изменении политики новая версия будет опубликована по этой же ссылке с новой датой.

### Контакты
Вопросы о конфиденциальности: **hotbynow@gmail.com**

---

## English

**DuPanel** is a dual-pane file manager for Android. This policy explains what data the app uses.

### Data we collect
**None.** The app does not collect, transmit or sell any personal data. It contains no ads, no analytics, no crash reporting, no update checks, no accounts and no third-party data-collection SDKs. The developer receives no information about you or your files.

### Files on your device
The app requests **All files access** (MANAGE_EXTERNAL_STORAGE; on Android 10 and earlier, the storage read/write permissions) because its core purpose is to browse, copy, move, rename, zip and delete files and folders in internal storage, on SD cards and USB drives. All operations run on your device and only when you ask for them. Files leave the device only when you yourself copy them to a server you connected to, or hand them to another app ("Share", "Open with"). The developer never receives them.

### Network connections
The app uses the network **only** to connect to servers you enter yourself (SMB, FTP/FTPS, SFTP) — for example your router, NAS or web hosting. Data goes directly between your device and that server; the developer is not involved. So that you don't have to type them again, the app stores on the device the server address, port, shared folder, user name and the path to your SSH key file (if you set one), and the fingerprints of server keys and certificates you chose to trust. **Passwords and SSH key passphrases are not stored**: they are kept in memory only while the connection is open. The app does not copy your SSH key file; it reads it from the path you gave when connecting. Plain FTP (without TLS) sends the password and files unencrypted; use FTPS or SFTP for protected transfers.

### Other apps
To show "Favorite apps" and to open a file in an app you choose, DuPanel gets from Android the list of installed apps that can be launched or can open files. This list is not saved and never leaves the device; only the package names of apps you add to favorites or a toolbar, or choose for opening files, are saved. The install-packages permission (REQUEST_INSTALL_PACKAGES) is used only when you open an APK file yourself, to hand it to the Android system installer.

### Storage and deletion
Settings are stored in the app's private folder on the device: appearance, columns, toolbars, favorite folders and apps, the folders open in the panels and the saved panel position, recent search and selection masks, and server details (see above). If Android backup is turned on, the system may back these settings up to your Google account; the developer has no access to them. The "Exit" and "Restart" buttons delete temporary file copies and the app cache and clear the clipboard; the folder navigation history is kept in memory only and is gone when the app closes. All app data is removed when you uninstall the app or via Android Settings → Apps → DuPanel → Storage → Clear storage. Your own files on the device and on servers are not affected.

### Children
The app is not directed at children and does not collect children's data.

### Changes
If this policy changes, the new version will be published at the same address with a new date.

### Contact
Privacy questions: **hotbynow@gmail.com**
