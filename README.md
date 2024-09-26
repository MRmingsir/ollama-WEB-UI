# Ollama 聊天界面

这是一个基于Streamlit的Ollama聊天界面，使用嵌入式Python 3.12.6。

## 依赖

本项目依赖以下 Python 库:

- streamlit
- requests

## 安装和运行

1. 确保项目目录中包含 `py3.12.6` 文件夹（嵌入式Python环境）。

2. 首次使用时，双击运行 `检查依赖.bat` 检查所需依赖。

3. 如果发现缺失依赖，双击运行 `安装依赖.bat` 一键安装所需依赖。

4. 之后每次使用，只需双击 `启动程序.bat` 即可启动Ollama聊天界面。

注意: 请确保Ollama服务已在本地运行，并监听在 http://localhost:11434，11434是默认端口，如果被占用请自行修改。

ollama 下载地址：https://ollama.com/

ollama 端口修改需要在环境变量中进行修改，在用户变量中添加 OLLAMA_HOST=0.0.0.0:11434，保存后重启终端。   


## 文件说明

- `ollama_webui.py`: 主应用程序文件
- `安装依赖.bat`: 用于安装所需依赖的批处理文件
- `启动程序.bat`: 用于启动应用程序的批处理文件
- `requirements.txt`: 项目依赖列表
- `README.md`: 项目说明文件
- `py3.12.6/`: 嵌入式Python目录

## 注意事项

如果遇到任何问题，请查看命令行窗口中的错误信息。

## 作者

@文抑青年 | [B站主页](https://space.bilibili.com/259012968)
