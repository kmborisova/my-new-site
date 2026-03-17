---
title: "Все посты"
date: 2025-03-17
draft: false
---

# Все посты

{{ range .Pages }}
* [{{ .Title }}]({{ .RelPermalink }}) — {{ .Date.Format "2006-01-02" }}
{{ end }}
