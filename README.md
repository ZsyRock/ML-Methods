# ML-Methods

## how to upload the changes via git

### 查看当前状态
git status

### 添加新修改的文件
git add .

### 提交改动
git commit -m "描述你的更改，比如：更新线性回归代码"

### 推送到 GitHub
git push

### 追踪Git根目录
git rev-parse --show-toplevel

### 查看Git记录了哪些提交
git log --oneline --graph


## how to generate branch

### generate branch via Git
git switch -b feature-login

### push the changes to this branch
git push -u origin feature-login

### add Tags to mark the important timenode
git tag -a v1.0 -m "发布第一个版本"
git push origin v1.0

### switch the menu back to main
git switch main
