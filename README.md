# BuildGithub1s

一个自动构建GitHub1s的小Action。

## 使用方法

1. Fork该仓库
2. 登录账号并进入<https://github.com/settings/tokens>，创建一个包含`repo`的token；
![image](https://user-images.githubusercontent.com/58381667/110201852-2e34a000-7ea0-11eb-883f-cd96fe5cb297.png)
3. 记住该token，并填入你Fork的仓库中的secrets，名为`GH_TOKEN`；
![image](https://user-images.githubusercontent.com/58381667/110201939-b9159a80-7ea0-11eb-92be-d9ed310abada.png)
4. 在secrets中填入`TARGET_BRANCH`和`TARGET_REPO`，分别为目标分支和目标仓库（格式为`USER/REPO`）；
5. 在仓库上点一个star启动，构建产物将会被推送到`TARGET_REPO`的`TARGET_BRANCH`分支上。

