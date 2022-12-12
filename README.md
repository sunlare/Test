git reset --hard HEAD^  版本回退（回退一次提交）
 git reset --hard Obfafd  回退到指定Obfafd的commit id版本
 git reset HEAD  用版本库中的文件去替换暂存区的全部文件。
 git checkout -- x.txt   用暂存区指定文件去替换工作区的指定文件（危险）
 git checkout HEAD x.txt 用版本库中的文件替换暂存区和工作区的文件（危险）
 git rm --cached x.txt  从暂存区删除文件
