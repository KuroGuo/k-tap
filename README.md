## K-tap

### Quick Examples

```html
<div id="box"></div>
<script src='k-tap.js'></script>
<script>
  var box = document.querySelector('#box');

  box.addEventListener('k.tap', function () {
    alert('taped');
  });
</script>
```