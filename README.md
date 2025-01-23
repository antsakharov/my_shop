# my_shop
# Запуск celery
celery -A myshop  worker --loglevel=info -P gevent
# Запуск flower
celery -A myshop flower 
# Flower доступен по адресу:
http://localhost:5555

