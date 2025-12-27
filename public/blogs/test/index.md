# Typora简明教程

![image-20251206165218361](imgs/封面.png)



## 安装与设置

双击安装程序：`typora1.8.10-setup-x64.exe`

推荐为所有用户安装

<img src="imgs/image-20251206094403772.png" alt="image-20251206094403772" style="zoom:67%;" />

默认安装位置，下一步：

<img src="imgs/image-20251206094628862.png" alt="image-20251206094628862" style="zoom:67%;" />

勾选桌面快捷方式

<img src="imgs/image-20251206094711501.png" alt="image-20251206094711501" style="zoom:67%;" />

点安装

<img src="imgs/image-20251206094727504.png" alt="image-20251206094727504" style="zoom:67%;" />

先不启动，完成安装

<img src="imgs/image-20251206094753275.png" alt="image-20251206094753275" style="zoom:67%;" />

进行偏好设置

<img src="imgs/image-20251206094817744.png" alt="image-20251206094817744" style="zoom:67%;" />

推荐调整的设置都框出来了

<img src="imgs/image-20251206094845611.png" alt="image-20251206094845611" style="zoom:60%;" />



## 标题

### 语法

标题一共有`6`种，对应`h1`到`h6`

```markdown
# 1级标题
## 2级标题
### 3级标题
#### 4级标题
##### 5级标题
###### 6级标题
```

注意`#`后面有一个空格，展示的效果如下：

<img src="imgs/image-20251206095515018.png" alt="image-20251206095515018" style="zoom:67%;" align="left" />

> **注意**
>
> 最多就`6`级，不能再多了！



### 快捷键

<kbd>Ctrl</kbd> + <kbd>1 - 6</kbd>切换到对应级别的标题

<kbd>Ctrl</kbd> + <kbd>0</kbd>将标题切换为普通文本

<kbd>Ctrl</kbd> + <kbd>+ / -</kbd>对标题通过加减改变其级别



#### 跟小卷学习Java编程



## 段落

### 语法

`typora`中的段落分大段落和小段落

大段落直接回车，如：

> **大段落示例**
>
> 跟小卷学编程
>
> 跟小卷学编程

小段落：<kbd>Shift</kbd> + <kbd>Enter</kbd>

> **小段落示例**
>
> 跟小卷学编程
> 跟小卷学编程
> 跟小卷学编程

## 分隔线

> **分隔线语法**
>
> 1. `---`加回车
> 2. `***`加回车

---

***



## 文字修饰

### 语法

> - 加粗：`**文字**`
>
>   <kbd>Ctrl</kbd> + <kbd>B</kbd>，可反转
>
> - 删除线：`~~文字~~`
>
>   <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>5</kbd>，可反转
>
> - 下划线：`<u>文字</u>`
>
>   <kbd>Ctrl</kbd> + <kbd>U</kbd>，可反转
>
> - 斜体：`*文字*`
>
>   <kbd>Ctrl</kbd> + <kbd>I</kbd>，可反转
>
> - 高亮文字：`==文字==`
>
>   要求在【偏好设置】中勾选高亮
>
>   ##### 自定义高亮快捷键
>
>   在【通用】中【打开高级设置】，编辑`conf.user.json`，在`keyBinding`配置项下加：`"Highlight": "Ctrl+Shift+H"`，修改后重启`typora`即可生效

以上操作，选中文字后，用快捷键操作更方便，也可以在界面操作，点工具栏中的【格式】，可反转

<img src="imgs/image-20251206103333061.png" alt="image-20251206103333061" style="zoom:67%;" align="left" />

### 示例

跟小卷**学编程**跟小卷学编程~~跟小卷~~学编程

~~跟小卷学编程~~

跟==<u>小卷</u>==学编程

跟小卷*学编程*

### 转义字符

要输出如下的内容，需要使用`\`来转义

1\*2\*3\*4\*5

\\*

```
1\*2\*3\*4\*5

\\*
```

## 上下标

确保在【Markdown扩展语法】中勾选上标、下标

### 语法

上标：`^n^`

下标：`~2~`

### 示例

x^2^

H~2~O

x~1~^2^

```markdown
x^2^

H~2~O

