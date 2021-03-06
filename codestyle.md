### 代码规范
#### 分号
- 不要在行尾加分号, 也不要用分号将两条命令放在同一行。
#### 行长度    
- 每行不超过80个字符，以下情况除外：
    - 长的导入模块语句
    - 注释里的URL
- 不要使用反斜杠连接行。如果一个文本字符串在一行放不下, 可以使用圆括号来实现隐式行连接	
- 在注释中，如果必要，将长的URL放在一行上。	
#### 括号
- 宁缺毋滥的使用括号
- 除非是用于实现行连接, 否则不要在返回语句或条件语句中使用括号. 不过在元组两边使用括号是可以的.
#### 缩进
- 用4个空格来缩进代码
- 绝对不要用tab, 也不要tab和空格混用. 
- 对于行连接的情况, 要么垂直对齐换行的元素，要么使用4空格的悬挂式缩进(这时第一行不应该有参数)
#### 空行	
- 顶级定义之间空两行, 方法定义之间空一行
- 顶级定义之间空两行, 比如函数或者类定义. 
- 方法定义, 类定义与第一个方法之间, 都应该空一行. 
- 函数或方法中, 某些地方要是合适, 就空一行.
#### 空格
- 按照标准的排版规范来使用标点两边的空格
- 括号内不要有空格.
- 按照标准的排版规范来使用标点两边的空格
- 不要在逗号, 分号, 冒号前面加空格, 但应该在它们后面加(除了在行尾)
- 参数列表, 索引或切片的左括号前不应加空格
- 在二元操作符两边都加上一个空格
- 当'='用于指示关键字参数或默认参数值时, 不要在其两侧使用空格
- 不要用空格来垂直对齐多行间的标记, 因为这会成为维护的负担(适用于:, #, =等)
#### 注释
- 模块：每个文件应该包含一个许可样板. 根据项目使用的许可(例如, Apache 2.0, BSD, LGPL, GPL), 选择合适的样板.
- 函数和方法：一个函数必须要有文档字符串, 除非它满足以下条件:
	- 外部不可见
	- 非常短小- 简单明了。
	- 文档字符串应该包含函数做什么, 以及输入和输出的详细描述. 
- 类：类应该在其定义下有一个用于描述该类的文档字符串. 如果你的类有公共属性(Attributes), 那么文档中应该有一个属性(Attributes)段. 并且应该遵守和函数参数相同的格式.
#### 命名
- 应该避免的名称：
	- 单字符名称, 除了计数器和迭代器
	- 包/模块名中的连字符(-)
	- 双下划线开头并结尾的名称(Python保留, 例如__init__)
- 命名约定：
    - 所谓"内部(Internal)"表示仅模块内可用, 或者, 在类内是保护或私有的.
    - 用单下划线(_)开头表示模块变量或函数是protected的(使用import * from时不会包含).
    - 用双下划线(__)开头的实例变量或方法表示类内私有.
    - 将相关的类和顶级函数放在同一个模块里. 不像Java, 没必要限制一个类一个模块.
    - 对类名使用大写字母开头的单词(如CapWords, 即Pascal风格), 但是模块名应该用小写加下划线的方式
- 常量
	- 常量使用以下划线分隔的大写命名
- 函数名
	- 函数名应该为小写，必要时可用下划线分隔单词以增加可读性。
    
    
   
    
    
