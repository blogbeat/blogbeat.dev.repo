---
title: "{{ replace .Name "-" " " | title }}"
subtitle: "{{ replace .Name "-" " " | subtitle }}"
#description: "DESCIPTION"
date: {{ .Date }}
draft: true
author: "blogbeat"
image:   ""
tags:  ["blog"]
categories:  ["tech"]
---
#put text below - only shown if description is empty
