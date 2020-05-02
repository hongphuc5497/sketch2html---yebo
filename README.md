# Yebo - sketch2html

## File structure

```file structure
app
|- fonts
|
|- images
|
|- styles
|    |- fontawesome.css
|    |- reset.css
|    `- style.css
|
`- index.html
```

## HTML Tree

```html
.wrapper
  header.header
    nav.nav
      ul.nav__list
        li.nav__item * 6
          a.nav__link
            img.nav__logo * 1
  div.feature
    div.feature__header
      img.feature__img-top
      h2.feature__heading
      p.feature__header-desc
    ul.feature__list
      li.feature__item * 2
        div.feature__item-img
          img.img__bg
          img.img__brand
        div.feature__item-content
          div.feature__item-content-top
            img.feature__img-top
            h3.feature__heading
            p.feature__item-text
          div.feature__item-content-bottom
            img.img__bg
      li.feature__item
        div.feature__item-img
          img.img__bg
          img.img__brand
        div.feature__item-content
          div.feature__item-content-top
            img.feature__img-top
            h3.feature__heading
            p.feature__item-text
          div.feature__item-content-bottom
            img.img__bg
        div.feature__item-img
          img.img__bg
```
