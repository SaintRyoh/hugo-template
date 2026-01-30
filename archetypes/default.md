---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
# image: /images/post.jpg  # Relative path - staticPath is prepended by theme
---
