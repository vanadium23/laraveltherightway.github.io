---
isChild: true
anchor:  composer_and_packagist
title: Composer и Packagist
---

## Composer и Packagist {#composer_and_packagist_title}

По умолчанию, Laravel использует Packagist в качестве репозитория и GitHub для скачивания своих файлов. Но Вы можете задать свои репозитории с помощью настройки [Satis][satis] зеркала пакетов. Также Вы можете использовать любой класс или даже функцию в Laravel (до тех пор пока она может быть автозагружена). Но это не рекоммендуемая практика. Лучше оформить свои наработки в виде [Composer библиотеки][own-composer] и включить её как зависимость в файл composer.json.

[satis]:https://getcomposer.org/doc/articles/handling-private-packages-with-satis.md
[own-composer]:http://knpuniversity.com/screencast/question-answer-day/create-composer-package