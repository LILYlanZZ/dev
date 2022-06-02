git commit --no-verify -m "提交"     忽略eslint提交
git commit --no-verify -m "合并代码"

git add  
git commit
也可以使用 git commit -a 命令 , 省去 git add 步骤 
 git commit -a -m "修改"

git push

 git commit --no-verify -a -m '打包'

提示也比较明确 在git commit -m "" 时，要使用 fix: xxxxx
但是这里有一个坑，fix之后必须是英文的冒号，并且需要敲一个空格。
并且不能以大写字母作为描述的开头。