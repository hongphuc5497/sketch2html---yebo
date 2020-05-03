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

## HTML tree

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
  
  div.tweet
    i.tweet__icon
    h2.tweet__heading
      span.tweet__location
      span.tweet__author
      time.tweet__time
    p.tweet__content
    ul.tweet__pagi
      li.tweet__pagi-item * 3
  
  ul.images
    li.images__block
      div.images__block-item
        div.images__item * 2
          img.images__item-bg
          div.images__item-brand
            img
            h3.image__item-text
      div.images__block-item
        div.images__item
          img.images__item-bg
          div.images__item-brand
            img
            h3.image__item-text

    li.images__block
      div.images__item * 2
        img.images__item-bg
        div.images__item-brand
          img
          h3.image__item-text

    li.images__block
      div.images__block-item
        div.images__item * 2
          img.images__item-bg
          div.images__item-brand
            img
            h3.image__item-text
      div.images__block-item
        div.images__item
          img.images__item-bg
          div.images__item-brand
            img
            h3.image__item-text
  
  div.discover
    a.discover__btn
```
