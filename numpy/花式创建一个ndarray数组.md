# ndarray数组的花式创建方法

函数 | 说明
--|--
np.array()|`朴实`的创建（没有花里胡哨哦）
np.arange()|按`步长`创建数组
np.linspace()| 按`元素数`创建数组
np.logspace()|按`等比数列`创建数组
np.random. ?()|按`random随机数`创建数组
np.zeros()|创建`填充 0 `的数组
np.ones()| 创建`填充 1 `的数组
np.empty()| 初始`内容随机`的数组
np.full() | 创建`指定值`的数组
np.eye()| 创建`对角矩阵`

## np.array  
np.array(10)
## np.arange
np.arange(10)  
np.arange(1,5,2)
## np.linspace
np.linspace(1,10,2)  
## np.logspace
np.logspace(0,2,10)  
## np.random.?
np.random.randint(10)  
np.random.rand(10)  
......
## np.zeros 
np.zeros((2,3))
## np.ones 
np.ones((2,3))
## np.empty 
np.empty((2,3))
## np.full 
np.full((2,3))
## np.eye [必须是矩阵]
np.eye((3,3))


