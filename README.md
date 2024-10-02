# terr
Задание 1
1) Перейдите в каталог src. Скачайте все необходимые зависимости, использованные в проекте.

![alt text](https://github.com/StepanovSA/guard_network/blob/main/Kali%201.png)


2) Изучите файл .gitignore. В каком terraform-файле, согласно этому .gitignore, допустимо сохранить личную, секретную информацию?(логины,пароли,ключи,токены итд)


3) Выполните код проекта. Найдите в state-файле секретное содержимое созданного ресурса random_password, пришлите в качестве ответа конкретный ключ и его значение.


4) Раскомментируйте блок кода, примерно расположенный на строчках 29–42 файла main.tf. Выполните команду terraform validate. Объясните, в чём заключаются намеренно допущенные ошибки. Исправьте их.

![alt text](https://github.com/StepanovSA/guard_network/blob/main/Kali%201.png)

5) Выполните код. В качестве ответа приложите: исправленный фрагмент кода и вывод команды docker ps.

![alt text](https://github.com/StepanovSA/guard_network/blob/main/Kali%201.png)

6) Замените имя docker-контейнера в блоке кода на hello_world. Не перепутайте имя контейнера и имя образа. Мы всё ещё продолжаем использовать name = "nginx:latest". Выполните команду terraform apply -auto-approve.
Объясните своими словами, в чём может быть опасность применения ключа -auto-approve. Догадайтесь или нагуглите зачем может пригодиться данный ключ? В качестве ответа дополнительно приложите вывод команды docker ps.

![alt text](https://github.com/StepanovSA/guard_network/blob/main/Kali%201.png)

7) Уничтожьте созданные ресурсы с помощью terraform. Убедитесь, что все ресурсы удалены. Приложите содержимое файла terraform.tfstate.

![alt text](https://github.com/StepanovSA/guard_network/blob/main/Kali%201.png)

8) Объясните, почему при этом не был удалён docker-образ nginx:latest. Ответ ОБЯЗАТЕЛЬНО НАЙДИТЕ В ПРЕДОСТАВЛЕННОМ КОДЕ, а затем ОБЯЗАТЕЛЬНО ПОДКРЕПИТЕ строчкой из документации terraform провайдера docker. (ищите в классификаторе resource docker_image )
