# Hello_world
Just another repository

Hi,everybody! Nice to meet you on GitHub.
I`m a student to study ocean acoustics in Beijing.


# the Note of 《GitHub Guide》
1. By default your repository has one branch named master which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master. master为初始默认分支，也被视为主分支。在分支上做测试修改，完成后再交付给主分支。

2. When you create a branch off the master branch, you’re making a copy, or snapshot, of master as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates. 其他分支建立时都相当于彼时主分支的拷贝或者快照。如果主分支发生变化，非主分支均可下拉获取更新。

3. A new branch called feature (because we’re doing ‘feature work’ on this branch). The journey that feature takes before it’s merged into master.
![GitHub branch diagram](https://guides.github.com/activities/hello-world/branching.png)

4. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why. 保存修改内容被称为**确认**。Commit changes(确认修改) 中填写的是描述修改内容及其原因的交付信息。

5. Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. 拉起请求是GitHub协作的核心。当开启拉起请求动作时，就意味着向对方推荐自己修改，请求对方查看并提取出修改意见以整合进他们的分支中。
The changes, additions, and subtractions are shown in green and red. 拉起请求会显示出自己分支和对方分支的差异 —— 增添部分和删减部分会用绿色和红色标识出来。
As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished. 确认修改内容后就能够开启一个拉起请求动作并开始一次讨论。
By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams. 在拉起请求动作相应的信息中，可以使用@功能来提醒特定的人或团队给自己反馈。

6. 非主分支向主分支master发出上行的拉起请求后，主分支确认合并后会显示**删除**该非主分支；而当非主分支向主分支发起的拉起请求是下行时，即主分支是内容提供方，非主分支本身等待被更新，此时主分支确认后是非主分支被主分支的内容合并，主分支不发生任何变化，非主分支会显示**恢复**。

