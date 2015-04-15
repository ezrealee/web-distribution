---
title: my markdown
subtitle: this is a subtitle
author: ezrealee
---

# Sample Markdown

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod.

## Text basics

This is *italic* and this is **bold**.  Another _italic_ and another __bold__.

> __Here is some quotation__. Lorem ipsum dolor sit amet, consectetur
> adipisicing elit, sed do eiusmod tempor incididunt ut labore et
> dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.

## Links

This is an [example inline link](http://example.com/) and [another one with a title](http://example.com/ "Hello, world"). And [another][someref] one.

## Code

This is inline code: `some code here`.

```javascript
    <script>
        document.location = 'http://example.com/?q=markdown+cheat+sheet';
    </script>
```

```php
public static function check_img_code()
{
    $qs = $this->request->query();

    return $qs;
}
```

```java
public class HelloWorld {
   public static void main(String[] args) {
       System.out.println("Hello, world!");
   }
}
```

[someref]: http://example.com "rich web apps"
[MarkdownREF]: http://daringfireball.net/projects/markdown/basics
[gfm]: http://github.github.com/github-flavored-markdown/