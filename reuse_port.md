## 配置

    events {
        reuse_port on;
    }

## 指令

**reuse_port** `on` | `off`

**默认:** `reuse_port off`

**上下文:** `events` 

开启或者关闭对SO_REUSEPORT套接字参数的支持.
     
