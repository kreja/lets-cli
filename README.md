# cli

命令行工具

## todo
- .gitignore 文件拷贝


# push

相当于

```
git add .
git commit -m 'xx'
git push origin [branch]
```

Usage: push -m [options]

选项：
  -m, --msg   提交信息                 [字符串] [默认值: "update"]
  -h, --help  显示帮助信息                                  [布尔]

示例：
  push -m "update"