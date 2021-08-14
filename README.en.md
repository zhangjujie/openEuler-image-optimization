# Summer2021-No.63 openEuler基础镜像优化

#### Description
https://gitee.com/openeuler-competition/summer-2021/issues/I3EM49

#### Software Architecture
Software architecture description

#### Installation

1. kiwi-ng system build --description openeulerdescription.x86_64/ --target ~/test

2. docker load -i test/openeuler.x86_64-1.0.0.docker.tar.xz

3. docker images

   ```shell
   [root@host]# docker images
   REPOSITORY                           TAG       IMAGE ID       CREATED        SIZE
   openeuler                            latest    7e078d8c1da8   25 hours ago   202MB
   hub.oepkgs.net/openeuler/openeuler   21.03     4367e32711f9   4 months ago   230MB
   ```

   

#### Instructions

1.  docker run --name openeuler --priviledged -it openeuler bash

#### Contribution

1.  Fork the repository
2.  Create Feat_xxx branch
3.  Commit your code
4.  Create Pull Request


#### Gitee Feature

1.  You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2.  Gitee blog [blog.gitee.com](https://blog.gitee.com)
3.  Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4.  The most valuable open source project [GVP](https://gitee.com/gvp)
5.  The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6.  The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
