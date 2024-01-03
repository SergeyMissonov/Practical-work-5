#  Практическая работа 5

1. Установливаем Docker и Docker Compose согласно инструкции
2. Настраиваем Docker для работы без прав root командами sudo groupadd docker, 
   sudo usermod -aG docker $USER
3. Создаем простой скрипт выводящие приветствие "Hello World"
4. Создаем репозиторий на Github для нашего проекта "Practical-work-5"
5. Создаем Dockerfile для сборки образа и добавляем наш скрипт
6. Собираем образ с помощью Dockerfile командой docker build -t practical-work-5 .
7. Запускаем Docker контейнер docker run -it practical-work-5 /bin/bash и       
   проверяем нашу программу 
8. Создаем docker-compose.yml для запуска нашего контейнера с программой
9. Запускаем сервис коммандой docker-compose up и проверяем работоспособность
