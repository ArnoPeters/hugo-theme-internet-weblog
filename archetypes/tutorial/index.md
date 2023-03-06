---
draft: true
slug: "{{lower (replace .Name " " "-") }}"  # TODO: Tutorial: Check SLUG.
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
categories: ["Tutorial"] # TODO: Tutorial: Write Tags
---

TODO: Tutorial. Write Summary. 
_What problem are we solving, using what steps in 2 or 3 sentences._

<!--more-->

TODO: Tutorial. Context. 
- When does this apply? ???????
- Possible choices
- Pro and Cons
- Chosen one

## Starting point (Implementation)
TODO: Preparations (when starting from scratch)
- Uses ... (how to verify you have this in the correct version) . Install / upgrade
- Uses ... (how to verify you have this in the correct version) . Install / upgrade200200000000000000000000

Step-by-step
- bricks n pieces
- final product

## Conclusion
TODO: Lessons learned
TODO: Call to action? 


## Further reading? 
Should this be here? 
Subfile? 