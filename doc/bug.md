### 以下是已知的 Bug及当前解决思路：

- 中文名 pcap 文件读取失败：解决-先copy再读取，使用 json 代替 pcap
- 有的字段更改之后不会生效，请注意，如头部长度：解决-实现更加标准的构造编辑界面
- 有些字段显示负数：解决-采取更长的数据类型