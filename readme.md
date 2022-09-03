## 测试git不常用语句

### git commit --amend

commit后如果又修改了文件，不想再次add . 和commit的话，可以直接使用此命令，新的修改也会commit， 
但是查看log是只有一开始commit的那条，新提交的备log不会再次生成，一般是工作中只能一天提交一次的话可以使用