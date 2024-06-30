---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
description: "{{ replace .File.ContentBaseName "-" " " | title }} - "
tags: [random, zmiana]
---
