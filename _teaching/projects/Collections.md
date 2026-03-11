---
show: true
width: 6
date: 2026-03-10
height: 295px
images:
- src: "assets/images/courses/Game1.gif"
  #title: Project 1
  desc: Project 1
  link: https://picsum.photos/
- src: "assets/images/courses/Game2.gif"
  #title: Photo 2
  desc: Project 2
- src: "assets/images/courses/Game3.gif"
  #title: Project 3
  desc: Project 3
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
