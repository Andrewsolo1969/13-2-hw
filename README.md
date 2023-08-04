

# Домашнее задание к занятию 13.2 «Защита хоста» - Соловьёв Андрей SYS-18

---

## Задание 1

- Установите eCryptfs.
- Добавьте пользователя cryptouser.

![User_cryptouser.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/User_cryptouser.PNG)

В домашнем каталог пользователя cryptouser созданы 123, 456

![touch.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/touch.PNG)


- Зашифруйте домашний каталог пользователя с помощью eCryptfs.

Миграция домашнего каталога пользователя:
sudo ecryptfs-migrate-home -u cryptouser

![migr.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/migr.PNG)

Зашифрованная домашняя директория пользователя cryptouser


![crypto1.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/crypto1.PNG)





В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

До шифрования

![before.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/before.PNG)

После шифрования

![after.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/after.PNG)


## Задание 2

- Установите поддержку LUKS.

 Подготовка

 ![z21.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/z21.PNG)

- Создайте небольшой раздел, например, 100 Мб.

 ![gpart.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/gpart.PNG)


- Зашифруйте созданный раздел с помощью LUKS.

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.


Подготовка, монтирование и форматирование раздела



![z23.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/z23.PNG)


Монтирование «открытого» раздела и зашифрованный раздел:


![z24.PNG](https://github.com/Andrewsolo1969/13-2-hw/blob/main/img/z24.PNG)
























 
