# 音频文件目录

请将您想要作为背景音乐的音频文件放在此目录中。

## 支持的格式
- MP3 (推荐)
- AAC
- OGG
- WAV

## 使用方法
1. 将音频文件上传到此目录
2. 在 `_includes/footer.html` 中的 `playlist` 数组中添加对应的音频信息
3. 更新 `src` 路径为 `{{ base_path }}/assets/audio/您的文件名.mp3`

## 推荐设置
- 文件大小: 建议小于10MB
- 音质: 128-320kbps MP3
- 时长: 3-6分钟的轻音乐效果最佳

## 示例配置
```javascript
{
    title: "您的音乐标题",
    artist: "艺术家名称", 
    src: "{{ base_path }}/assets/audio/your-music.mp3"
}
```
