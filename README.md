简体中文 | [English](./README_EN.md)

<p>
<strong><h2>曾坤の主页</h2></strong>

</p>

![曾坤の主页](https://s1.328888.xyz/2022/06/05/WM3CS.png)

>主页的 Logo 字体已经过压缩，若用本站 Logo 以外的字母会变回默认字体，这里是 [完整字体](https://file.imsyy.top/font/Pacifico-Regular.ttf)

>天气 API 每日限量100次，需 [自行申请](https://www.tianqiapi.com/)，或更换其他 API

### Demo
>由于 CDN 缓存原因，查看最新效果可能需要 `Ctrl` + `F5` 强制刷新浏览器缓存

- [曾坤の主页](https://static-bd004b6a-412d-4795-aefc-e181a6efa562.bspapp.com/)

### 功能

- [x] 载入动画
- [x] 站点简介
- [x] Hitokoto 一言
- [x] 日期及时间
- [x] 实时天气
- [x] 时光进度条
- [x] 音乐播放器
- [x] 移动端适配
* [ ] 还没想好呢

### 音乐

>本项目采用了基于 `MetingJS` 的 `Aplayer` 音乐播放器，可实现快速自定义歌单  
>*仅支持 **中国大陆地区**，其他区域请将 [以下内容](https://file.imsyy.top/js/music/music-other.js) 替换 `music.js` 以实现音乐播放器的正常使用

更改 `music.js` 的参数即可实现自定义歌单列表

```js
var server = "netease"; //netease: 网易云音乐; tencent: QQ音乐; kugou: 酷狗音乐; xiami: 虾米; kuwo: 酷我
var type = "playlist"; //song: 单曲; playlist: 歌单; album: 唱片
var id = "7452421335"; //封面 ID / 单曲 ID / 歌单 ID
```

### 插件

* [Bootstrap](https://getbootstrap.com/)
* [iziToast](https://izitoast.marcelodolza.com/)
* [Font Awesome](https://fontawesome.com/)
* [jQuery](https://jquery.com/)
* [Aplayer](https://aplayer.js.org/)

### API

* [MetingAPI By 武恩赐](https://api.wuenci.com/meting/api/)
* [小歪 API](https://api.ixiaowai.cn/)
* [天气 API](https://www.tianqiapi.com/)
* [Hitokoto 一言](https://hitokoto.cn/)

