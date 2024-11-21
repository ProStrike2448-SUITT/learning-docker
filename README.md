# learning-docker

Опанування базових налаштування та використання Docker, пройшовши курс на https://docs.docker.com/get-started/introduction/get-docker-desktop/

## 1. Системні вимоги (WSL 2 backend)

✅ Windows 10 Education 22H2 (build 19045.5131)  
✅ Увімкнув віртуалізацію в BIOS  
![](screenshots/enable_virtualisation.jpg)  
✅ Увімкнув необхідні можливості  
![](screenshots/windows_features.png)  
✅ Встановив WSL  
![](screenshots/wsl_install.png)  
✅ Перезапустив ПК

> [!WARNING]
> Щоб запустити контейнери Windows, потрібна Windows 10 або Windows 11 Professional або Enterprise. Випуски Windows Home або Education дозволяють запускати лише контейнери Linux.

## 2. Інтерактивне встановлення

1. Завантажив інсталятор
   ![](screenshots/docker_installer.png)
2. Запустив інсталятор подвійним кліком
   ![](screenshots/docker_installer_run.png)
3. Успішно встановив
   ![](screenshots/succesful_install.png)
4. Зареєстрував персональний акаунт
   ![](screenshots/docker_account.png)
5. Пройшов коротке опитування
   ![](screenshots/docker_survey.png)

## 3. Перший контейнер

1. Запустив welcome-to-docker за допомогою терміналу
   ![](screenshots/docker_welcome.png)
2. Перейшов за посиланням http://localhost:8080 у браузері
   ![](screenshots/welcome_page.png)

## 4. Управління контейнерами у Docker Desktop

1. У вкладці Containers обрав запущений контейнер
   ![](screenshots/containers.png)
2. Перейшов у вкладку Exec та вивів зміст контейнеру на екран за допомогою команди
   ![](screenshots/container_info.png)
3. Знайшов контейнер для наступної роботи через поле пошуку
   ![](screenshots/search.png)
