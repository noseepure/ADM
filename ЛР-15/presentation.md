---
## Front matter
lang: ru-RU
title: Лабораторная работа 15
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

Получение навыков по работе с журналами системных событий.

# Выполнение лабораторной работы

## Настройка сервера сетевого журнала

![файл /etc/rsyslog.d/netlog-server.conf](image/01.png){ #fig:001 width=70% height=70%}

## Настройка сервера сетевого журнала

![Настройка файрвола](image/02.png){ #fig:002 width=70% height=70%}

## Настройка клиента сетевого журнала 

![файл /etc/rsyslog.d/netlog-client.conf ](image/03.png){ #fig:003 width=70% height=70%}

## Просмотр журнала

![Просмотр системных сообщений](image/04.png){ #fig:004 width=70% height=70%}

## Результаты выполнения лабораторной работы

Приобретены практические навыки по работе с журналами системных событий.