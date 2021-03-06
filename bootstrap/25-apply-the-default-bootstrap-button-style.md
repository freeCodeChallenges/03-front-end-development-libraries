# <center>25 - Apply the Default Bootstrap Button Style</center>

[Previous page](24-add-elements-within-your-bootstrap-wells.md) | [Next page](26-create-a-class-to-target-with-jquery-selectors.md)

#### [Home - React](./README.md)



Bootstrap has another button class called `btn-default`.

Apply both the `btn` and `btn-default` classes to each of your `button` elements.

# --hints--

You should apply the `btn` class to each of your `button` elements.

```js
assert($('.btn').length > 5);
```

You should apply the `btn-default` class to each of your `button` elements.

```js
assert($('.btn-default').length > 5);
```

# --seed--

## --seed-contents--

```html
<div class="container-fluid">
  <h3 class="text-primary text-center">jQuery Playground</h3>
  <div class="row">
    <div class="col-xs-6">
      <div class="well">
        <button></button>
        <button></button>
        <button></button>
      </div>
    </div>
    <div class="col-xs-6">
      <div class="well">
        <button></button>
        <button></button>
        <button></button>
      </div>
    </div>
  </div>
</div>
```

# --solutions--

```html
<div class="container-fluid">
  <h3 class="text-primary text-center">jQuery Playground</h3>
  <div class="row">
    <div class="col-xs-6">
      <div class="well">
        <button class="btn btn-default"></button>
        <button class="btn btn-default"></button>
        <button class="btn btn-default"></button>
      </div>
    </div>
    <div class="col-xs-6">
      <div class="well">
        <button class="btn btn-default"></button>
        <button class="btn btn-default"></button>
        <button class="btn btn-default"></button>
      </div>
    </div>
  </div>
</div>
```



[Previous page](24-add-elements-within-your-bootstrap-wells.md) | [Next page](26-create-a-class-to-target-with-jquery-selectors.md)

#### [Home - React](./README.md)