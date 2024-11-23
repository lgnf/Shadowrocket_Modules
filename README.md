# YoutubeModuleSR

Возможности модуля:
1. Отключение рекламы в приложении YouTube;
2. Фоновое воспроизведение без Premium;
3. Картинка в картинке без Premium;
4. Выбор качества видео по умолчанию;
5. Автоперевод субтитров на русский язык (на данный момент модно отключить только вручную в плеере).

Управление настройками фонового воспроизведения и выбора качества видео находятся в настроках YouTube в разделе ФОНОВЫЙ И ОФЛАЙН-РЕЖИМ.
Так же там есть настройка умного скачивания, но пока что я не разобрался как оно работает.

Перед установкой модуля советую использовать конфиг для Shadowrocket от Misha Tugushev (https://github.com/misha-tgshv?ref=mishatugushev.ru) актуальный для РФ.
1. Открываем вкладку Настройка (Config) с иконкой папки, жмем в верхнем правом углу на + и добавляем ссылку на готовый конфиг в поле Загрузить с URL (Download from URL):
   https://cdn.jsdelivr.net/gh/misha-tgshv/shadowrocket-configuration-file@release/conf/sr_ru_public_lists.conf
3. Заходим конфиг и в нём открываем HTTPS Decryption → активируем HTTPS Decryption → выпускаем сертификат Generate A New CA Certificate;
4. Устанавливаем сертификат на устройство Install CA Certificate to System → Allow → Profile Downloaded;
5. Открываем настройки iPhone → открываем Profile Downloaded → Install → вводим пароль Enter Passcode → два раза подтверждаем кнопкой Install → получаем сертификат и значение Profile Installed;
6. Открываем Основные → О телефоне → и в самом низу находим Certificate Trust Settings → активируем сертификат Shadowrocket;
7. Снова открываем вкладку Настройка (Config) с иконкой папки, заходим во вкладку Модули (Modules), жмем в верхнем правом углу на + и добавляем ссылку на модуль в поле Загрузить с URL (Download from URL):
   https://github.com/lgnf/Shadowrocket_Modules/blob/main/YouTubePremium/YoutubePremium.module
8. Убеждаемся, что модуль включен - на нём должна стоять галочка;
9. Включаем VPN.

Модуль и скрипты были взяты из этого репозитория: 
https://github.com/YanbingJiang/Shadowrocket_diy_rules
