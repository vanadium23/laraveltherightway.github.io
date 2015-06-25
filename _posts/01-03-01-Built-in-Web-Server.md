---
title:   Встроенный веб-сервер
isChild: true
anchor:  builtin_web_server
---

## Встроенный веб-сервер {#builtin_web_server_title}

Вы можете заметить файл server.php в исходных кодах Laravel. Этот файл предназначен для запуска проекта без необходимости установки веб-сервера (такого как Apache или Nginx), но эта опция, в основном, расчитана только для разработки. Он работает на основе внутреннего веб-сервера PHP, доступном начиная с версии 5.4. Для запуска сервера Вам необходимо выполнить следующую команду из терминала:

{% highlight console %}
> php -S localhost:8000 server.php
{% endhighlight %}

или проще (примечание: следующее работает **только** для Laravel `v4.x`):

{% highlight console %}
> php artisan serve
{% endhighlight %}

Так же Вы можете указать необязательные параметры:

{% highlight console %}
> php artisan serve --port=8080 --host=local.dev
{% endhighlight %}
