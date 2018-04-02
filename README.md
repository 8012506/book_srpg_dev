# **《SRPG游戏开发》导航**

----------

The program of book 《SPRG游戏开发》(《SRPG Game Development》).

----------

# **目录(Menu)**

## 前言

>为什么写这些文章与使用的开发工具
>
>[https://blog.csdn.net/darkrabbit/article/details/79111027](https://blog.csdn.net/darkrabbit/article/details/79111027)

## 第一章 FE4部分技术简述

>挑选一些典型的技术进行简述
>
>[https://blog.csdn.net/darkrabbit/article/details/79118504](https://blog.csdn.net/darkrabbit/article/details/79118504)

## 第二章 创建项目

>创建项目与导入Unity的Tile组件
>
>[https://blog.csdn.net/darkrabbit/article/details/79133620](https://blog.csdn.net/darkrabbit/article/details/79133620)

## 第三章 绘制地图

一 导入素材

>Inspector
>
>导入贴图素材与设置
>
>[https://blog.csdn.net/darkrabbit/article/details/79168225](https://blog.csdn.net/darkrabbit/article/details/79168225)

二 绘制一张简单地图

>Unity Component
>
>Grid与素材的关系，以及如何绘制Tilemap
>
>[https://blog.csdn.net/darkrabbit/article/details/79177935](https://blog.csdn.net/darkrabbit/article/details/79177935)

三 创建自己的SrpgTile

>ScirptableObject
>
>如何自定义一个带数据的Tile，以及修改Rule Tile
>
>[https://blog.csdn.net/darkrabbit/article/details/79181945](https://blog.csdn.net/darkrabbit/article/details/79181945)

四 初步完善地图编辑器(Map Graph)

>MonoBehaviour，Editor，编辑器扩展
>
>如何在Scene面板中绘制文字与辅助线
>
>[https://blog.csdn.net/darkrabbit/article/details/79212137](https://blog.csdn.net/darkrabbit/article/details/79212137)

## 第四章 图集(Atlas)

>Inspector
>
>如何打包图集，与Draw Call的关系
>
>[https://blog.csdn.net/darkrabbit/article/details/79212625](https://blog.csdn.net/darkrabbit/article/details/79212625)

## 第五章 颜色映射(Palette Swap)与职业动画(Class Animator)

一 颜色映射流程(Flow Chart)

>Flow Chart
>
>颜色映射的流程图
>
>[https://blog.csdn.net/darkrabbit/article/details/79266426](https://blog.csdn.net/darkrabbit/article/details/79266426)

二 颜色组(Color Chart)
>ScriptableObject
>
>实现颜色组
>
>[https://blog.csdn.net/darkrabbit/article/details/79266433](https://blog.csdn.net/darkrabbit/article/details/79266433)

三 颜色转换器(Color Swapper)

>MonoBehaviour
>
>实现颜色转换器
>
>[https://blog.csdn.net/darkrabbit/article/details/79266439](https://blog.csdn.net/darkrabbit/article/details/79266439)

四 测试与创建Class Animator

>AnimatorController
>
>测试颜色映射，创建职业的动画
>
>[https://blog.csdn.net/darkrabbit/article/details/79266446](https://blog.csdn.net/darkrabbit/article/details/79266446)

五 修正颜色转换器(Fix Color Swapper)

>MonoBehaviour
>
>修正在动画中不能颜色映射的错误
>
>[https://blog.csdn.net/darkrabbit/article/details/79266457](https://blog.csdn.net/darkrabbit/article/details/79266457)

六 颜色组编辑器(EditorWindow)

>Editor，EditorWindow，编辑器扩展
>
>更方便的调整颜色
>
>[https://blog.csdn.net/darkrabbit/article/details/79266462](https://blog.csdn.net/darkrabbit/article/details/79266462)

七 减少Draw Call与使用Cache
>CSharp
>
>创建缓存，减少颜色映射的Draw Call
>
>[https://blog.csdn.net/darkrabbit/article/details/79266467](https://blog.csdn.net/darkrabbit/article/details/79266467)

## 第六章 基础框架(Framework) （待定）待整理

一 本章简介(Introduction)

>Introduction
>
>源代码文件的简介
>
>[https://blog.csdn.net/darkrabbit/article/details/79535095](https://blog.csdn.net/darkrabbit/article/details/79535095)

二 单例(Singleton)

>CSharp，MonoBehaviour
>
>普通单例与MonoBehaviour单例
>
>[https://blog.csdn.net/darkrabbit/article/details/79535119](https://blog.csdn.net/darkrabbit/article/details/79535119)

三 消息事件(Message Center)

>CSharp
>
>消息事件系统，注册（注销，分发）消息
>
>[https://blog.csdn.net/darkrabbit/article/details/79579918](https://blog.csdn.net/darkrabbit/article/details/79579918)

四 程序入口(Appication Entry)

>MonoBehaviour
>
>游戏入口，扩展SceneManager
>
>[https://blog.csdn.net/darkrabbit/article/details/79597349](https://blog.csdn.net/darkrabbit/article/details/79597349)

五 对象池(Object Pool)

>MonoBehaviour
>
>对象的生成与回收
>
>[https://blog.csdn.net/darkrabbit/article/details/79790087](https://blog.csdn.net/darkrabbit/article/details/79790087)

六 配置文件(Config File)

>CSharp
>
>配置文件的读取等
>
>[https://blog.csdn.net/darkrabbit/article/details/79790119](https://blog.csdn.net/darkrabbit/article/details/79790119)

七 视图管理器(View Manager)

>Csharp，MonoBehaviour
>
>视图的管理，打开关闭等
>
>[https://blog.csdn.net/darkrabbit/article/details/79790164](https://blog.csdn.net/darkrabbit/article/details/79790164)


## 第七章 移动(Move)与寻路(AStar) 待整理

>显示移动范围(move range)和攻击范围(attack range)，还有寻路(A*)

## 第八章 地图事件(Map Event) 待整理

>地图事件部分

## 第九章 技能(Skill)与道具(Item) 待整理

>技能与道具

## 待定章 to be continue

>未确定章节

----------

## **Project in GitHub**

[Test Version](https://github.com/DarkLop/book_srpg_dev)