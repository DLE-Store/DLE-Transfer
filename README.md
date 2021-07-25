# DLE Transfer
Делаем теги глобальными

![version](https://img.shields.io/badge/version-2.0.0-red.svg?style=flat-square "Version")
![DLE](https://img.shields.io/badge/DLE-14.x-green.svg?style=flat-square "DLE Version")
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/DLE-Store/DLE-Transfer/blob/main/LICENSE)

## Назнчение
Поможет вам вывести разные данные тегов которые привязаны к определенному TPL файлу в другом

## Специальная версия
- Для работы необходим плагин [UImages PRO](https://vk.cc/c4iglC)

## Преимущества
- Лёгкий в использовании.
- Быстро работает.


## Установка
- Загрузить через систему плагинов файл dle-transfer.xml

Рассмотрим на примере вывода тега Делаем теги глобальными в DLE с **fullstory.tpl** в **main.tpl**:

В **fullstory.tpl** пишем
```smarty
[transfer=fulltitle]{title}[/transfer]
```
И потом в **main.tpl** в нужном месте
```smarty
{transfer_fulltitle}
```

В итоге Название новости будет показано в файле **main.tpl** тегом **{transfer_fulltitle}**
