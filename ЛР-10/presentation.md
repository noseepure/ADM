---
## Front matter
lang: ru-RU
title: Лабораторная работа 10
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

Приобретение практических навыков по конфигурированию SMTP-сервера в части настройки аутентификации

# Выполнение лабораторной работы

## Настройка LMTP в Dovecot

![файл dovecot.conf](image/01.png){ #fig:001 width=70% height=70%}

## Настройка LMTP в Dovecot

![файл 10-master.conf](image/02.png){ #fig:002 width=70% height=70%}

## Настройка LMTP в Dovecot

![файл 10-auth.conf](image/03.png){ #fig:003 width=70% height=70%}

## Проверка работы

![отправка письма](image/04.png){ #fig:004 width=70% height=70%}

## Настройка SMTP-аутентификации

![файл 10-master.conf](image/05.png){ #fig:005 width=70% height=70%}

## Настройка SMTP-аутентификации

![файл master.cf](image/06.png){ #fig:006 width=70% height=70%}

## Проверка работы

![telnet авторизация](image/07.png){ #fig:007 width=70% height=70%}

##  Настройка SMTP over TLS 

![конфигурация postfix](image/08.png){ #fig:008 width=70% height=70%}

##  Настройка SMTP over TLS 

![файл master.cf](image/09.png){ #fig:009 width=70% height=70%}

## Проверка работы

![telnet авторизация](image/10.png){ #fig:010 width=70% height=70%}

## Проверка работы

![Работа почтового клиента](image/11.png){ #fig:011 width=70% height=70%}

## Результаты выполнения лабораторной работы

Приобретены практические навыки по установке и конфигурированию SMTP-сервера.