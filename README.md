# treeview
加载必需的文件：
```html
<link type="text/css" rel="stylesheet" href="./treeview.css">
<script type="text/javascript" src="./jquery-1.8.3.min.js"></script>
<script type="text/javascript" src="./treeview.js"></script>
```
HTML格式：
```html
<div class="tree-folders">
    <span>父目录</span>
    <span class="no-child">父目录-无子目录</span>
    <span>多级目录</span>
</div>
<div class="tree-files">
    <span class="no-child">子目录</span>
</div>
<div class="tree-files">
    <div class="tree-folders">
        <span>多级目录-子目录</span>
    </div>
    <div class="tree-files">
        <span class="no-child">多级目录-子目录-子目录</span>
    </div>
</div>
```
引用：
```javascript
$('.container').treeView({defaultOpen:false});
```
