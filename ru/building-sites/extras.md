---
title: "Установка компонентов"
translation: "building-sites/extras"
---

## Установка пакета

Эта раздел разъяснит вам процесс установки пакета через [Управление пакетами](extending-modx/transport-packages "Управление пакетами").

Для загрузки пакетов через [Управление пакетами](extending-modx/transport-packages "Управление пакетами") требуются cURL или PHP сокеты. MODX сообщит вам, если у вас их нет. Если у вас возникают проблемы с управлением пакетами после подтверждения их установки, см. [Устранение неполадок управления пакетами](building-sites/extras/troubleshooting "Устранение неполадок управления пакетами").

Перейдите в Пакеты -> [Установщик](extending-modx/transport-packages "Управление пакетами").

![](/download/attachments/23c66e1935073aec60f9d9ea342a5b6b/modx-package-management-1.jpg)

Затем нажмите кнопку "Загрузить пакеты".

![](/download/attachments/23c66e1935073aec60f9d9ea342a5b6b/modx-package-management-2.jpg)

Просмотрите доступные пакеты, развернув категории. Нажмите "Загрузить", чтобы загрузить любой пакет, который вы хотите загрузить. Вы также можете загрузить несколько пакетов одновременно.

![](/download/attachments/23c66e1935073aec60f9d9ea342a5b6b/modx-package-management-3.jpg)

Пакет будет загружен в соответствующий каталог MODX. Теперь вы можете просмотреть новый пакет и нажать "Установить", чтобы установить его.

![](/download/attachments/23c66e1935073aec60f9d9ea342a5b6b/modx-package-management-4.jpg)

[Поставщики](building-sites/extras/providers "Поставщики")

Вы можете выбрать источник для загрузки пакетов, добавить новый источник или выбрать пакеты на вашем локальном компьютере. Используйте ссылку "Поставщики -> Добавить нового поставщика" чтобы добавить нового поставщика, по умолчанию modx.com/extras доступно в качестве удаленного поставщика.

## Ручная установка

Вы можете вручную скопировать пакет в каталог core/packages. Пакет должен быть transport.zip-архивом, таким как wayfinder-2.1.1-beta1.transport.zip. Затем нажмите "Загрузить пакеты" в списке и выберите "Искать пакеты локально". Пакет теперь будет отображаться в списке пакетов, и вы можете установить его как обычно.

## Шаг за шагом

### Загрузка пакетов

У вас есть несколько вариантов: вы можете загрузить пакет удаленно через поставщика, выбрав в меню провайдера modx.com (или просто нажав "Загрузить пакеты").

Чтобы загрузить пакеты, просто выберите в списке пакет, который вы хотите загрузить, и нажмите кнопку "Загрузить".

Либо пакеты можно загрузить непосредственно через браузер по ссылке, расположенной по адресу <http://modx.com/extras/>. Скачанные zip-пакеты нужно загрузить в каталог core/packages/, и перейти в раздел "Управление пакетами". Затем нужно нажать "Загрузить пакеты" в списке и выбрать "Искать пакеты локально". MODX просканирует каталог основных пакетов и добавит все имеющиеся у вас пакеты.

Для загрузки пакетов требуется, чтобы на вашем веб-сервере были установлены cURL или сокеты. Если они не установлены, список пакетов будет пустым.

Официальный поставщик modx.com имеет URL-адрес:
<http://rest.modx.com/extras/>
 и поставляется в комплекте с MODX Revolution 2.0.

### Установка пакетов

Вы можете легко установить пакеты, нажав "Установить". Загрузится консоль, показывающая детали установки пакета.

Если у пакета есть лицензионное соглашение, вам необходимо согласиться с ним, прежде чем продолжить. Кроме того, пакет может предоставить файл README, с которым вы можете ознакомиться перед установкой.

Наконец, пакет может запросить или не запросить некоторые предустановочные параметры и настройки для вас, такие как:

![](/download/attachments/18678070/pkgsetupopt.png?version=1&modificationDate=1247328671000)

Затем пакет будет установлен в вашей системе MODX.

### Обновление пакетов

Вы можете легко обновить любой пакет, который был загружен у поставщика. Просто нажмите на кнопку "Проверить наличие обновлений" или "Обновить", и MODX покажет все новые версии пакета. Если ваш пакет обновлен, появится сообщение об этом.

Затем вы можете выбрать версию, которую хотите установить, и MODX скачает пакет и начнет процесс установки.

Если вы хотите вернуться на предыдущую версию пакета, вам необходимо нажать "Деинсталлировать".

### Удаление пакетов

Вы можете удалить любой пакет или удалить или деинсталлировать его. _Удаление_ полностью удаляет zip-файл из вашего каталога core/packages. Деинсталляция же просто удаляет его последнюю версию.

Обратите внимание на три метода деинсталляции пакета:

![](/download/attachments/18678070/pkguninstall.png?version=1&modificationDate=1247328671000)