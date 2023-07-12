# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

# 参考 

- [pypi安装](https://packaging.python.org/en/latest/tutorials/packaging-projects/#installing-your-newly-uploaded-package)


-使用方法

- 安装pip

--  pip install example_package_shengtong


'''
~/.local/lib/python3.10/site-packages
'''
包的安装路径是；
~/.local/lib/python3.10/site-packages
'''
#from example_package_shengtong 
import example  # 导入安装的包，定义时候一个一个py文件
a = example.add_one(1) # 调用包中的函数
print (a)
'''

# push

git add .
git commmit -m 'info note '
git push -u origin main

# pull

git pull

# config

git config user.email  ""
git config user.name ""
