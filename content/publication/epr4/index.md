---
<div style="text-align: justify;font-family:serif;font-size:25px"> 
title: "Mankind invented a system to cope with the fact that we are so intrinsically lousy at manipulating numbers. It's called the graph."
subtitle: "(c) Charlie Munger"
</div>:

authors:
- Aleksandra Butneva
- Political Science Students in Fall 2020
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-10-20T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "*First steps in coding graphs.*"
publication_short: ""

abstract: 

# Summary. An optional shortened abstract.
summary: The magic of powerful plots.

tags:
- data science
- R
- data visualization

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Pixabay*](https://pixabay.com/de/)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<div style="text-align: justify;font-family:serif;font-size:18px;"> 

When I just started my journey with R, I sincerely did not understand why the graphs are so important as everybody talks about them. The academic truth is that graphs are more than important – they are pivotal. If a scientist is a wizard, data visualization part is his/her magic wand. **Graphs depict anticipated trends and relationships, reveal outliers, deliver descriptive and causal insides about the data**.
From my understanding, creating basic plots can be learned more easily than it is commonly believed by students who study humanities and have absolutely no experience in coding. Let me give you a non-technical introduction into data visualization with R (assuming that you do not know what R is):

1.	**All you need is to install R and RStudio on your PC and load/create some data to visualize it** – google how to do it and maybe watch a short introductory tutorial.

2.	**The next step is to learn basic commands**: *install.packages(ggplot)* and *library(ggplot)*. Imagine that you want to borrow a book in a library, so you first pick the desired book from a shelf (i.e., “install the package”) and then show it to the librarian so that he/she notes your book as borrowed in the system or activates it (the “library” part of our code). So, we need a book called “ggplot” that allows creating beautiful graphs with intuitive commands.

3.	**Understand the structure of code**. Ggplot works with labels, so it is necessary to tell him what the basic layer is and then include more sophisticated code. For the beginners, this implies following the principle of minimal effort: **data/axes first, lines/points/theme second, custom titles/text/legend/miscellaneous last**. In other words, we need to tell our graph-builder that (1) we want to visualize particular data and one/two (or more) variables, which should be plotted along X and Y axes; (2) we then add a line or data points to our XY-plane that was designed in the first step and choose a background; (3) and we do everything else once the basic structure is established.

4.	**Understand a baseline coding example and not forget about using “+” for each layer**. Finally, you should know what the commands below do to create a line graph (I use # to comment):

*ggplot(my_data*                                                                 # specify data

*aes(x = independent_var, y = dependent_var)) +*                                 # specify variables
 
*geom_line() +*                                                                  # draw a line

*theme_minimal() +*                                                              # choose the background

*ggtitle("My Title")*                                                            # add a title

If you can understand those commands, you are well prepared to read ggplot2 tutorials and master data visualization. Good luck!

 *Want to know more data visualization insides? Take a look at my [presentation](https://aleksandra-butneva.netlify.app/files/Tutorial_6.pdf) from Fall 2020.*
 
**

</div>
