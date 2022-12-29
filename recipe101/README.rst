Template for the Read the Docs tutorial
=======================================

This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/


步骤
===

1.github建仓库
2.导入readthedocs
3.clone到本地
4.push测试

git clone git@github.com:cong-han/recipe101.git
touch .gitignore
echo 'build/' > .gitignore

sphinx-quickstart
git add .
git commit -m "first"
git push -u origin main 
    https://blog.csdn.net/u014361280/article/details/109703556