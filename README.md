# go-table-checksum
go实现的MySQL数据比对工具,主要是想解决pt工具对主备关系的依赖，以及对我们的binlog消息订阅工具的校验，数据按照chunk取出后生成MD5值进行校验，并发采用goroutine和chan实现,还在改进中...
