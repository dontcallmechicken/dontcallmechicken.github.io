---
date: {{ .Date }}
lastmod: {{ now.Format "2006-01-02" }}
# image: ""
showTableOfContents: false
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
# description: ""
# tags: ["",]
type: "post"
draft: true
---
