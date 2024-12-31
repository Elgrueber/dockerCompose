# dockerCompose
Assignment "Orchestration of a group of Docker containers using Docker Compose."

Task 1.
https://hub.docker.com/repository/docker/alenkora/custom-nginx/general

Task 2.
<img width="864" alt="Task2_Netology" src="https://github.com/user-attachments/assets/dc655711-f1cc-4e8d-9a97-a03c8c441513" />

Task 3.
1. docker attach custom-nginx-t2
2. Ctrl-C
3. docker ps -a.
<img width="920" alt="image" src="https://github.com/user-attachments/assets/7967e6a0-971f-4e68-9e47-968c46be2a78" />
   
Контейнер остановился, так как я остановила Nginx в контейнере, и контейнер был завершён. Контейнер будет работать нормально, если основной процесс Nginx не будет прерван. После перезапуска контейнера, Nginx снова начнёт работу.

4,5:
<img width="453" alt="image" src="https://github.com/user-attachments/assets/c5f7fae1-01a5-4965-8235-e5817cd8eb39" />

6,7:
<img width="700" alt="image" src="https://github.com/user-attachments/assets/506c3651-5c2e-4531-b1f9-71a3aff77b7e" />

<img width="219" alt="image" src="https://github.com/user-attachments/assets/1c19e37b-03a0-4113-a3d8-9fe4cc7f6dc8" />

8:
<img width="505" alt="image" src="https://github.com/user-attachments/assets/bdd10823-16a6-41ef-b519-3c3e75f394c7" />

9,10:
<img width="515" alt="image" src="https://github.com/user-attachments/assets/6cbe2474-96d0-4960-966f-e2ff4aea36c7" />

Проблема с доступом к контейнеру через curl на порту 8080 возникает из-за того, что конфигурация Nginx была изменена, и теперь он слушает порт 81 внутри контейнера, но порт 8080 на хосте остался привязанным только к порту 80 внутри контейнера.

11:
<img width="758" alt="image" src="https://github.com/user-attachments/assets/9f3d3c7b-c1d1-4079-8515-0ab1d45d32f6" />

<img width="413" alt="image" src="https://github.com/user-attachments/assets/9ee31b44-314a-4621-9606-6a42d0f33dd6" />

12:
<img width="506" alt="image" src="https://github.com/user-attachments/assets/d2575a3a-2d79-4da4-b2dc-aac68aa4b672" />

Task 4.
1,2
<img width="760" alt="image" src="https://github.com/user-attachments/assets/95002a0b-9e85-4bec-8aec-44450f2af818" />
3,4:
<img width="556" alt="image" src="https://github.com/user-attachments/assets/b7d4c9b8-a9a7-4b20-a5c0-f7664bc39b37" />
5:

<img width="533" alt="image" src="https://github.com/user-attachments/assets/eefa555f-85c6-482b-9574-4cd926566224" />

Task 5.
1,2:
![image](https://github.com/user-attachments/assets/5551b363-b2c6-4f5f-bf86-3435187b24ce)
![image](https://github.com/user-attachments/assets/478d2e13-6a48-4c02-83a8-515c0740fdf8)
![image](https://github.com/user-attachments/assets/ff52acf4-16e2-4003-846f-fad38be1c402)
![image](https://github.com/user-attachments/assets/f3c1b048-2de3-4fbf-87a8-86687d46a692)
Ответ на вопрос: по умолчанию docker compose ищет файл docker-compoe.yaml. Поэтому он и запускается. 

3:
![image](https://github.com/user-attachments/assets/3427301d-d5d0-4793-a020-42db2ae740c8)
![image](https://github.com/user-attachments/assets/1ff9e199-ebe6-4a73-85c4-fd9ec09b421c)
![image](https://github.com/user-attachments/assets/6db5b19c-22b3-4e28-bdb8-4bac3b9ee85a)
![image](https://github.com/user-attachments/assets/16abffac-1407-4b17-8494-47e05e0a5379)

4,5,6:
![image](https://github.com/user-attachments/assets/cb22a2eb-7317-40c8-a556-f25a90a651c2)

7:
![image](https://github.com/user-attachments/assets/da523426-3f27-4bbe-877a-63d4bc01cc13)
Warning - так как в файле используется устаревший атрибут version, который не применяется в текущих версиях Docker Compose. Лучше удалить, чтобы не было возможной путаницы в будущем. Далее удалила из файла. 
![image](https://github.com/user-attachments/assets/10fded3d-9afc-42ca-a4ba-d1d77c1f1a95)
![image](https://github.com/user-attachments/assets/8e3636ef-c7f3-44b1-bfae-ae596f759bfd)






