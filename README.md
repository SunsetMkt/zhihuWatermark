# zhihuWatermark
仿知乎隐写水印 参考 https://v2ex.com/t/877614 提供的信息 由GitHub Copilot自动生成

## Example

```html
<script src="zhihuWatermark.js"></script>
<script>
    // 获取timestamp
    var timestamp = new Date().getTime();
    // 获取当前页面的url
    var url = window.location.href;
    var wmClass = insertWatermark(timestamp, url);
    // console.log(wmClass);
</script>
```
