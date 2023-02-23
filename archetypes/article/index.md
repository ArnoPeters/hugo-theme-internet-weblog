---
draft: true
slug: "{{lower (replace .Name " " "-") }}"  # TODO: Article: Check SLUG.
author: ["{{ with .Site.Params.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Params.Author.lastname }}{{ . }}{{ end }}"]
# title: What is the page about in 60-64 characters?
# 64 : "123456789-123456789-123456789-123456789-123456789-123456789-1234"
title: "{{ replace .Name "-" " " | title }}"  # TODO: Verify 'title'
# description: Call to Action including Primary Keyword & Secondary Keyword in max 130 characters
# https://www.metatags.org/all-meta-tags-overview/the-important-meta-tags/meta-name-description/
# 130 chars: "123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-"
description: "" # TODO: Write 'description' 
#summary: "" #TODO: only use when <!--more--> is not used
date: {{ .Date }}
publishdate: {{ .Date }}
#coverImage: "cover.png"
#coverImageAlt: "cover alt Text"
tags: [] # "string", "string", ... # TODO: Tutorial: Write Tags
#categories: ["Tutorial"] # TODO: Tutorial: Write Tags
---
TODO: Article: Write Summary
<!--more-->

TODO: Article: Verify type. If this is to be a tutorial, use ```hugo new --kind tutorial article/name-of-your-article```

TODO: Article: Write Content
