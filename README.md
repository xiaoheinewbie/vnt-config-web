# 🌸 vnt-config-web

用于 **可视化配置 VNT 的 `config.yaml` 文件** ✨  
 [VNT](https://github.com/vnt-dev/vnt) 是一个简单、高效、能快速组建虚拟局域网的工具

---

## 💡 功能介绍
- 🌼 可视化填写配置参数  
- 🐱 一键生成 `config.yaml` 文件  
- 🍓 支持导出与本地保存  
- 🌈 简化命令行使用体验

---

## 🪄 使用方式

1. 打开网页 
   👉 [https://xiaoheinewbie.github.io/vnt-config-web](https://xiaoheinewbie.github.io/vnt-config-web)

2. 填写相关参数  
   根据网页提示输入以下内容：
   - 🔑 组网 Token  
   - 💻 设备 ID  
   - 🌐 服务器地址  
   - ☁️ STUN 服务器 等信息  

3. 点击「生成配置」按钮 ✨  
   会自动生成一个 `config.yaml` 内容，下载或者复制。

4. 将文件放入 VNT客户端 程序目录  
   把 `config.yaml` 保存到与你的 `vnt-cli` 程序同一目录下。

5. 运行 VNT！🚀  
   ```bash
   vnt-cli -f config.yaml
