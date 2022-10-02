# 校园生活圈小程序
拥有 表白墙、失物招领、兼职、闲置物品等功能

## 基于云开发（参考文档）
- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

## 部署教程
1. 将该项目导入微信开发者工具
2. 更改 miniprogram/app.js 里面的云环境id
``` bash
wx.cloud.init({
	env:'xxx',  //xxx为你的云环境id
    traceUser: true
})
```
3. 创建对应的五个数据库集合（biaobai、found、lost、xianzhi、jianzhi）
4. 将 cloudfunctions 文件下的四个文件上传云函数部署（右键点击，选择第三个选项“上传并部署：云端安装环境”）
## 程序截图
### 首页
<width = "108px" height = "234px" align=“center”></img>
### 我的
<img src=" width = "108px" height = "234px" align=“center”></img>
### 表白墙
<width = "108px" height = "234px" align=“center”></img>
### 失物招领
<width = "108px" height = "234px" align=“center”></img>
<width = "108px" height = "234px" align=“center”></img>
### 兼职
<width = "108px" height = "234px" align=“center”></img>
<width = "108px" height = "234px" align=“center”></img>
### 闲置
<width = "108px" height = "234px" align=“center” />
<width = "108px" height = "234px" align=“center” />
<width = "108px" height = "234px" align=“center” />