#第一个mankdown
### 换行
* 一个空格 
不会换行  

* 两个空格  
才会换行  

注释格式  

```
* This two-line bullet 
won't break

* This two-line bullet  
will break
```
###加粗、斜体和下划线
**粗体**语法：`**使用两个星号**` 或者 `__使用两个下划线__`  
__字体加粗__  
*斜体*语法：`*使用一个星号*` 或者 `_使用一个下滑下_`  
_字体倾斜_  

###标题信息
	Header 1
	=======
	
	Header 2
	-------
	
or  

	#Header1
	##Header2
	###Header3
	####Header4

###超链接和邮件地址
#### 在线的
把邮件地址放到<>之间，就会变成可点击的邮件地址   
<xunyan@wecash.net>  
`<your@email.com>`  

地址链接也是同样方法：<http://www.baidu.com>  
`<http://www.xxx.com>`  

如果你想展示一个特别长的url，但是不想看上去很乱，或者你想把所有的url放到一起  
使用中括号的格式，2个，前面是展示出来的，后一个是实际链接的地址url：[这是一个可点击的链接][链接的地址]`[a link][arbitraty_id]`,把链接的地址单独写在下面 
[链接的地址]:http://www.baidu.com  
`[arbitraty_id]:http:www.//xxx.com`  
  
或者直接写成[link this][]`[link this][]`这种格式，把地址写在link this里面  
[link this]:http://www.baidu.com
`[link this]:http://www.baidu.com`  

###图片
`![Alt Image Text](path/or/url/to.jpg "optional Title")`  
本地图片打开方式 
![猫咪图片](/Users/xunyan/Desktop/1.jpeg)  

网络图片打开方式  
![网络图片](http://b.hiphotos.baidu.com/zhidao/wh%3D450%2C600/sign=4b0a4e1f7b8da9774e7a8e2f8561d42f/c83d70cf3bc79f3df946691cb2a1cd11728b2972.jpg)  

### 列清单lists
* lists 必须以一个星号和一个空格开头
- `-`也可以
	* tab缩进显示下一级别列表
		1. 数字也支持
		2. 格式就是 （数字+.+空格）例如 `1. `
		42. 你写的数字是多少没有关系，markdown会自动排序
		1. 所以你可以每行都写 `1. `,我会自动进行排序

### 区块
> 用`>`来代表区块  
只要没用行和行之间没有空行，其实不需要每一行都用`>`来开头，也能代表一整个区块  
> 就是看起来有点丑
> 区块也可以分级别
> > 下一层级
> > > 再下一层级  

> 好多markdown的语法都可以在区块区间使用  
> * lists  
> * [link this][]  
> * 等等其他

--  
###快捷键
**加粗**  command+B   
<!--注释--> command+/   
*斜体*  command+I   
`inline code` command+K  
1. 序号  shift+command+o  
* 无序的list shift+command+U  
> 区块 shift+command+B  
[插入链接]() shift+command+K  
![插入图片]() shift+command+I
