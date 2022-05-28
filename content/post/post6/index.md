---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Report formatting in markdown"
subtitle: "work in markdown"
summary: ""
authors: []
tags: [interesting]
categories: [informstion]
date: 2022-05-21T12:18:45+03:00
lastmod: 2022-05-21T12:18:45+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Reports with R Markdown

Making plots and being able to write output files is important. However, the most important part of any analysis is communicating your findings effectively! The rmarkdown package is one of the best and easiest ways of doing this. It let’s you create a fancy looking report without ever leaving RStudio. You can interleave your code and plots together with explanation text and formatting you might normally do in a tool like Microsoft Word. You can even make websites with it (like this one!)!

Let’s get started with R Markdown and make ourselves a sweet report.
Creating an R Markdown notebook

In RStudio, go to File -> New File -> R Markdown. It will ask you what you want to call the file - leave the output as HTML for now.

You should see a file open with a lot of text and code already there. This is the default R Markdown document and comes with a lot of pointers about how to do things. For now, save the file as example.Rmd, and hit the “Knit” button.

If everything went well, you should see a nicely formatted webpage/ report pop up in RStudio’s built-in browser. Congratulations, you’ve made your first report!
The stuff between the ---s is called YAML - it’s a markup format that describes what kind of document to make, who wrote it, and other technical bits that’s not actual content in your report. If you want, you can modify it, but let’s leave it be for now.
