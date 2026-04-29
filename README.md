[README.md](https://github.com/user-attachments/files/27212361/README.md)
# Patch Agent CLI

一个轻量级的自动化漏洞修复脚本，基于 Python 标准库开发，无外部依赖。

## 运行方式

系统默认在 `dry-run` (安全测试) 模式下运行，只会打印将要执行的命令，不会真实修改系统。

```bash
# 默认运行 (Dry-run)
python main.py

# 指定目标主机
python main.py -t 192.168.1.100

# 开启执行模式 (危险，请确保在测试环境)
python main.py --execute
```
