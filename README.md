# bitrix-beGateway-module

Установка и использование модуля:\n
1. Скопировать папку модуля в дирректорию на сервере \bitrix\modules
2. В админке в разделе marketplace в установленных решениях появится модуль. Установите его.
3. В админке создайте платёжную систему и привяжите к ней обработчик.
4. В настройках модулей установите нужные настройки
5. На страницы редиректов (success_url, fail_url) выведите компонент devtm:begateway.transaction.info
