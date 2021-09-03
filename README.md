# git-branch-test

git 分支测试，测试内容如下：

假如有一个公共分支 release2021 ，在 release2021 分支新开 feature-a 和 feature-b 分别对应用户a和用户b用于代码开发，当 feature-a 和 feature-b 同时修改 README.md 文件，feature-a 开发完功能，先合并到 release2021 ，这个时候 feature-b 合并到 release2021 肯定有冲突，在 release2021 新开 feature-b-conflict ，将 feature-b 合并到 feature-b-conflict 解决冲突，再将 feature-b-conflict 合并到 release2021 这个时候是没有冲突的，那 feature-b 合并到 release2021 还会有冲突吗？feature-b 修改其他地方代码合并到 release2021 还会有冲突吗？

## test

1. main 分支添加
2. feature-b 分支添加feature-b 分支添加feature-b 分支添加
