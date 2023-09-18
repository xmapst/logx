# logx
基于uber zap封装的日志类

go version >=1.18

## 使用
```go
package main

import (
    "github.com/xmapst/logx"
)

func main()  {
    // 直接使用, 内容将直接输出到控制台
    logx.Infoln("日志内容")


    // 设置写入文件
    logx.SetupLogger("logx.log")
    logx.Infof("日志内容")
}
```

