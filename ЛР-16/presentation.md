---
## Front matter
lang: ru-RU
title: Лабораторная работа 16
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

Получить навыки работы с программным средством Fail2ban для обеспечения базовой защиты от атак типа «brute force».

# Выполнение лабораторной работы

## Защита с помощью Fail2ban

![установка службы](image/01.png){ #fig:001 width=70% height=70%}

## Защита с помощью Fail2ban

![файл /etc/fail2ban/jail.d/customisation.local](image/02.png){ #fig:002 width=70% height=70%}

## Защита с помощью Fail2ban

![лог службы fail2ban](image/03.png){ #fig:003 width=70% height=70%}

## Проверка работы Fail2ban

![статус службы](image/04.png){ #fig:004 width=70% height=70%}

## Проверка работы Fail2ban

![статус службы](image/05.png){ #fig:005 width=70% height=70%}

## Проверка работы Fail2ban

![опция ignore](image/06.png){ #fig:006 width=70% height=70%}

## Результаты выполнения лабораторной работы

Приобретены практические навыки работы с fail2ban