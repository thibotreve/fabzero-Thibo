---
sort: 2
images:
  - title: title
    link: https://via.placeholder.com/200/6ab0de/fff.png
    image: https://via.placeholder.com/200/6ab0de/fff.png
  - title: title
    link: https://via.placeholder.com/200/6ab0de/fff.png
    image: https://via.placeholder.com/200/6ab0de/fff.png
  - title: title
    link: https://via.placeholder.com/200/6ab0de/fff.png
    image: https://via.placeholder.com/200/6ab0de/fff.png
  - title: title
    link: https://via.placeholder.com/200/6ab0de/fff.png
    image: https://via.placeholder.com/200/6ab0de/fff.png
  - title: title
    link: https://via.placeholder.com/200/6ab0de/fff.png
    image: https://via.placeholder.com/200/6ab0de/fff.png
---

# Inclusion of Images via link

## Show image on the internet

![test image internet](https://ingegnomakerspace.github.io/inclusievekets/assets/images/logo.svg)

## Show image from THIS website

Image must be located in **assets** folder and you need to use the variable {% raw %}`{{ site.baseurl }}`{% endraw %} to indicate where this website is located

![test image internet]({{ site.baseurl }}/assets/images/logo.svg)

## Turn your image in a link to a webpage

[![test image internet]({{ site.baseurl }}/assets/images/logo.svg)](https://ingegnomakerspace.github.io/inclusievekets/)

## Turn your image in a link to page of THIS website

You need to use the variable {% raw %}`{{ site.baseurl }}`{% endraw %} to refer to the root of your website. You can use `#` to refer to a header section in that page.

[![test image internet]({{ site.baseurl }}/assets/images/logo.svg)]({{ site.baseurl }}/Lessen/01_Git/A_Markdown/04codes.html#code-highlight)

# Album Images via frontmatter images table

foto vanop het internet

![foto Thibo](https://media-exp1.licdn.com/dms/image/C4E03AQEBkb9GNCWZYg/profile-displayphoto-shrink_200_200/0?e=1604534400&v=beta&t=HPmUTsdglBTbVdHwWsXKnrC0pnPC6wRy8PnMo5GBtyw)

foto van in mijn repository

![foto Thibo]({{ site.baseurl }}/assets/0.jpg)

{% include album.liquid data=page.images %}
