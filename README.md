# hello-c
Hello C Exercise

## 如何运行
### CLion
- [ ] 将作业 `git clone` 下来
- [ ] 打开 `CLion`
- [ ] 使用 `File => Open...` 选择你下载的项目
### VSCode
- [ ] 将作业 `git clone` 下来
- [ ] 打开 `VSCode`
- [ ] 使用 `打开文件夹` 选择你下载的项目
- [ ] 使用 `code runner插件` 或  `命令行终端中输入gcc hello.c -o hello` 来编译测试运行你的代码(vsc用户可以无视cmakelist)
## 你的任务 
- [ ] 在 `hello.c` 文件开头的注释里, 填上你的姓名 (Author: ), 学号 (ID: ) 与做作业时的日期 (Date: )。
- [ ] 修改 `main` 函数, 让其输出 `To C or not to C, this is the question!\n`。
  - 注意: 由于是程序自动检查你的输出, 所以请严格输出指定的信息。

## 关于 GitHub Classroom
- 你在本地可以对程序做任何修改, 但不要**删除**老师/助教提供的文件, 也不要对这些文件进行重命名。
- 你在本地可以使用通常的方法编译、运行、测试你的程序, 这与 GitHub Classroom 的自动检查无关。
  只有当你通过 `git push` 提交代码时, GitHub Classroom 才起作用。

## 一点解释
- [`.gitignore`](https://www.atlassian.com/git/tutorials/saving-changes/gitignore) 是与 `git` 相关的功能, 与本次作业无关。 
  但是任何一个严肃的 Git 项目都应该[选用合适的 `.gitignore` 文件](https://github.com/github/gitignore)。
  我们选用了 [`CMake.gitignore`](https://github.com/github/gitignore/blob/master/CMake.gitignore) 与 [`JetBrains.gitignore`](https://github.com/github/gitignore/blob/master/Global/JetBrains.gitignore)。
- `LICENSE` 是许可证信息, 与本次作业无关。同样地, 一个严肃的项目需要[指定合适的许可证](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)。
  我们选用了 `MIT License`。
- 目录下的`test_data.bz2`文件请无视，该文件已经被加密用于OJ测试，你无法打开这个文件是正常情况。
