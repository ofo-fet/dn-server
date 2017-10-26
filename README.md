# ofo-dawn
ofo dawn server

---

## step one

### conf dn server to ofo dn server
dn config server https://raw.githubusercontent.com/ofo-hooper/ofo-dawn/master

这里的 github 路径并非 git 上的页面路径,而是 git file 的原始路径.
获取原始路径的方式:

    Click the Raw button to get the raw URL for a file.

参考: https://help.github.com/articles/limits-for-viewing-content-and-diffs-in-a-repository/


## step two

### 创建私有的脚手架(模板/ template).
### npm publish(首次需要 npm adduser/ npm login)

publish 要注意你发布到那个源上, 如果是官方源, 切回 npm 的 registry.
npm config set registry http://registry.npmjs.org

淘宝镜像: --registry=https://registry.npm.taobao.org
