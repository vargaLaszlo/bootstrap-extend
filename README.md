# Bootstrap Extend

Missing parts of Bootstrap 4.x

## Installation

### SCSS

Include bootstrpa-extend after bootstrap

```scss
@include './path-to-bootstrap/bootstrap';
@include './path-to-bootstrap-extend/bootstrap-extend'

```

## Components

### Vertical input group

```html
<div class="input-group vertical-input-group">
    <div class="input-group">
        <span class="input-group-addon">One</span>
        <select class="form-control"><option>1</option></select>
    </div>
    <div class="input-group">
        <span class="input-group-addon">One</span>
        <select class="form-control"><option>1</option></select>
    </div>
</div>
```

## Utilities

### Text wrap

```html
<p class="text-wrap">Wrap me!!!</p>
```

### Responsive sizing

```html
<div class="w-auto w-xs-25 w-sm-33 w-md-50 w-lg-100"></div>

<div class="h-auto h-xs-25 h-sm-33 h-md-50 h-lg-100"></div>
```
