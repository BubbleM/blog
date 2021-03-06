 !DOCTYPE 文档类型  告知浏览器使用哪种HTML或XHTML规范   其中DTD为文档类型定义，里面包含了文档的规则，浏览器根据定义的DTD来解释页面的标识，并展现出< !DOCTYPE html>

该标签可声明三种DTD类型：
- 严格版本 XHTML Strict DTD
>干净的标记，免于表现层的混乱
- 过渡版本  Transitional DTD
>可包含W3C期望移入样式表的呈现属性和元素。如果用户使用了不支持层叠样式表CSS的浏览器，以至于不得不使用HTML的呈现特性时，用过渡版本
- 基于框架的HTML版本 Frameset DTD
>被用于带有框架的文档。除Frameset元素取代了body元素之外，Frameset DTD等同于Transitional DTD

假如文档中的标记不能遵循DOCTYPE声明中所指定的DTD，这个文档除了不能通过代码校验之外，还有可能无法在浏览器中正确显示。

### 常用的声明
> 在 HTML 4.01 中有三种 <!DOCTYPE> 声明。在 HTML5 中只有一种.
> 在 HTML 4.01 中，<!DOCTYPE> 声明引用 DTD，因为 HTML 4.01 基于 SGML。DTD 规定了标记语言的规则，这样浏览器才能正确地呈现内容。
HTML5 不基于 SGML，所以不需要引用 DTD。

1. HTML5 
```
<!DOCTYPE html>
```
2. HTML4.01
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
```
3. XHTML 1.0
```
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

详细参考http://www.w3school.com.cn/tags/tag_doctype.asp
