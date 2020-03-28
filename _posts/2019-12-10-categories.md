---
title: Creating post categories
subtitle: Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis.
categories: [setup, features]
author: evan
---

Create new post entries in `categories` folder, similar to creating posts, but with following front matter settings:

```yml
---
layout: category
permalink: /setup/basics/
pagination: 
  enabled: true
  permalink: /:num/
  categories:
    values:
      - setup
      - basics
    matching: all
  sort_field: 'title'
  sort_reverse: true
---
```

The permalink has to match the permalink set in `_data/home_categories.yml` file.