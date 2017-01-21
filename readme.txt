Tag 标签操作
//列出所有tag
git tag
//新建一个tag在当前commit
git tag 1
//新建一个tag在指定commit
git tag 2 8989920311bacb3f4e3ced7f82ab75ca47c318c7
//删除本地tag
git tag -d 1
//查看tag信息
git show 2
//提交所有tag
git push --tags
//删除远程tag
git push origin --delete tag 2
//新建一个分支，指向某个tag
git checkout -b [branch] [tag]
