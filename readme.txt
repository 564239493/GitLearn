Git is a version control system.
Git is free software.
--- 继续修改---
Git is a distributed version control system.
Git is free software.
--- 第三次修改 ---
Git is a distributed version control system.
Git is free software distributed under the GPL.
--- dev分支操作 ---
Creating a new branch is quick.
git checkout命令加上-b参数表示创建并切换，相当于以下两条命令：
	git branch dev
	git checkout dev
小结：
	Git鼓励大量使用分支：

	查看分支：git branch

	创建分支：git branch <name>

	切换分支：git checkout <name>

	创建+切换分支：git checkout -b <name>

	合并某分支到当前分支：git merge <name>

	删除分支：git branch -d <name>
--- 解决冲突 ---
Creating a new branch is quick AND simple.
1