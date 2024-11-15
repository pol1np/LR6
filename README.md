# LR6
Лабораторная работа №6
1. Создаем копию в личное хранилище
![image](https://github.com/pol1np/LR6/blob/report/newfolder/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-15%20040702.png?raw=true)
2. Клонируем удаленный репозиторий на компьютер
![image](https://github.com/pol1np/LR6/blob/report/newfolder/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-15%20040908.png?raw=true)
3. Добавляем файл через интерфейс Github
![image](https://github.com/pol1np/LR6/blob/report/newfolder/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-15%20041145.png?raw=true)
![image](https://github.com/pol1np/LR6/blob/report/newfolder/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-15%20041323.png?raw=true)
4. Подтягиваем изменения в локальный репозиторий
![image](https://github.com/user-attachments/assets/45adc0b1-e31c-4cfd-89a6-fb91a7bb27d9)
5. Получаем историю для каждой ветки
![image](https://github.com/user-attachments/assets/8239bf87-a14f-4fad-ad06-e3cb366a2169)
6. Смотрим последние изменения для каждой ветки
![image](https://github.com/user-attachments/assets/34dedd9a-b986-41ef-a547-ffcbb85abf00)
![image](https://github.com/user-attachments/assets/0f5d7d00-a555-4d05-b558-de71c63fe576)
7. Выполняем слияние и решаем конфликт </br>
![image](https://github.com/user-attachments/assets/dd3c8133-0472-4ff6-b6f8-2adb47dd48b9) </br>
![image](https://github.com/user-attachments/assets/e1687b52-b050-47b4-838a-19daacb2311f) </br>
![image](https://github.com/user-attachments/assets/ea44f9d8-dc66-469c-9e05-0d5baae2c3b3) </br>
![image](https://github.com/user-attachments/assets/bb36da7c-7430-423f-8c57-a16c674a4305) </br>
![image](https://github.com/user-attachments/assets/7d538ebb-4569-48a6-a8dd-5cca115361d3) </br>
![image](https://github.com/user-attachments/assets/49827b9c-4157-402a-9ee4-808880621721) </br>
![image](https://github.com/user-attachments/assets/4a75f470-329d-499f-af74-5fbf53ad6fdf) </br>
![image](https://github.com/user-attachments/assets/c0be92ac-2acb-46e5-8321-a8196b0150f0) </br>
8. Удаляем побочную ветку master </br>
![image](https://github.com/user-attachments/assets/6a4add7f-4249-4726-bcd1-2f098ce1b7d0)
9. Делаем изменение в файле и создаем коммит </br>
![image](https://github.com/user-attachments/assets/7eeec953-a983-4d9b-bc72-10e0bd266dd2)
10. Создаем новый файл, делаем коммит </br>
![image](https://github.com/user-attachments/assets/77ce7073-89d1-4b8b-8f29-463205a11fa0)
11. Делаем откат коммита </br>
![image](https://github.com/user-attachments/assets/3713864b-6895-4ddd-a518-ef8352bf6c71)
12. Создаем ветку для отчета и переходим на нее </br>
![image](https://github.com/user-attachments/assets/18473dce-f9a7-4e98-97fb-e0497008d8f5)
13. Отправляем все данные на удаленный репозиторий</br>
![image](https://github.com/user-attachments/assets/8795487f-a03a-44b6-94ba-8627ea6b7542)
# Лог команд
git config global user.name/email </br>
git clone https://github.com/pol1np/LR6 </br>
git pull </br>
git reflog --all </br>
git log -p </br>
git checkout branch1 </br>
git merge master </br>
git diff </br>
git add mergefile.txt </br>
git status </br>
git commit -m "..." </br>
git branch -d master </br>
git add mergefile.txt </br>
git commit -m "..." </br>
git add WOW.txt </br> 
git commit -m "..." </br>
git reset --hard HEAD </br>
git checkout -b otchet </br>
git branch </br>
git push --set-upstream origin otchet </br>
# История операция
commit 8b2cbd8b583214c76d3bdd24455e2ea3d619efbd (HEAD -> master, origin/master, origin/HEAD)
Author: pol1np <144121623+pol1np@users.noreply.github.com>
Date:   Fri Nov 15 04:12:56 2024 +0300

    Create New file

commit 921f53b8d0cebf542c791cf31f04e9b792f385a4
Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
Date:   Sat Nov 21 20:09:49 2020 +0300

    Обновление информации

commit c08a654a63cfc3a7146b2b7015884d9020f5cbf5
Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
Date:   Sat Nov 21 20:02:16 2020 +0300

    Файл создан пустым

commit 3c6e9131bb47ed6009c28226afb0535c7f6d5964
Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
Date:   Sat Nov 21 19:58:20 2020 +0300

Merge: 8ecb019 8daf57b
Author: pol1np <polinaprotcenko@gmail.com>
Date:   Fri Nov 15 06:41:37 2024 +0300

    Merge branch 'report' of https://github.com/pol1np/LR6 into report

commit 8daf57bf5d1ce4f171aeed7d3963ac29a62050e4
Author: pol1np <144121623+pol1np@users.noreply.github.com>
Date:   Fri Nov 15 06:33:33 2024 +0300

    Update README.md

commit 3ce9dc979ca93ad1602889a11feeb0e29cd3a31f
Author: pol1np <144121623+pol1np@users.noreply.github.com>
Date:   Fri Nov 15 06:03:43 2024 +0300

    Add files via upload

commit 3190cbebe9bf1f5848b45a6327a7265702e08e56
Author: pol1np <144121623+pol1np@users.noreply.github.com>
Date:   Fri Nov 15 06:01:36 2024 +0300







