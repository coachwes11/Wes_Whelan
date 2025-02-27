---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
price: ${{ printf "%.2f" .Price }}/day
draft: true
author:
tags:
image:
description:
toc:
---
