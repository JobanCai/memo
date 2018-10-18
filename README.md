# redis

    https://segmentfault.com/a/1190000002680804
    sentinel 模式 failover 进行选举时选举规则 ：
    slave的选举主要会评估slave的以下几个方面：

> 与master断开连接的次数
> Slave的优先级
> 数据复制的下标(用来评估slave当前拥有多少master的数据)
> 进程ID
