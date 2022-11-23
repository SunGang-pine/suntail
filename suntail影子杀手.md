# 从〇开始学前端

> 时间：2022年11月21日09:30:53
>
> 最近，处于低谷，不知道每天在干什么，内心也非常的烦躁，每到周六周日，都不想要学习。而在周一到周五，又很信心满满的。我是谁，我在哪，我在干什么？
>
> **冴羽的学习是为了什么？我该学什么？我该怎么学？对应到 6W 分析法中，分别是 Why？What？How？**：**https://github.com/mqyqingfeng/Blog/issues/308**



费曼学习法：

- 而所谓的费曼学习法其实很简单，它的核心是——当你准备学习一门新知识时，必须站在传授者的立场，假设自己要向别人讲解这门知识。那么你一定要用最简洁、清晰和易于理解的语言表达出来，才能让行外的人也能听懂。费曼说：“最好是几岁的小孩也能明白你在说什么。”





这个文档的书写过程

1. 首先在语雀中编写计划：https://www.yuque.com/songguopinenut/adbgu1/tga40plt79x63hga#an5px9xtwa2uq3ffy7p7g1cgv2kauy5g
2. 每天制定一个计划，然后执行他。
3. 每天提交到github







参考资料：

1. 千古图文：https://web.qianguyihao.com/#%E5%89%8D%E8%A8%80
2. 前端面试之道yck：
   - https://yuchengkai.cn/
   - 30多块钱买的，前端面试之道：https://appstyndchc4700.h5.xiaoeknow.com/p/course/column/p_62eb4931e4b00a4f372f29ec?type=3&share_user_id=u_630444873a380_tOqYPBnaXs&share_type=5&scene=%E5%88%86%E4%BA%AB&entry=2&entry_type=2002
3. 被删的前端游乐场：http://www.godbasin.com/
4. [其他的东西在各个章节，进行补充。]





文档目录结构，参考JavaGuide的面试突击版。

# 0. 前端

## 0.1 什么是前端

> http://www.godbasin.com/front-end-basic/front-end/front-end-1.html



## 0.2 开发前端的工具

### 0.2.1 VS Code

> 全面解析：https://web.qianguyihao.com/00-%E5%89%8D%E7%AB%AF%E5%B7%A5%E5%85%B7/01-VS%20Code%E7%9A%84%E4%BD%BF%E7%94%A8.html



一些插件：



### 0.2.2 Git

> 代码重工的Git教程，图文并茂：http://heavy_code_industry.gitee.io/code_heavy_industry/pro008-Git/lecture/
>
> 加强：https://web.qianguyihao.com/00-%E5%89%8D%E7%AB%AF%E5%B7%A5%E5%85%B7/02-Git%E7%9A%84%E4%BD%BF%E7%94%A8.html



- 将本地库的东西上传至远程库(github)。按照基础步骤就好了。

> https://github.com/SunGang-pine/emptyProject

```
echo "# emptyProject" >> README.md											// 创建一个README.md的文件
git init																	// 初始化git
git add README.md															// 将README.md加入暂存区
git commit -m "first commit"												// 将暂存区的文件提交到本地库
git branch -M main															// 将当前分支重命名为main
git remote add origin git@github.com:SunGang-pine/emptyProject.git			// 添加一个远程版本库，别名为origin
git push -u origin main														// 以下命令将本地的 main 分支推送到 origin 主机的 main 分支
```



- 一些基础的概念

```
- 初始化git init
- 克隆git clone


- git status：位于那个分支


- git add .  ：工作区文件全部添加到暂存区
- git commit -m "firstmark"：暂存区提交到本地库，并附带注释
- 
- git push origin master：提交到远程库
- git pull ：拉代码
- 
- git branch -a ：查看全部分支
- git checkout -b dev：创建新的分支
- git checkout master：切换到master分支
- git merge dev：在master分支合并dev分支
- git branch -D dev：删除本地dev分支

如果想要删除远程的dev分支？

- git push origin :dev：为空放到dev中，即为删除
- 
- git reset --hard head^：回退到之前的那个版本（初始提交）操作
- 
- git reflog：查看日志
- git log：查看提交历史
- git reset --hard HEAD@{1}：回退指定位置(后面可以为代码参数)
```



- Git的客户端工具



# 1. HTML

## 1.1 什么是HTML

## 1.2 HTML的语义化





# 2. CSS

## 1.1 什么是CSS

## 1.2 CSS的一些基础概念



# 3. JavaScript

快速ES6：https://github.com/LuRenJiasWorld

完成版ES6：https://wangdoc.com/es6/

## 1.1 什么是JavaScript

## 1.2 JavaScript的一些基础概念



## 2.1 什么是ES6

## 2.2 ES6的一些基础概念



## 3.1 什么是TS

## 3.2 TS的一些基础概念



# 4. 框架

## 4.1 Vue

### 4.1.1 什么是Vue

### 4.1.2 Vue的一些基础概念



## 4.2 React

### 4.2.1 什么是React

### 4.2.2 React的一些基础概念



## 4.3 微信小程序

### 4.3.1 什么是微信小程序

### 4.3.2 微信小程序的一些基础概念



## 4.4 Uniapp

### 4.4.1 什么是Uniapp

### 4.4.2 Uniapp的一些基础概念





# 999、面试

> 注意事项~~~~
