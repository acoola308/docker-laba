# Лабараторная работа №3
1 задание - [ссылка на образ](https://hub.docker.com/r/acoola308/custom-nginx) 

2 задание 
![Снимок экрана 2024-12-13 003242](https://github.com/user-attachments/assets/c1c8b240-c52a-42e7-97e6-7155d7d79f60)

3 задание 
![Снимок экрана 2024-12-13 011135](https://github.com/user-attachments/assets/94f02d70-9256-4a25-9193-eeed5a96693d)
контейнер остановился потому что

![Снимок экрана 2024-12-13 011205](https://github.com/user-attachments/assets/e8db7c6d-fa07-4c2a-a5c2-4f49f7da95c1)  
отредактировал файл "/etc/nginx/conf.d/default.conf", заменив порт "listen 80" на "listen 81"

![Снимок экрана 2024-12-13 012721](https://github.com/user-attachments/assets/d63906a0-8368-4c9c-b011-23e3605c0ef2)  
кратко описал суть проблемы

![Снимок экрана 2024-12-13 015039](https://github.com/user-attachments/assets/bfe0e7d0-a97b-4731-8cbc-0ac7db349c89)  
выявляем полный идентификатор контейнера,  останавливаем наш контейнер и докер службу, редактируем файлы контейнера hostcongig.json и config.v2.json так, чтобы он находился на 81 порту, и наш хост ссылался на него

![Снимок экрана 2024-12-13 013955](https://github.com/user-attachments/assets/4be2ab58-aa5f-4b30-8dfa-b9c5eaab6c51)
![Снимок экрана 2024-12-13 014239](https://github.com/user-attachments/assets/cdcfaa3b-4850-4c0f-b20b-a955779c91ed)
![Снимок экрана 2024-12-13 014258](https://github.com/user-attachments/assets/df8e868c-ce80-4216-afa4-e467998c39fc)

