# Red line project Simon


I redid the site [zwinrechteroever](http://www.zwinrechteroever.be/), it's from a local history group. The problem with this site is that the styling is chaotic because there is no clear structure.

This is my endproduct: my version of [zwinrechteroever](https://simonrijsselaere.github.io/Redline-project/index.html)

## Pages I adapted

### Homepage

The homepage of this site is a PowerPoint in PDF with 2 images beneath it. There is no explanation what this site is about until you start clicking further.

The client agreed he wanted to have a more simple homepage with basic information, what the group does and where to find them. I also added a simpler banner and navbar to all the pages.

### Museumpage

The carousel displaying pictures is placed partly over the text. The text that was readable was also kind of weird.

I changed the page to 3 divs with the location, content and library so its more clear.

### Contactpage

The contact form on the original page was overflowing out it's box.

I made a new contact form and added the basic contact information.


## What went well

1. using bootstrap to make the sites structure and making it responsive
2. quick advancement in the general layout of the site


## What did not went well

1. Spending sometimes too much time on details. For example I spend too much time adding the 2 images of the logo of the group on both sides. Just using `float-left` and `float-right` didn't work because the image on the right popped to the next line. Apparently you just have to use `clearfix` in the div containing them both and it works. In general I spend too much time looking for small things like this.
2. my site doesnt have that much content, it's not bad in a way that is makes the styling easier but I would have preferred to have more to work with.
