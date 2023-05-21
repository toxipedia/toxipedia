---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: ["",""]
categories: ["{{ getenv "category1" }}","{{ getenv "category2" }}"]
featured_image: {{ getenv "featuredImage" }}
author: 
moleculeURL: {{ getenv "moleculeURL" }}
peptideURL:
---
