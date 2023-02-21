---
## Front matter
lang: ru-RU
title: Лабораторная работа 13
author: Камила Мухтарова НПИбд-01-20
institute: Российский Университет Дружбы Народов
date: 21 декабря, 2022, Москва, Россия

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

Приобретение навыков настройки сервера NFS для удалённого доступа к ресурсам. 

# Выполнение лабораторной работы

## Настройка сервера NFSv4 

![Настройка сервера](image/01.png){ #fig:001 width=70% height=70%}

## Настройка сервера NFSv4 

![Подключение клиента](image/02.png){ #fig:002 width=70% height=70%}

## Монтирование NFS на клиенте

![файл /etc/fstab](image/03.png){ #fig:003 width=70% height=70%}

## Монтирование NFS на клиенте

![Монтирование](image/04.png){ #fig:004 width=70% height=70%}

## Подключение каталогов к дереву NFS

![файл /etc/exports](image/05.png){ #fig:005 width=70% height=70%}

## Подключение каталогов к дереву NFS

![файл /etc/fstab](image/06.png){ #fig:006 width=70% height=70%}

## Подключение каталогов к дереву NFS

![Монтирование](image/07.png){ #fig:007 width=70% height=70%}

## Подключение каталогов для работы пользователей 

![Настройка сервера](image/08.png){ #fig:008 width=70% height=70%}

## Подключение каталогов для работы пользователей 

![файл /etc/exports](image/09.png){ #fig:009 width=70% height=70%}

## Подключение каталогов для работы пользователей 

![файл /etc/fstab](image/10.png){ #fig:010 width=70% height=70%}

## Подключение каталогов для работы пользователей 

![Монтирование](image/11.png){ #fig:011 width=70% height=70%}

## Результаты выполнения лабораторной работы

Приобретены практические навыки по настройке службы NFS.