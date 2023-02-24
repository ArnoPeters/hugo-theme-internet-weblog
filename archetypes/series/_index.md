---
draft: true
author: ["{{ with .Site.Params.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Params.Author.lastname }}{{ . }}{{ end }}"]
# title: What is the page about in 60-64 characters?
# 64 : "123456789-123456789-123456789-123456789-123456789-123456789-1234"
title: "{{ replace .Name "-" " " | title }}"  # TODO: Verify 'title'
# description: Call to Action including Primary Keyword & Secondary Keyword in max 130 characters
# https://www.metatags.org/all-meta-tags-overview/the-important-meta-tags/meta-name-description/
# 130 chars: "123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-"
description: "" # TODO: Write 'description' 
tags: [] # "string", "string", ... 
date: {{ dateFormat "2006-01-02" .Date }}
publishdate:  {{ dateFormat "2006-01-02" .Date }}
---

TODO: Write SERIES intro
<!--more-->