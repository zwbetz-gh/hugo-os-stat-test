---
title: "Hugo's os.Stat Function"
date: 2018-10-31T09:46:38-05:00
draft: false
---

Hugo's `os.Stat` function is useful for getting info about a file. For example: 

## This code

```
{{ $file := "data/links.json" }}
{{ $stat := os.Stat $file }}
File Name: {{ $stat.Name }}
File Size: {{ $stat.Size }} bits
File Mode: {{ $stat.Mode }}
File ModTime: {{ $stat.ModTime }}
File IsDir: {{ $stat.IsDir }}
```

## Gives this output

{{< os-stat "data/links.json" >}}