## 0.10.1（2025-1-21)
1.  修复 $lib 没有放在 properties 里

## 0.10.0（2023-2-10)
1.  新增
    - 支持 `ID-Mapping 3.0` 用户关联协议 

## 0.9.1（2021-09-16)
1.  优化
    - 修改初始化配置参数 `show_log` 默认值为 `fasle`
    - 修改初始化配置参数 `max_string_length` 默认值为 `500`
    - 优化批量发送 `300` 条限制逻辑
2.  新增
    - 新增 `getServerUrl` 接口

## 0.9.0（2021-07-28)
1. 新增
    -  新增事件监听功能；
    -  新增 `A/B Testing` 插件集成功能；

## 0.8.0（2021-04-16)
1. 新增
    - 新增批量发送功能；

## 0.7.0（2021-03-13)
1. 新增
    - 增加 `_flush_time` 和 `_track_id` 属性；	

## 0.6.0（2020-09-16)
1. 新增
    - 新增获取匿名 ID 接口；

## 0.5.0（2020-07-02)
1. 新增
    - 新增所有事件都有的预置属性 `$app_id` 和 `$timezone_offset`；

## 0.4.0（2020-02-17)
1. 新增
    - 新增 `logout()` 接口；

## 0.3.0
1. 优化
    - 优化异步获取数据导致的首日首次问题；

## 0.2.0
1. 修复
    - 修复异步获取数据，导致设置是否首次访问不准的问题；

## 0.1.1
1. 优化
    - 修改预置事件为 `App` 的相关预置事件名字；

## 0.1.0
1. 第一个版本；

