# Bootstrap 4.0 NavBar Example

```html
<!-- Emmet Basic Structure -->
nav.navbar.navbar-expand
    a.navbar-brand
    button.navbar-toggle[data-toggle="collapse" data-target="#navbarMenu"]
        span.navbar-toggler-icon
    div.collapase.navbar-collapse#navbarMenu
        ul.navbar-nav
            li.nav-item
                a.nav-link
            li.nav-item
                a.nav-link

<!-- Navbar Colors -->
nav.navbar.navbar-light.bg-light
nav.navbar.navbar-dark.bg-dark
<!-- Menu Options line up to the left -->
ul.navbar-nav.mr-auto
<!-- Menu Options line up to the right -->
ul.navbar-nav
or
ul.navbar-nav.ml-auto

<!-- Collapsing Menu Elements when in regular Browser -->
<!-- ul.navbar need to be wrapped by the following -->
div.collapase.navbar-collapse
<!-- and nav need the the class navbar-expand-sm-->
nav.navbar.navbar-expand-sm

<!-- Add Toggle Button [Including the Sandwitch Icon]-->
button.navbar-toggle[data-toggler=collapse]
    span.navbar-toggler-icon

<!-- Bound the Toggle Sandwitch Button with the Colapse Menu -->
button.navbar-toggle[data-toggle="collapse" data-target="#navbarMenu"]
        span.navbar-toggler-icon
    div.collapase.navbar-collapse#navbarMenu
        ul.navbar-nav

```

```html
    
```

```html

```
[Official Documentation](https://getbootstrap.com/docs/4.1/components/navbar/)

[Reference](https://youtu.be/23bpce-5s8I)

[Academind Channel](https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w)