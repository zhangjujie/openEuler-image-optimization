# Summer2021-No.63 openEuler基础镜像优化

#### 介绍
https://gitee.com/openeuler-competition/summer-2021/issues/I3EM49

#### 软件架构
软件架构说明

#### 安装教程

1. kiwi-ng system build --description openeulerdescription.x86_64/ --target ~/test

2. docker load -i test/openeuler.x86_64-1.0.0.docker.tar.xz

3. docker images

   ```shell
   [root@host]# docker images
   REPOSITORY                           TAG       IMAGE ID       CREATED        SIZE
   openeuler                            latest    7e078d8c1da8   25 hours ago   202MB
   hub.oepkgs.net/openeuler/openeuler   21.03     4367e32711f9   4 months ago   230MB
   ```

   

#### 使用说明

1.  docker run --name openeuler --priviledged -it openeuler bash
2.  执行docker run 命令的时候需要加入参数--priviledged以免yum安装软件的时候有错误

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
