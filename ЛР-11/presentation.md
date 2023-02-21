---
## Front matter
lang: ru-RU
title: Лабораторная работа 11
author: Ярметов Камран
institute: Российский Университет Дружбы Народов
date: 17 февраля, 2023,, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

## Цель лабораторной работы

Приобретение практических навыков по настройке удалённого доступа к серверу с помощью SSH. 

# Выполнение лабораторной работы

## Тестирование SSH-авторизации

![подключение суперпользователя](image/01.png){ #fig:001 }

## Тестирование SSH-авторизации

![подключение суперпользователя](image/02.png){ #fig:002 }

## Тестирование SSH-авторизации

![подключение пользователя](image/03.png){ #fig:003 }

## Конфигурация SSH

![файл /etc/ssh/sshd_config](image/04.png){ #fig:004 width=70% height=70%}

## Настройка дополнительных портов

![подключение на 2022 порт](image/05.png){ #fig:005 }

## Настройка удалённого доступа по SSH по ключу 

![подключение при помощи ключа](image/06.png){ #fig:006 }

## Перенаправление портов

![перенаправлен порт 8080](image/07.png){ #fig:007 width=70% height=70%}

## Удаленное выполнение команд

![выполнение команд hostname и ls](image/08.png){ #fig:008 width=70% height=70%}

## Удаленный запуск приложения

![запуск firefox по ssh](image/09.png){ #fig:009 width=70% height=70%}

## Результаты выполнения лабораторной работы

Приобретены практические навыки по работе с ssh и перенаправлением портов.