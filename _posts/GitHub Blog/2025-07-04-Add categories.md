---
layout: single
title: "Add categories"
categories: GitHub_Blog
---

# How to categorize posts

- 1. uncomment jekyll-archives code block (_config.yml).
  2. Add _pages derectory in the blog derectory
  3. Add "category-archive.md" file
  4. write following codes
```markdown
---
title: "Category"
layout: categories
permalink: /categories/
author_profile: true
sidebar_main: true
---
```
  4. Edit navigation.yml  
  Change the "title" name as you want & "url" (_data).  
  example)
```yml
  - title: "The Name What You Want"  
       url: /cateroies/
```

  5. Add category name on your posts
  ```markdown
  ---
  layout: single
  title: "sample post"
  categories: The Name of Category You Want
  ---
  ```