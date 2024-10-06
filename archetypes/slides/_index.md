+++
outputs = ["Reveal"]

draft = true
slug = "{{lower (replace .Name ' ' '-') }}"  # slug property is not working for _index.md, url property is -> https://github.com/gohugoio/hugo/issues/7124
url = "slides/{{lower (replace .Name ' ' '-') }}"
author = ["{{ with .Site.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Author.lastname }}{{ . }}{{ end }}"]
title = "{{ replace .Name '-' ' ' | title }}"
summary = "TODO: Write summary"
description = "TODO: Write description"
tags = [] # "string", "string", ...
date = {{ .Date }}
publishdate = {{ .Date }}
showaboutme = false

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


