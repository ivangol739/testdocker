# Клонируйте репозиторий:
git clone https://github.com/ivangol739/testdocker

# Перейдите в директорию проекта:
cd testdocker

# Настройте переменные окружения

# Выполните миграции базы данных:
python manage.py migrate

# Сборка и запуск
docker build -t my_first_image:1.1 . 

docker run -d -p 8080:80 my_first_image:1.1 


