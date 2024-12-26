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

