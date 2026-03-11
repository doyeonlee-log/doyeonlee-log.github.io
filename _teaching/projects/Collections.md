---
show: true
width: 8
date: 2026-03-10
height: 295px
images:
- src: "assets/pictures/courses/Game1.gif"
  title: Project 1
  #desc: Description 1.
  link: https://picsum.photos/
- src: "assets/pictures/courses/Game2.gif"
  title: Photo 2
  #desc: Description 2
- src: "assets/pictures/courses/Game3.gif"
  title: Project 3
  #desc: Description 2
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
