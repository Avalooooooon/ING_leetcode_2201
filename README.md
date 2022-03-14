# Introduction

## 多终端发布

不论是在哪台终端，修改了书籍文件后按下列步骤进行操作：
1. ```git pull origin main```，先pull完成本地与远端的融合
2. 修改书籍内容
3. ```git add -A``` ，添加本地所有文件到仓库
4. ```git commit -m``` 修改说明，提交修改；
5. ```git push origin main```，更新至main分支；
6. ```bash deploy.sh # macos```运行deploy.sh文件，生成项目并上传到github仓库的gh-pages分支；
7. ```gitbook serve```，启动gitbook服务。启动服务后，项目文件夹中会生成一个_book文件夹，此文件夹就是最终生成的项目。

## 顺序
704.二分查找
