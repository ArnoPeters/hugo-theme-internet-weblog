+++
outputs = ["Reveal"]

draft = true
slug = "{{lower (replace .Name " " "-") }}"  # slug property is not working for _index.md, url property is -> https://github.com/gohugoio/hugo/issues/7124
url = "slides/{{lower (replace .Name " " "-") }}"
author = ["{{ with .Site.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Author.lastname }}{{ . }}{{ end }}"]
# title = What is the page about in 60-64 characters?
# 64  = "123456789-123456789-123456789-123456789-123456789-123456789-1234"
title = "{{ replace .Name "-" " " | title }}"  # TODO: Verify 'title'
# description = Call to Action including Primary Keyword & Secondary Keyword in max 130 characters
# https://www.metatags.org/all-meta-tags-overview/the-important-meta-tags/meta-name-description/
# 130 chars = "123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-123456789-"
description = "" # TODO: Write 'description' 

summary = "TODO: Write summary"
tags = [] # "string", "string", ...
date = {{ .Date }}
publishdate = {{ .Date }}
showAboutMe = false  #todo: not implemented yet

[reveal_hugo]
#theme = "custom/aps-robot-lung"
#custom_theme = "lib/reveal-hugo/themes/aps-robot-lung.css"
#highlight_theme= "agate"
#custom_css = "custom.css"  # files can be page resource
#custom_js = "custom.js"
+++
# {{ replace .Name "-" " " | title }}
TODO: Write Slide

{{% reveal-hugo/note %}}
TODO: speaker notes
- wat zeg ik

- wat is de conclusie die ik eruit kan trekken

{{% /reveal-hugo/note %}}
