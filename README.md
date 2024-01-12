# MLSTAT2024
MLSTAT2024 website

## 克隆仓库

1. 执行git clone https://github.com/ML-Stat/MLSTAT2024.git

2. cd到MLSTAT2024文件夹，执行 git clone -b master https://github.com/ML-Stat/MLSTAT2024.git public

执行完上述的两条命令之后就成功克隆了mian和master分支

## 修改

在content里面修改具体的会议内容

在static/images/文件夹下存放图片

## 生成网页

在MLSTAT2024文件夹下执行

1. hugo --cleanDestinationDir

2. hugo -D

3. git add .

4. git commit -m "(填写这次修改的备注)"

5. git push

在public文件夹下执行

1. git add .

2. git commit -m "(填写这次修改的备注)"

3. git push

备注：hugo server可在本地先查看修改是否成功
