----
title: JavaScript snippet
date: 2019-06-20
---

# 背景画像削除のブックマークレット

```javascript
javascript:(function(){document.getElementsByTagName('html')[0].style.backgroundImage='url()';})();
```