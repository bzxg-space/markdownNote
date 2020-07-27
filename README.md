# markdown基本语法

## 前言

> 1. **说明**：使用markdown语法，编写内容为 `markdown基本语法`  md文件  
> 2. **时间**：`2020/4/10-2020/4/11`
> 3. **编写人**：`@bzxg`
> 4. **编写工具**：[MarkdownX](https://www.coolapk.com/apk/com.ryeeeeee.markdownx)

## 1、强调文本

1. **加粗** ： `**加粗**` 或 `__加粗__`
2. *倾斜*： `*倾斜*` 或 `_倾斜_`
3. ~~删除~~： `~~删除~~`  
4. ***加粗且倾斜*** ： `***加粗且倾斜***`

## 2、表格

> 使用 | 来分隔单元格，使用 - 来分隔标题行和其他行  
依次是左对齐 、 右对齐 、居中对齐

| 左对齐 | 右对齐 | 居中对齐 |
| :--- | ---: | :---: |
| 1 | 2 | 3 |
| 4 | 5 | 6 |

```
| 左对齐 | 右对齐 | 居中对齐 |
| :--- | ---: | :---: |
| 1 | 2 | 3 |
| 4 | 5 | 6 |
```

## 3、水平线
-  `___` 
___
-  `***`
***
- `---`

---

## 4、标题

1. # 一级标题

	- `# 一级标题`

2. ## 二级标题

	-  `## 二级标题`
3. ### 三级标题
    -  `### 三级标题`
4. #### 四级标题
	-  `#### 四级标题`
5. ##### 五级标题
	-  `##### 五级标题`
6. ###### 六级标题
	-  `###### 六级标题`

## 5、超链接

1. 小书签:<https://bzxg-space.github.io/bookmarklet/>  
	- `小书签:<https://bzxg-space.github.io/bookmarklet/>`   
2. https://bzxg-space.github.io/bookmarklet/  
	- `https://bzxg-space.github.io/bookmarklet/`  
3. [小书签](https://bzxg-space.github.io/bookmarklet/)
	- `[小书签](https://bzxg-space.github.io/bookmarklet/)`  
4. [小书签](https://bzxg-space.github.io/bookmarklet/ "访问小书签")  
	- `[小书签](https://bzxg-space.github.io/bookmarklet/ "访问小书签")`  

## 6、图片

 ```
格式：![替代文字](图片地址 "标题文字")

![可爱](https://ae01.alicdn.com/kf/Ud2a16fd840ed4155a93a2f32c82dc053f.jpg "不拖延，保持可爱")
 ```

![可爱](https://ae01.alicdn.com/kf/Ud2a16fd840ed4155a93a2f32c82dc053f.jpg "不拖延，保持可爱")

## 7、引用

> 这是引用的内容

 `> 这是引用的内容` 

## 8、代码高亮

1. 行内代码：`行内代码`
2. 代码块
>  \`\`\`  
>  代码块  
>  ……  
>  \`\`\`

  - ```
     <div>  
        我是一个div  
    </div>
    ```


3. 语言代码块高亮

>  \`\`\`语言名  
>  语言代码块  
>  \`\`\`

  - ```html
     <div>  
        我是一个div  
     </div>
     ```

## 9、无序列表

### 1.语法

> \*或+或- 子项  
​\*或+或- 子项  
​\*或+或- 子项  

### 2.示例

#### 2.1 水果

- 香蕉
- 苹果
- 橘子

#### 2.2 终端

* 手机
* 平板
* 手表
* 电视

#### 2.3 配置

+ 标配
+ 中配
+ 高配
+ 顶配

## 10、有序列表

### 1.语法

> 1. 第一行
> 2. 第二行
> 3. 第三行

### 2.示例

#### 2.1 水果

1. 香蕉
2. 苹果
3. 橘子

## 11、其他

1. 转义
	
> 使用  `\` 

2. 换行
> 插入处先敲 `两个及以上` 的 `空格` 然后 `回车`  
或 `<br/>​​`

3. 推荐格式
> 标题、列表项、代码块、引用等前后各空一行

4. 一些特殊符号
> 数字上标：​​X&sup2;  根号：&radic; 3  
商标：爱分享&reg;   角度：30&deg;

5. 更多特殊符号：[@csdn](https://blog.csdn.net/html5_/article/details/21639475 "点击查看")
6. html特殊字符编码对照表：[@脚本之家](https://www.jb51.net/onlineread/htmlchar.htm)
7. 插入有趣Emoji表情：[@csdn](https://blog.csdn.net/qq_44830040/article/details/106816917?%3E)
8. 超多Emoji表情：[@emoji-cheat-sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)

