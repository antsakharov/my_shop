# my_shop
# Запуск celery
celery -A myshop  worker --loglevel=info -P gevent
# Запуск flower
celery -A myshop flower 
# Flower доступен по адресу:
http://localhost:5555
# Установка GTK-for-Windows-Runtime-Environment-Installer:
https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases
# Установка gettext для Windows:
https://mlocati.github.io/articles/gettext-iconv-windows.html