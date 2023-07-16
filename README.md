# Домашнее задание к занятию «Что такое DevOps. СI/СD» - Твердяков Михаил

### Задание 1

**Что нужно сделать:**

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2018-52-12.png)

2. Установите на машину с jenkins [golang](https://golang.org/doc/install).

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-01-37.png)

3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-05-22.png)

4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```.

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-14-01.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-14-20.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-16-23.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-16-35.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-16-49.png)

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---

### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-50-56.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-51-23.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-51-29.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-51-38.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-51-48.png)

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-16%2019-55-43.png)

2. Создайте raw-hosted репозиторий.

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-17%2001-06-38.png)

3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-17%2001-07-01.png)

4. Загрузите файл в репозиторий с помощью jenkins.

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-17%2001-07-38.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-17%2001-07-55.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-17%2001-08-04.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-17%2001-08-14.png)

![png](https://github.com/tverdyakov/8-02-hw/blob/main/screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-07-17%2001-08-29.png)

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---
## Дополнительные задания* (со звёздочкой)

Их выполнение необязательное и не влияет на получение зачёта по домашнему заданию. Можете их решить, если хотите лучше разобраться в материале.

---

### Задание 4*

Придумайте способ версионировать приложение, чтобы каждый следующий запуск сборки присваивал имени файла новую версию. Таким образом, в репозитории Nexus будет храниться история релизов.

Подсказка: используйте переменную BUILD_NUMBER.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.
