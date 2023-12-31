## Github学习笔记

https://www.bilibili.com/video/BV1HM411377j?p=8&vd_source=55cda1d3c417173da89292890bfc3059

![](./figure/image-20231227165058475.png)

![](./figure/image-20231227202143234.png)

```sh
git config --global user.name 'JamesPan1999'
git config --global user.name 'jiongliangpan@163.com'
该设置在github主页上显示了是谁修改了该仓库
```

```
git init
git status
git add   （可以上传整个文件夹下的所有内容）

```

![](./figure/gir_rm.png)

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



https://www.bilibili.com/video/BV1HM411377j?p=11&vd_source=55cda1d3c417173da89292890bfc3059

ssh密钥配置方法



```shell
echo "# myfirst_repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main    //设置主分支为main分支
git remote add origin git@github.com:JamesPan1999/myfirst_repo.git  //给远程的这个ssh地址设置别名为origin（也可以自定义）
git push -u origin main:main    //将本地的main分支合并到远程main分支中，远程推送地址为origin  -u代表了upstream
```

