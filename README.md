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

![Снимок экрана 2024-12-13 014908](https://github.com/user-attachments/assets/9ae0de10-c5f0-4a77-adb3-ce47afe7a84f)
запускаем докер службу и контейнер, смотрим список работающих контейнеров, видим что всё работает. удаляем контейнер без его остановки с помощью параметра rm -f

4 задание 
![Снимок экрана 2024-12-13 030751](https://github.com/user-attachments/assets/c3f4ab41-a572-40c4-b762-4fbfa21e82e2)

5 задание 

![Снимок экрана 2024-12-13 032105](https://github.com/user-attachments/assets/e70af210-b98a-4d97-97b0-5591d70cdf10)
![Снимок экрана 2024-12-13 032105](https://github.com/user-attachments/assets/47403271-c342-4902-b344-4b81f5a2ffed)

![Снимок экрана 2024-12-13 033139](https://github.com/user-attachments/assets/3d0b141e-8c6b-4aed-a42e-2f8696cd25bc)
Если существуют оба файла compose.yaml и docker-compose.yaml, Compose предпочитает канонический compose.yaml


