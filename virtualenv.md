# virtualenv虚拟环境

1. 安装

```shell
# 正常环境下
pip install virtualenv
# 多版本环境下
python[version] -m pip install virtualenv
```

2. 创建虚拟环境

```shell
# 创建并进入项目目录
mkdir demo
cd demo

# 创建虚拟焊接并命名
virtualenv demo-venv
```

3. 激活虚拟环境

```shell
.\demo-env\Scripts\activate
```

4. 退出虚拟环境

```shell
deactivate
```

5. 删除虚拟环境

删除虚拟环境所在的文件夹即可

-- --
参考：[要不我们还是用回 virtualenv/venv 和 pip 吧 - 李辉](https://zhuanlan.zhihu.com/p/81568689)
