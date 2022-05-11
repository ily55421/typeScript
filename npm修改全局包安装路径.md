## npm修改全局包安装路径

```npm
npm config set prefix "E:/Developer/nodejs/npm_global"
npm config set cache "E:/Developer/nodejs/npm_cache"
```

## node.js更换镜像源 

1、首先输入 npm get registry 查看当前镜像源，

```
npm get registry

https://registry.npmjs.org/（npm默认镜像源）
```

2，修改镜像源 npm config set registry xxx(镜像源地址)，国内一般使用淘宝镜像源 

```
npm config set registry https://registry.npm.taobao.org
```

3，npm 修改成功，输入 npm get registry 再次查看镜像源

```
npm get registry

// 公司镜像源
http://cd.dreamdt.cn:23106/

// 修改为淘宝源
PS D:\> npm config set registry https://registry.npm.taobao.org
PS D:\> npm get registry
https://registry.npm.taobao.org/
```

![1652235750344](image/1652235750344.png)

