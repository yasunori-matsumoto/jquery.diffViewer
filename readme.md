#jquery.diffviewer

## example
1. Create before, after html node
  ```
  <div class="parent">
    <p class="before"><img src="a.png" alt="a"></p>
    <p class="after"><img src="b.png" alt="a"></p>
  </div>
  ```
  You can add separator (optional)
  ```
    <div class="parent">
      <p class="before"><img src="a.png" alt="a"></p>
      <p class="after"><img src="b.png" alt="a"></p>
      <div class="separator"><p>&nbsp;</p></div>
  </div>
  ```
  
  
1. Set width & height to parent
  ```
  .parent p {
    position: relative;
    width: 640px;
    height: 320px;
  }
  ```
1. Runch
  ```
  $('.parent').diffViewer();
  ```

## options
```
$('.parent').diffViewer({before:'.before', after:'.after'});
```
1. before  
  set before Node.

1. after  
  set after Node.
  
1. sseparator  
  set separator Node (optional)

##version
- 1.0 - create library