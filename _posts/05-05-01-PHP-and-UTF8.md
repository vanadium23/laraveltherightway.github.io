---
title:   Работа с UTF-8
isChild: true
anchor:  php_and_utf8
---

## Работа с UTF-8 {#php_and_utf8_title}

Laravel использует библиотеку [patchwork/utf8][patchwork] для всё работы, связанной с UTF8. Для разработчика необходимо понять следующии концепции:

* [Character Sets / Character Encoding Issues][li-1]
* [Handling UTF-8 with PHP][li-2]
* [Unicode Normalization][li-3]
* [Grapheme Clusters][li-4]
* [Unicode Security Considerations][li-5]


[patchwork]:https://github.com/nicolas-grekas/Patchwork-UTF8
[li-1]:http://www.phpwact.org/php/i18n/charsets
[li-2]:http://www.phpwact.org/php/i18n/utf-8
[li-3]:http://en.wikipedia.org/wiki/Unicode_equivalence
[li-4]:http://unicode.org/reports/tr29/
[li-5]:http://www.unicode.org/reports/tr36/#Deletion_of_Noncharacters