x~1~^2^
```



## 无序列表

### 操作

创建一级

<kbd>*</kbd> | <kbd>+</kbd> | <kbd>-</kbd> + <kbd>Space</kbd>

在此基础上

<kbd>Enter</kbd>创建同一级

<kbd>Tab</kbd>转成下一级

<kbd>Enter</kbd> + <kbd>Enter</kbd>返回上一级文本，文本换行后再<kbd>Enter</kbd>，则创建同级

当前列表项第一行最后<kbd>Shift</kbd> + <kbd>Enter</kbd>小段落换行，<kbd>Enter</kbd> + <kbd>Backspace</kbd>大段落换行

### 快捷键

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>]</kbd>，生成一级列表项、对列表项大段落生成子项、取消同一级所有的列表项

<kbd>Ctrl</kbd> + <kbd>[</kbd>切换成上一级

<kbd>Ctrl</kbd> + <kbd>]</kbd>切换成下一级



## 有序列表

### 操作

创建一级

<kbd>1</kbd> + <kbd>.</kbd> + <kbd>Space</kbd>

在此基础上

<kbd>Enter</kbd>创建同一级

<kbd>Tab</kbd>转成下一级

<kbd>Enter</kbd> + <kbd>Enter</kbd>返回上一级文本，文本换行后再<kbd>Enter</kbd>，则创建同级

当前列表项第一行最后<kbd>Shift</kbd> + <kbd>Enter</kbd>小段落换行，<kbd>Enter</kbd> + <kbd>Backspace</kbd>大段落换行

### 快捷键

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>[</kbd>，生成一级列表项、对列表项大段落生成子项、取消同一级所有的列表项

<kbd>Ctrl</kbd> + <kbd>[</kbd>切换成上一级

<kbd>Ctrl</kbd> + <kbd>]</kbd>切换成下一级



## 任务列表

### 用法

`- [ ] 待完成任务`

`- [x] 已完成任务`

### 示例

- [ ] 学习Java Web
- [x] 学习Java SE

- [ ] 跟小卷学习obsidian

```markdown
- [ ] 学习Java Web
- [x] 学习Java SE
```

>**自定义任务列表快捷键**
>
>参考[自定义高亮快捷键](#自定义高亮快捷键)
>加配置项：`"Task List": "Ctrl+Shift+T"`



## 区块

### 用法

<kbd>></kbd>，生成区块，可嵌套

### 示例

> **Java核心编程**
>
> 跟小卷一起学习Java基础
> 手把手敲代码
>
> > **关于学习笔记**
> >
> > 学编程不要忘了记笔记
> > `markdown`笔记神器`typora`
>
> Java基础语法
> Java面向对象

```markdown
> **Java核心编程**
>
> 跟小卷一起学习Java基础
> 手把手敲代码
>
> > **关于学习笔记**
> >
> > 学编程不要忘了记笔记
> > `markdown`笔记神器`typora`
>
> Java基础语法
> Java面向对象
```



## 行内代码

### 用法

\`java\`

### 快捷键

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>`</kbd>，生成行内代码或取消生成

跟小卷一起学习`java`核心编程



## 代码块

### 用法

\`\`\`language<kbd>Enter</kbd>

从一些代码编辑器复制过来的代码，粘贴到`typora`中会自动识别为代码块，在右下角输入语言即可。

### 快捷键

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>k</kbd>

```java
String msg = "跟小卷学Java";
System.out.println(msg);
```

```js
let msg = "跟小卷学js"
console.log(msg)
```



## 链接

### 用法

- 直接写链接

- `[链接名称](url)`

  `url`可以是网络地址，如：`https://xxx.xx.com`，也可以是本地资源，可以用相对路径或者绝对路径

  > **file前缀**
  >
  > 标准的文件协议头是`file:///`，但在`markdown`中在尝试用`typora`或`obsidian`软件编辑链接可以开头加`file://`，反而标准的`file:///`在`typora`中不生效，因此在引用本地资源是推荐都加上`file://`

- `[链接名称](url "描述信息")`

- 通过锚点链接到`md`文件的标题

  `[链接名称](#同一个文档中其他标题)`

  `[链接名称](其他md文档路径#某标题)`

### 快捷键

<kbd>Ctrl</kbd> + <kbd>k</kbd>

复制一个链接，选中文字作为链接名称，按快捷键

### 示例

- 直接写链接

  https://www.baeldung.com/ - 专业Java学习网站

