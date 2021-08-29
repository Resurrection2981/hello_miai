# Send TTS to MiSpeaker from Home Assistant

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

## 说明

> 原项目：<https://github.com/harepo/hello_miai>
> 
> 原项目不支持最新的 HACS 安装，做了一些小修改。
> 


## 介绍

配置例子,填写绑定小爱音箱的用户账号信息：

```yaml
hello_miai:
  miid: '13123456789'
  password: 'password'
```

调用服务，如果你有多个音箱，miai_num代表你的音箱id。

```yaml
wait_time: 0
miai_num: 0
message: 你好天睿tera，我不是小爱。
```
