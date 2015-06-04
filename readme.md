#jquery.diffviewer

## example
1. create before, after html node
  ```
  <div class="parent">
    <p class="before"><img src="a.png" alt="a"></p>
    <p class="after"><img src="b.png" alt="a"></p>
  </div>
  ```
1. set width & height to parent
  ```
  .parent p {
    position: relative;
    width: 640px;
    height: 320px;
  }
  ```
1. runch
  ```
  $('.parent').diffViewer();
  ```

## options
```
$('.parent').diffViewer({before:'.before', after:'.after'});
```
* before
  set before Node.

* after
  set after Node.

##version
- 1.0 最初の設定を作成