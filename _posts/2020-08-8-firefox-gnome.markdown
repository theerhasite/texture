---
layout: post
title:  "Тема adwaita для Firefox"
description: Тема для Firefox
date:   2019-05-23 21:03:36 +0530
categories: Firefox Gnome
---
Браузер Firefox по умолчанию выглядит не-очень красиво,например браузер Epiphany выглядит намного красивее и интегрированнее
Автор темы рассмотренной в статье попытался сделать Firefox более красивым и интегрированным с Gnome 3,и-так,начнём
В-первую очередь  нам нужно установить git,думаю с установкой у вас проблем не возникнет
Далее клонируем репозиторий следующей командой

```
git clone https://github.com/rafaelmardojai/firefox-gnome-theme.git
```
Заходим в директорию с темой
```cd firefox-gnome-theme
```
И собственно,устанавливаем саму тему!

```
./scripts/install.sh
```
**Cкроллбары**
По желанию вы можете установить гномовские скроллбары,для этого выполните следующую команду


```
git clone https://github.com/rafaelmardojai/firefox-gnome-scrollbars.git && cd firefox-gnome-scrollbars
./install.sh
```

