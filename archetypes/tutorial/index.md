---
draft: true
slug: "{{lower (replace .Name " " "-") }}"  # TODO: Tutorial: Check SLUG.
author: ["{{ with .Site.Params.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Params.Author.lastname }}{{ . }}{{ end }}"]
title: "{{ replace .Name "-" " " | title }}"  # TODO: Tutorial: Check title. What is the page about in 60-64 characters?
description: "" # TODO: Tutorial: Write Description. Call to Action including Primary Keyword & Secondary Keyword in max 130 characters
                # https://www.metatags.org/all-meta-tags-overview/the-important-meta-tags/meta-name-description/
#summary: "" #TODO: only use when <!--more--> is not used

date: {{ .Date }}
publishdate: {{ .Date }}
#coverImage: "cover.png"
#coverImageAlt: "cover alt Text"
tags: [] # "string", "string", ... # TODO: Tutorial: Write Tags
categories: ["Tutorial"] # TODO: Tutorial: Write Tags
---

TODO: Tutorial. Write Summary. 
_WHY are we doing WHAT in 2 or 3 sentences. Think about what process or workflow is made possible, and the summary of what steps will be taken to do so._

<!--more-->

Why

When

How To

Possible choices
Pro and Cons
Chosen one


# Prerequisites & preparations

- Uses ... (how to verify you have this in the correct version) . Install / upgrade
- Uses ... (how to verify you have this in the correct version) . Install / upgrade200200000000000000000000
TODO: Preparations (when starting from scratch)

## Starting point (Implementation)
Step-by-step
- bricks n pieces
- final product

## Conclusion
TODO: Lessons learned
TODO: Call to action? 