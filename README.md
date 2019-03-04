# FastMonitor
# 快速的把你的系统监控起来

## 这个监控要解决的问题

### 1. 市面上有很多监控,但是配置起来及其不方便
### 2. 我需要一个秒级的实时监控系统
### 3. 方便程序打点
### 4. 可能我就需要监控一个点,不想配置那么大的其他玩意



## 依赖
### 1.nodejs
### 2.socket.io
### 3.redis

## 性能瓶颈

### 1.目前严重依赖redis的队列写性能,大概qps在20000qps左右
### 2.如果你的业务超过这个,请不要选择我