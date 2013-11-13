# media-block

Creates a new block-formatting context to
easily create layouts that have a thumbnail
on the left or right and text next to it. The
text will never wrap below the figure.

## Install

```
component install segmentio/media-block
```

## Usage

```html
<div class="media">
  <img class="media-figure"/>
  <div class="media-content">
    This content will never wrap the image
  </div>
</div>
```

Change the direction by using `media-figure-alt`.