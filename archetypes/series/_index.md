---
draft: true
author: ["{{ with .Site.Params.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Params.Author.lastname }}{{ . }}{{ end }}"]
title: "{{ replace .Name "-" " " | title }}"
tags: [] # "string", "string", ... 
date: {{ .Date }}
publishdate:  {{ .Date }}
---

TODO: Write SERIES intro
<!--more-->