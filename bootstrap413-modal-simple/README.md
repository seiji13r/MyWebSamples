# Bootstrap 4.0 NavBar Example

```html
<!-- Emmet Basic Structure -->

<!-- Main Container (Button) -->
button.btn [data-toggle="modal" data-target="#myModal"]

<!-- Modal -->
.modal.fade#myModal
    .modal-dialog
        .modal-content
            .modal-header
                h2.modal-title
                button.close [data-dismiss="modal"]
                    span  &times;
            .modal-body
            .modal-footer
                button.close [data-dismiss="modal"]
                    span (Close Modal)

```

```html

```
## Closing the Modal
Add the buttons with the attribute `data-dismiss="modal"`

## Fading the Modal in and Out
By just adding the class fade into the modal div whe have the modal fading when showing and hiding.
`.modal.fade#myModal`
```html
    <div class="modal fade" id="myModal"></div>
```

## Java Script Notes
The behavior added when the Modal is Shown is as follows
`div.modal` Container will be added the `show` class and also and inline style of diplay: block.
Also at the very bottom "just before `<body>` closes" a new container will be automatically added.
`<div class="modal-backdrop show"></div>`

When Modal is hidden this states are toggled.
`div.modal` Container will remove the `show` class and also and inline style of diplay: none.



[Official Documentation](https://getbootstrap.com/docs/4.1/components/navbar/)

[Video Reference](https://youtu.be/N3RK2dZpQXs)

[Academind Channel](https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w)