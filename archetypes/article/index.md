---
draft: true
slug: "{{lower (replace .Name " " "-") }}"  # TODO: Article: Check SLUG.
author: ["{{ with .Site.Params.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Params.Author.lastname }}{{ . }}{{ end }}"]
title: "{{ replace .Name "-" " " | title }}"  # TODO: Article: Check title. What is the page about in 60-64 characters?
description: "" # TODO: Article: Write Description. Call to Action including Primary Keyword & Secondary Keyword in max 130 characters
                # https://www.metatags.org/all-meta-tags-overview/the-important-meta-tags/meta-name-description/
#summary: "" #TODO: only use when <!--more--> is not used
tags: [] # "string", "string", ... # TODO: Article: Write Tags
date: {{ .Date }}
publishdate: {{ .Date }}
#coverImage: "cover.png"
#coverImageAlt: "cover alt Text"
---
TODO: Article: Write Summary
<!--more-->

TODO: Article: Verify type. If this is to be a tutorial, use ```hugo new --kind tutorial article/name-of-your-article```

TODO: Article: Write Content
