# sqlmap

[![Build Status](https://api.travis-ci.org/sqlmapproject/sqlmap.svg?branch=master)](https://api.travis-ci.org/sqlmapproject/sqlmap) [![Python 2.6|2.7](https://img.shields.io/badge/python-2.6|2.7-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/sqlmapproject/sqlmap/master/LICENSE) [![Twitter](https://img.shields.io/badge/twitter-@sqlmap-blue.svg)](https://twitter.com/sqlmap)

sqlmap это инструмент для тестирования проникновения с открытым исходным кодом, который автоматизирует процесс обнаружения и использования ошибок внедрения SQL и захвата серверов баз данных. Оно приходит с мощным двигателем обнаружения, много характеристик ниши для типичного тестера проникания и обширный ряд переключателей продолжая от fingerprinting базы данных, над данными fetching от базы данных, к достигать основной системы файлов и исполнять команды на операционной системе через внеполосные соединения.

**Проект sqlmap спонсируется [Netsparker Web Security Security Scanner](https://www.netsparker.com/?utm_source=github.com&utm_medium=referral&utm_content=sqlmap+repo&utm_campaign=generic+advert).**

Скриншоты
----

![Скриншот](https://raw.github.com/wiki/sqlmapproject/sqlmap/images/sqlmap_screenshot.png)

Вы можете посетить [сборник скриншотов](https://github.com/sqlmapproject/sqlmap/wiki/Screenshots) демонстрируя некоторые функции в вики.

Установка
----

Вы можете скачать последнюю версию tarball, нажав [здесь](https://github.com/sqlmapproject/sqlmap/tarball/master) или последний zipball, нажав [здесь](https://github.com/sqlmapproject/sqlmap/zipball/master).

Предпочтительно вы можете загрузить sqlmap, клонировав [Git](https://github.com/sqlmapproject/sqlmap) репозиторий:

    git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap-dev

sqlmap работает из коробки с [Python](http://www.python.org/download/) версии **2.6.x** и **2.7.x** на любой платформе.

Использование
----

Чтобы получить список основных опций и переключателей, используйте:

    python sqlmap.py -h

Чтобы получить список всех опций и переключателей, используйте:

    python sqlmap.py -hh

Вы можете найти пример запуска [здесь](https://asciinema.org/a/46601).
Чтобы получить обзор возможностей sqlmap, список поддерживаемых функций и описание всех параметров и переключателей, а также примеры, вам рекомендуется ознакомиться с [руководством пользователя](https://github.com/sqlmapproject/sqlmap/wiki/Usage).

Ссылки
----

* Домашняя страница: http://sqlmap.org
* Скачать: [.tar.gz](https://github.com/sqlmapproject/sqlmap/tarball/master) or [.zip](https://github.com/sqlmapproject/sqlmap/zipball/master)
* RSS-канал: https://github.com/sqlmapproject/sqlmap/commits/master.atom
* Отслеживание проблем: https://github.com/sqlmapproject/sqlmap/issues
* Руководство пользователя: https://github.com/sqlmapproject/sqlmap/wiki
* Часто задаваемые вопросы (FAQ): https://github.com/sqlmapproject/sqlmap/wiki/FAQ
* Твиттер: [@sqlmap](https://twitter.com/sqlmap)
* Обзоры: [http://www.youtube.com/user/inquisb/videos](http://www.youtube.com/user/inquisb/videos)
* Скриншоты: https://github.com/sqlmapproject/sqlmap/wiki/Screenshots
