---
## Front matter
lang: ru-RU
title: Лабораторная работа 9
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

Приобретение практических навыков по установке и простейшему конфигурированию POP3/IMAP-сервера.

# Выполнение лабораторной работы

## Конфигурация dovecot

![файл dovecot.conf](image/01.png){ #fig:001 width=70% height=70%}

## Конфигурация dovecot

![файл auth-system.conf.ext](image/03.png){ #fig:003 width=70% height=70%}

## Конфигурация dovecot

![файл auth-system.conf.ext](image/04.png){ #fig:004 width=70% height=70%}

## Настрока Firewall

![Настрока Firewall](image/05.png){ #fig:005 width=70% height=70%}

## Проверка работы

![конфигурация почтового клиента](image/06.png){ #fig:006 width=70% height=70%}

## Проверка работы

![конфигурация почтового клиента](image/07.png){ #fig:007 width=70% height=70%}

## Проверка работы

![отправка письма](image/08.png){ #fig:008 width=70% height=70%}

## Проверка работы

![подключение по telnet](image/09.png){ #fig:009 width=70% height=70%}

## Результаты выполнения лабораторной работы

Приобретены практические навыки по установке и конфигурированию SMTP-сервера.