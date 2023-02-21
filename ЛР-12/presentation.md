---
## Front matter
lang: ru-RU
title: Лабораторная работа 12
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

Получение навыков по управлению системным временем и настройке синхронизации времени. 

# Выполнение лабораторной работы

## Настройка времени

![команды настройки времени](image/01.png){ #fig:001 width=70% height=70% }

## Управление синхронизацией времени 

![источники для синхронизации часов](image/02.png){ #fig:002 width=70% height=70% }

## Создание собственного NTP-сервера

![файл /etc/chrony.conf](image/03.png){ #fig:003 width=70% height=70% }

## Конфигурация клиента NTP

![файл /etc/chrony.conf](image/04.png){ #fig:004 width=70% height=70%}

## Проверка синхронизации

![проверка синхронизации](image/05.png){ #fig:005 }

## Результаты выполнения лабораторной работы

Приобретены практические навыки по работе со службой синхронизации времени