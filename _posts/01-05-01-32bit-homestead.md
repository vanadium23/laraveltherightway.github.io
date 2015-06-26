---
isChild: true
anchor:  32bit-homestead
---

## Homestead для 32-bit компьютеров {#homestead32bit_title}

Homestead не будет запускаться на Вашем 32-битном компьютере, поскольку ему необходима аппаратная виртуализация (VT-x). Она необходима  Homestead, поскольку его базовый образ - ubuntu/trusty64, которая является 64-битной машиной. Для тех людей, которые не могут включить это в своём BIOS, или для компьютеров без поддержки VT-x, можно использовать 32-битную версию Homestead, доступную по [ссылке][32bit-homestead-here].

[32bit-homestead-here]: https://github.com/buonzz/homestead32