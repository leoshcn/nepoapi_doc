
# 主要步骤
1. 设计你的表格
2. 找到 可以反回 json 文本结果的 api 并用 [getman](https://getman.cn/) 进行测试 
3. 建立按钮 用循环语句获取目标单元格的值 [ YouTube 上的参考教学 ](https://youtu.be/iSlBE3CWg5Q)
4. 建立 Winhttp 查询，用 Get 方法通过 api 得到 json 格式的返回结果。把数组型结果解析后定义为`Dictionary` 。解析过程需要用到一个开源的函数 JsonConverter 来自 [github](https://github.com/VBA-tools/) 这个过程也有 [视频教程](https://youtu.be/KZeYKZJzQIk )


> [!NOTE]
> 开启 vba 的 `winhttp` 以及 `socks？` reference 模块支持
> 更新表格结构之后可能需要考虑相应修改参数和常数的值


# 几个有用的 免费 API 
* yfapi.net
* china stock price
* exchange rate

# 代码下载
* 代码案例在我的 github 仓库可以找到 [链接](https://github.com/leoshcn/vba-json-update)