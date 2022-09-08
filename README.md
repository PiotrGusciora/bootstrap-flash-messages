
Responsive Flash messages built with the latest Bootstrap 5. Flash messages provide contextual feedback informations for typical user actions with a handful of responsible and flexible messages boxes.

Check out [Bootstrap Flash messages Documentation](https://mdbootstrap.com/docs/standard/extended/flash-messages) for detailed instructions & even more examples.

## Basic examples

![Bootstrap 5 Flash messages](/assets/basic-examples.png)

#### HTML:
```html

<!-- Trigger buttons -->
<button type="button" id="primary" class="btn btn-primary m-1">Primary</button>
<button type="button" id="secondary" class="btn btn-secondary m-1">Secondary</button>
<button type="button" id="success" class="btn btn-success m-1">Success</button>
<button type="button" id="danger" class="btn btn-danger m-1">Danger</button>
<button type="button" id="warning" class="btn btn-warning m-1">Warning</button>
<button type="button" id="info" class="btn btn-info m-1">Info</button>
<button type="button" id="light" class="btn btn-light m-1">Light</button>
<button type="button" id="dark" class="btn btn-dark m-1">Dark</button>

<!-- Alerts -->
<div
    class="alert fade"
    id="alert-primary"
    role="alert"
    data-mdb-color="primary"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple primary flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
<div
    class="alert fade"
    id="alert-secondary"
    role="alert"
    data-mdb-color="secondary"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple secondary flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
<div
    class="alert fade"
    id="alert-success"
    role="alert"
    data-mdb-color="success"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple success flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
<div
    class="alert fade"
    id="alert-danger"
    role="alert"
    data-mdb-color="danger"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple danger flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
<div
    class="alert fade"
    id="alert-warning"
    role="alert"
    data-mdb-color="warning"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple warning flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
<div
    class="alert fade"
    id="alert-info"
    role="alert"
    data-mdb-color="info"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple info flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
<div
    class="alert fade"
    id="alert-light"
    role="alert"
    data-mdb-color="light"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple light flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
<div
    class="alert fade"
    id="alert-dark"
    role="alert"
    data-mdb-color="dark"
    data-mdb-position="top-right"
    data-mdb-stacking="true"
    data-mdb-width="535px"
    data-mdb-width="535px"
    data-mdb-append-to-body="true"
    data-mdb-hidden="true"
    data-mdb-autohide="true"
    data-mdb-delay="2000"
>
    A simple dark flash message with
    <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
</div>
```
#### JS:
```JS
const triggers = [
  'primary',
  'secondary',
  'success',
  'danger',
  'warning',
  'info',
  'light',
  'dark',
];
const basicInstances = [
  'alert-primary',
  'alert-secondary',
  'alert-success',
  'alert-danger',
  'alert-warning',
  'alert-info',
  'alert-light',
  'alert-dark',
];

triggers.forEach((trigger, index) => {
  let basicInstance = mdb.Alert.getInstance(document.getElementById(basicInstances[index]));
  document.getElementById(trigger).addEventListener('click', () => {
    basicInstance.show();
  });
});
```


## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)

## More examples

[Bootstrap Flash messages static examples:
![Bootstrap 5 Flash messages](/assets/static-examples.png)](https://mdbootstrap.com/docs/standard/extended/flash-messages/#section-static-example)

[Bootstrap Flash messages icons:
![Bootstrap 5 Flash messages](/assets/icons.png)](https://mdbootstrap.com/docs/standard/extended/flash-messages/#section-icons)

[Bootstrap Flash messages dismissing:
![Bootstrap 5 Flash messages](/assets/dismissing.png)](https://mdbootstrap.com/docs/standard/extended/flash-messages#section-dismissing)

___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/content-styles/colors/">Bootstrap Colors</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/utilities/close-button/">Bootstrap Close Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/content-styles/icons/">Bootstrap Icons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/components/alerts/">Bootstrap Alerts</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/layout/containers/">Bootstrap Container</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/components/toasts/">Bootstrap Toasts</a></li>
</ul>
