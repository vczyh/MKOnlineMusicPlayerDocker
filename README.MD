# MKOnlineMusicPlayer Docker

[ MKOnlineMusicPlayer](https://github.com/mengkunsoft/MKOnlineMusicPlayer) 是一款开源的基于 `Meting` 的在线音乐播放器。**具有音乐搜索、播放、下载、歌词同步显示、个人网易云音乐播放列表同步等功能。**

`MKOnlineMusicPlayer Docker`是`MKOnlineMusicPlayer`的`Docker`版本，集成了运行环境，部署方便。

## 使用

```bash
docker run -d \
    -p 4000:80 \
    --env TITLE=MusicPlayer \
    registry.cn-hangzhou.aliyuncs.com/vczyh/mk-online-music-player
```

| 参数                    | 说明                                 |
| ----------------------- | ------------------------------------ |
| -d                      | 后台运行                             |
| -p 4000:80              | 容器的 80 端口映射到主机的 4000 端口 |
| --env TITLE=MusicPlayer | 设置播放器名称，这里为 MusicPlayer   |

## 感谢

- [ MKOnlineMusicPlayer](https://github.com/mengkunsoft/MKOnlineMusicPlayer)