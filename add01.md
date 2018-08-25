**HTML DEMO**

<!--
 html 注释
-->

<p align='center'> Hello world! </p>
<p><center> Hello world! </center></p>

<p align='center'>
<img src='https://www.baidu.com/img/bd_logo1.png' />
</p>




**GFM DEMO**
_(Github Flvored Markdown)_
* 表格

	- 水浒人物表
	
	|姓名 | sex | star|
	|--- | :---: | ---------:|
	| xxxxx宋江xxxx| xxxxxxxxx男xxxxxxxxx | xxxx天魁星xxxx|
	|卢俊义 | 男 | 玉麒麟|
	| [baidu][baidu_web]|![][baidu_log]| |
	
[baidu_web]: https://www.baidu.com '百度'
[baidu_log]: https://www.baidu.com/img/bd_logo1.png "百度"

* task list
- [ ] item1
- [x] item2
- [ ] item3  

* Github emoji 表情
<https://github.com/guodongxiaren/README>
	- _Example_  
	:thumbsup: 


**混合强调样式**
- 基本强调样式
	1. **加粗**
	2. _倾斜_
	3. ~~删除~~  
	*- 以下Github不支持扩展语法 -*
	4. ==高亮==
	5. ++下划线++  
	
- 混合强调样式
	1. **_加粗倾斜_**
	2. ~~**加组删除**~~
	3. ~~_倾斜删除_~~
	
**链接**
- 基本语法  
	`\[链接文字](URL)`   
	`![链接文字](URL)`

- 图片文字链接
	[![](https://www.baidu.com/img/bd_logo1.png)](https://www.baidu.com)



**引用链接**  
- 基本用法  
_自引用:_  [baidu]  
[百度][baidu_web]


- 混合用法	
	[![][baidu_log]][baidu_web]
	
	
[baidu]: https://www.baidu.com '百度'
[baidu_web]: https://www.baidu.com '百度'
[baidu_log]: https://www.baidu.com/img/bd_logo1.png "百度"

**多级列表**  
`两个问题：`
- 1. 如何打断： 空行不行， 需要文字段落
1. item 1
	- item 1.1
	- item 1.2
2. item 2  
	1. item 2.1  
	2. item 2.2  
3.  item 3  
xxxxxxxxxxxxxxxxxxxxxxxxxxxx



xxxx

1. item 4
2. item 5

- 2. 打断的列表， 如何续上

1. item 1
	- item 1.1
	- item 1.2
2. item 2  
	1. item 2.1  
	2. item 2.2  
    xxxxxxx
    
1.  item 3
4. item 4
5. item 5
