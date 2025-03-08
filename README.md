# dow文档转视频项目说明

## 项目简介
本项目是一个多功能的媒体处理工具，支持dow文档转视频。语音生成本地部署，下载Kokoro-TTS-Windows-Gradio-CPU-x64-v1.0，打开run_gradio.bat，在打开python main.py，就能本地运行。
Kokoro-TTS-Windows-Gradio-CPU-x64-v1.0下载地址：https://github.com/mirbehnam/Kokoro-TTS-windows/releases/tag/v3
感谢：米尔贝南
Kokoro-TTS-窗户

## 环境要求
- Python 3.12 或更高版本
- Windows 操作系统

## 依赖项
项目运行需要以下Python包：
```
moviepy        # 视频处理
pydub          # 音频处理
mutagen        # 音频元数据处理
opencv-python  # 图像处理
python-docx    # Word文档处理
gradio-client  # Gradio客户端
PyQt5          # GUI界面
chinese_converter  # 中文转换
```

## 安装步骤

1. 克隆或下载项目到本地

2. 安装依赖包
   ```bash
   pip install -r requirements.txt
   ```


## 使用方法

1. 启动程序
   ```bash
   python main.py
   ```

2. 主要功能
   - 视频处理：支持视频剪辑、合并等操作
   - 音频处理：支持音频格式转换、编辑等功能
   - 文档处理：支持Word文档操作
   - 中文转换：支持中文简繁转换

## 目录结构
```
dow文档转移视频/
  ├── main.py            # 主程序入口
  └── requirements.txt           # 依赖说明
```

## 注意事项
1. 首次运行前请确保已正确安装所有依赖包
2. 使用前请检查配置文件的设置是否正确
3. 建议定期备份重要数据

## 常见问题
1. 如遇到依赖安装失败，请确保使用的是最新版本的pip
2. 如程序无法启动，请检查Python版本是否符合要求
3. 如遇到功能异常，请检查配置文件是否正确
