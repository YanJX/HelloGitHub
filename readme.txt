git inint   			// 在当前目录下创建一个空的Git仓库

git branch 			// 命令会列出所有分支，当前分支前会有个*号标记

git branch <name>    		// 创建分支  ex：git checkout -b develop

git checkout -b devlop 		// 该命令效果等同于以上两个命令 git checkout命令加上-b参数表示创建并切换

// 用git log --graph命令可以看到分支合并图。

git checkout <name>             // 切换分支  ex：git checkout develop

git checkout -b <name> 		// 该命令效果等同于以上两个命令 git checkout命令加上-b参数表示创建并切换 ex：git checkout -b develop

git merge <name>		// 合并某个分支到当前分支 ex：git merge develop

git branch -d <name>		// 删除分支 ex：git branch -d develop