- md网络链接

  [baeldung - 专业Java学习网站](https://www.baeldung.com/)

  [baeldung - hover显示标题](https://www.baeldung.com/ "专业Java学习网站")

- md标题链接

  [链接到代码块](#代码块)

  [链接到其他md文档](./test.md#类的继承)

- 本地其他资源链接

  [链接到drawio文件](./test.drawio)

  [绝对地址链接到drawio文件](D:/Study/typora教程/test.drawio)

  加上`file://`

  [链接到drawio文件](file://./test.drawio)

  [绝对地址链接到drawio文件](file://D:/Study/typora教程/test.drawio)

  

## 脚注

### 用法

在要加脚注的文字后面加`[^脚注标识符]`，这里的`标识符`可以是数字也可以是名称，确保唯一即可。

脚注的描述信息，单独成一行，一般放在页面最后，格式如下：

```
[^xxx]: 描述信息，可以换行<br>这是下一行
```



跟着小卷用一套坦克大战[^坦克大战]学习`Java`核心编程[^1]

[^坦克大战]: 仿90坦克实现的一个`Java`窗体应用，目的在于综合运用`Java SE`的各种知识点
[^1]: Java核心编程<br>包含了Java基础语法、集合、多线程、算法与数据结构、`io`、网络编程，<br>面向对象编程以及各种设计模式。



## 图像

### 用法

格式如

`![图片名称](url "描述信息")`

`url`可以是网络地址，比如从网页复制一张图片，https://img.mp.sohu.com/upload/20180815/402eb94f4351492f8dd1284de752abc9_th.jpg，对图片右键复制图片，粘贴过来会显示网络地址；而本地复制的图片，粘贴进来可以显示相对路径并基于该路径生成图片。

以上的复制行为可配置实现：

<img src="imgs/image-20251206132626078.png" alt="image-20251206132626078" style="zoom:58%;" align="left" />

### 快捷键

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd>



### img标签

除了`![]()`语法，也支持`html`的`<img>`标签语法，可以对图片右键：

![image-20251206133204468](imgs/image-20251206133204468.png)

完成图片语法转换以及缩放操作，也可对`<img>`标签加`align`属性进行水平对齐，默认居中，可指定`left`、`right`属性值，需要注意：**默认的缩放操作的`zoom`样式会对`box-shadow`、`border-radius`等样式属性也会缩放，也可以手动替换为`width`属性来避免这一影响**。

### 示例



<img src="https://img.mp.sohu.com/upload/20180815/402eb94f4351492f8dd1284de752abc9_th.jpg" alt="img" width="24%" style="border-radius: 8px;" />



<img src="https://img.mp.sohu.com/upload/20180815/402eb94f4351492f8dd1284de752abc9_th.jpg" alt="img" style="zoom: 18%; border-radius: 2%;" align="left" />



### 自定义样式

#### 主题目录

找到`typora`的主题目录：`~\AppData\Roaming\Typora\themes`，*偏好设置 | 外观 | 打开主题目录*

#### 全局样式文件

新建自定义全局样式文件：`base.user.css`，粘贴下面的样式：

```css
img {
    box-shadow: rgba(0, 0, 0, 0.4) 0px 30px 90px;
}
```

样式可参考[漂亮的css盒式阴影示例](https://getcssscan.com/css-box-shadow-examples)



## 表格

### 语法

```markdown
| aa   | bb   | cc   |
| ---- | ---- | ---- |
| 1    | 4    | 7    |
| 2    | 5    | 8    |
| 3    | 6    | 9    |
```



### 快捷键

<kbd>Ctrl</kbd> + <kbd>T</kbd>

### 操作

不建议直接操作表格源码，修改比较麻烦，可光标位于表格中，右键表格，基于弹出的选项点击来完成表格操作。

表格中的换行用`<br>`标签，也可在【偏好设置】的【Markdown】配置中设置不显示`<br/>`标签。

![image-20251206150010897](imgs/image-20251206150010897.png)



| Java教学安排                                  | Vue教学安排             | 收徒计划           |
| --------------------------------------------- | ----------------------- | ------------------ |
| Java基础<br />Java面向对象                    | es6语法回顾<br />ts基础 | 免费带1个月        |
| Java坦克1.0<br />Java坦克2.0<br />Java坦克3.0 | vue基础语法             | 自录加密视频教程   |
| Java Web                                      | vue组件化实战           | 远程解决问题、答疑 |



### html表格

`typora`的`markdown`形式的表格语法不支持单元格合并，如有类似特殊的需求，包括单元格样式定制，可自行维护`html`版本的表格源码。

<table>
    <tr>
    	<th rowspan="2">合并行</th>
        <th>列1</th>
        <th>列2</th>
    </tr>
    <tr>
    	<td style="color:red;background:lightyellow;">内容1</td>
        <td>内容2</td>
    </tr>
    <tr>
        <td colspan="3">合并列</td>
    </tr>
</table>


## 主题安装

找到[主题包位置](#主题目录)，将[软件目录](./softs)下的`typora-vue-theme-master.zip`

将压缩包中相关的文件和目录拖放到主题包下

<img src="imgs/image-20251206153017981.png" alt="image-20251206153017981" style="zoom:50%;" />

重启下`typora`后可以看到

<img src="imgs/image-20251206153114285.png" alt="image-20251206153114285" style="zoom:67%;" />

个人比较喜欢`vue`亮色主题

