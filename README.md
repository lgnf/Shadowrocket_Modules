# Shadowrocket_Modules
Useful modules for the Shadowrocket VPN client

Перед установкой модуля советую использовать конфиг ддя Shadowrocket от Misha Tugushev (https://github.com/misha-tgshv?ref=mishatugushev.ru)
1. Открываем вкладку Настройка (Config) с иконкой папки, жмем в верхнем правом углу на + и добавляем ссылку на готовый конфиг в поле Загрузить с URL (Download from URL):
   https://cdn.jsdelivr.net/gh/misha-tgshv/shadowrocket-configuration-file@release/conf/sr_ru_public_lists.conf
2. Заходим конфиг и в нём открываем HTTPS Decryption → активируем HTTPS Decryption → выпускаем сертификат Generate A New CA Certificate.
3. Устанавливаем сертификат на устройство Install CA Certificate to System → Allow → Profile Downloaded.
4. Открываем настройки iPhone → открываем Profile Downloaded → Install → вводим пароль Enter Passcode → два раза подтверждаем кнопкой Install → получаем сертификат и значение Profile Installed.
5. Открываем Основные → О телефоне → и в самом низу находим Certificate Trust Settings → активируем сертификат Shadowrocket.
6. Снова открываем вкладку Настройка (Config) с иконкой папки, заходим во вкладку Модули (Modules), жмем в верхнем правом углу на + и добавляем ссылку на модуль в поле Загрузить с URL (Download from URL):
   https://github.com/lgnf/Shadowrocket_Modules/blob/main/YouTubePremium/YoutubePremium.module
7. Убеждаемся, что модуль включен - на нём должна стоять галочка.
8. Включаем VPN.
