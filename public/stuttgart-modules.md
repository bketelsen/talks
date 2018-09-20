# Go Modules

[twitter]: # (@bketelsen)
[event]: # (Stuttgart Go Meetup)
[eventurl]: # (https://www.meetup.com/Stuttgart-Gophers/)
[title]: # (Go Modules)
[image]: # (/images/logo.png)
[imagealt]: # (Stuttgart Go Meetup)
[date]: # (September 20, 2018)

### Simplify Go Development

<!-- .slide: data-transition="zoom" -->
Slides [https://cda.ms/FV](https://cda.ms/FV)
---

## The Basics

- [Go Modules Wiki Page](https://cda.ms/FN)

---

## Quick tips

- There is also a speaker view, with notes - press '`s`'
- Press '`?`' with focus on the presentation for shortcuts
- <em>You can use html when necessary</em>
- Share the 'Present' URL with anyone you like!

Note:
- Anything after `Note:` will only appear here

---

## More markdown (fragments)

* static text
* fragment <!-- .element: class="fragment" -->
* fragment grow <!-- .element: class="fragment grow" -->
* fragment highlight-red <!-- .element: class="fragment highlight-red" -->
* press key down <!-- .element: class="fragment fade-up" -->

--

## More markdown (tables)

****

|h1|h2|h <!-- .element: class='fragment' -->
|-|-| <!-- .element: class='fragment' -->
|a|b| <!-- .element: class='fragment' -->

****

--

## More markdown (code)

```
version: '2'
services:
  slides:
    image: msoedov/hacker-slides

    ports:
      - 8080:8080
    volumes:
      - ./slides:/app/slides
    restart: always

    environment:
     - USER=bob
     - PASSWORD=pa55

```

--

## Local images

![demoPicture](/images/demo.png)

Copy images into slides/images/ & include with MD:

```
![demoPicture](/images/demo.png)

```
or HTML:

```
<img src="/images/demo.png">

```


---

## Learn more

- [RevealJS Demo/Manual](http://lab.hakim.se/reveal-js)
- [RevealJS Project/README](https://github.com/hakimel/reveal.js)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)

