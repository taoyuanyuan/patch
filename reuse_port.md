## 配置

    events {
        reuse_port on;
    }

## 指令

**reuse_port** `on` | `off`

**默认:** `reuse_port off`

**上下文:** `events` 

当打开reuse_port的时候，支持SO_REUSEPORT套接字参数，Linux从3.9开始支持该特性。   
使用该特性，cpu更加均衡，新建连接的能力增强，但是负作用是reload和upgrade会有少量的失效。
     
