---
anchor: dependency_management
---

# Dependency Management {#dependency_management_title}

Laravel не написан с нуля. Он основан на нескольких библиотеках и фреймворках. Вы можете посмотреть на весь список зависимостей [здесь][dependencies-laravel]. It is also being powered by [Illuminate components][illuminate]. All of these components are being tied into each other by making sure each of them can be treated and written as a composer [Composer library][comp-lib]. These libraries is hosted in public repositories.

[dependencies-laravel]:https://github.com/laravel/framework/blob/5.0/composer.json#L22-L43
[illuminate]:https://github.com/illuminate
[comp-lib]:https://getcomposer.org/doc/02-libraries.md