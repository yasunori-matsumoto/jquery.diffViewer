#jquery.diffviewer

## example
1. Create before, after html node
  ```
  <div class="parent">
    <p class="before"><img src="a.png" alt="a"></p>
    <p class="after"><img src="b.png" alt="a"></p>
  </div>
  ```
  You can add separator node (optional)
  ```
    <div class="parent">
      <p class="before"><img src="a.png" alt="a"></p>
      <p class="after"><img src="b.png" alt="a"></p>
      <div class="separator"></div>
  </div>
  ```
1. Set width & height
  ```
  .before, .after {
    position: relative;
    width: 640px;
    height: 320px;
  }
  ```
1. Runch  
  ```
  $('.parent').diffViewer();
  ```

***

## options
```
$('.parent').diffViewer({before:'.before', after:'.after'});
```

1. <dl>
<dt>before<dt>
<dd>set before class name.</dd>
<dd>*default : .before*</dd>
</dl>
1. <dl>
  <dt>after<dt>
  <dd>set after class name.</dd>
  <dd>*default : .after*</dd>
  </dl>
1. <dl>
  <dt>separator (optional)<dt>
  <dd>set separator class name</dd>
  <dd>*default : .after*</dd>
  </dl>

##version
- 1.0 - create library