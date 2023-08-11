#### 1. 标题&#x20;

```java
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

#### 2. 字体

```java
*斜体文本*
**粗体文本**
***粗斜体文本***
```

#### 3. 换行

```java
在结尾加上两个空格
```

#### 4. 分割线

```
---
```

#### 5. 删除线

```
~~被删除的文字~~
```

#### 6. 下划线

```
<u>带下划线文本</u>
```

#### 7. 列表

```
无序列表
* 第一点
* 第二点
* 第三点

有序列表
1. 第一点
2. 第二点
3. 第三点

列表间可嵌套
```

#### 8. 区块引用

```
> 区块引用

区块间可嵌套，区块与列表间也可嵌套
```

#### 9. 代码区块

````
小区块:
`直接用反引包起来`

大区块: 用 ``` 包裹一段代码，并指定一种语言（也可以不指定）
```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```
````

#### 10. 链接

```
[链接名称](链接地址) 或 <链接地址>


高级链接
我们可以通过变量来设置一个链接，变量赋值在文档末尾进行：
[Google][1]
[Runoob][runoob]
文档末尾：
[1]: http://www.google.com/
[runoob]: http://www.runoob.com/
```

#### 11. 图片

```
![图片描述，可写可不写，但是中括号要有](C:\Users\28982\Desktop\7qrbg5xpv5\图片地址，本地链接或者URL地址。)
```

#### 12. 表格

```
|  表头   | 表头  |
|  ----  | ----  |      
| 单元格  | 单元格 |
| 单元格  | 单元格 |


| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |   （在表格）
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
```

#### 13. 转义

```
用 \ 
```

#### 14. 红色字体

```
<font color='red'> text </font>
```

#### 15. 高亮

```
<mark>highlight</mark>
```

#### 16. 分页

```
<div style="page-break-after:always"></div>
```

#### 17. 脚注

[网址](https://www.runoob.com/markdown/md-paragraph.html#:~\:text=%E6%98%BE%E7%A4%BA%E6%95%88%E6%9E%9C%E5%A6%82%E4%B8%8B%E6%89%80%E7%A4%BA%EF%BC%9A-,%E8%84%9A%E6%B3%A8,-%E8%84%9A%E6%B3%A8%E6%98%AF%E5%AF%B9)

#### 18. 流程图

[网址](https://www.runoob.com/markdown/md-advance.html#:~\:text=Markdown%20%E8%A1%A8%E6%A0%BC-,1%20%E7%AF%87%E7%AC%94%E8%AE%B0,-%E5%86%99%E7%AC%94%E8%AE%B0)

#### 19. 取消超链接下划线

[网址](https://blog.csdn.net/qq_43340547/article/details/120761567)

#### 20. 实现页面内跳转

```
<a href="#funcApply">构造函数.apply()</a> 
[点击跳转](#funcApply)

<span id="funcApply">**apply()方法**</span>
```

#### 21. 表格内换行

```
<br/>
&#xA;
```

#### 22. 占位符

```
&ensp; 或 &#8194; //半角
&emsp; 或 &#8195; //全角
&nbsp; 或 &#160;
```

#### 23. 跳转标题

```
[7.1 客户](#7.1 客户)

锚点：
# xj

跳转：
<a href="#xj">页面内锚点跳转文件的纯文本</a>
```

#### 24. HTML表格模板

```
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-azew{border-color:inherit;font-size:10px;text-align:center;vertical-align:middle;font-size:10px}
.tg .tg-rq3n{background-color:#ffffff;border-color:inherit;text-align:center;vertical-align:middle;font-size:10px}
.tg .tg-mfxt{background-color:#ffffff;border-color:inherit;text-align:left;vertical-align:middle;font-size:10px}
.tg .tg-c6of{background-color:#ffffff;border-color:inherit;text-align:left;vertical-align:top;font-size:10px}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-azew">模块</th>
    <th class="tg-azew">说明</th>
    <th class="tg-azew">相关操作</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-rq3n" rowspan="2">客户</td>
    <td class="tg-mfxt" rowspan="2">客户的相关说明</td>
    <td class="tg-mfxt"><a href="#xjdd">1. 新建订单</a></td>
  </tr>
  <tr>
    <td class="tg-mfxt"><a href="#dydd">2. 打印订单</a></td>
  </tr>
  <tr>
    <td class="tg-rq3n" rowspan="3">销售订单</td>
    <td class="tg-mfxt" rowspan="3">客户提供的订单，记录客户要求的具体产品、数量、价格、交付要求以及其他相关条款和条件 </td>
    <td class="tg-mfxt"><a href="#xjkh">1. 新建客户</a></td>
  </tr>
  <tr>
    <td class="tg-mfxt"><a href="#ckkhzl">2. 查看客户资料</a></td>
  </tr>
  <tr>
    <td class="tg-mfxt"><a href="#cjkhgj">3. 创建客户跟进</a></td>
  </tr> 
  <tr>
    <td class="tg-rq3n" rowspan="3">客户</td>
    <td class="tg-mfxt" rowspan="3">客户的相关说明</td>
    <td class="tg-mfxt"><a href="#xjkh">1. 新建客户</a></td>
  </tr>
  <tr>
    <td class="tg-mfxt"><a href="#ckkhzl">2. 查看客户资料</a></td>
  </tr>
  <tr>
    <td class="tg-mfxt"><a href="#cjkhgj">3. 创建客户跟进</a></td>
  </tr>   
</tbody>
</table>
```


