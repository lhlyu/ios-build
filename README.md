# ios-build
IOS项目构建

## 变量

```
REPO_NAME: 库名字, 例如: ios
REPO_URL: 库地址，例子: https://<username>:<仓库访问令牌>@git.xxx.com/xx/ios.git
REPO_BRANCH: 指定库分支，例子: develop
WORKSPACE_NAME: ios项目工作空间，例子: qq
APP_NAME: app名字，例如: 企鹅
DEVELOPMENT_TEAM: 开发团队ID，例子: SDF33I32
OSSUTIL_CONFIG: 阿里云OSS配置，用来上传到OSS
OSS_URL: 上传到OSS的位置，例子: oss://resource-xxx-com/
```

## 步骤

1. 从指定库地址克隆项目
2. 安装工具
3. 构建
4. 将ipa上传到云对象存储
5. 通知到群
