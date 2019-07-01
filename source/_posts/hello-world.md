---
title: Jingle 赚闲钱项目 系统分析与设计
---


## 目录

- 1、[About 项目规划](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/1.AboutJingle.md)

- 2、[Team profile 团队组建](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/2.%E5%9B%A2%E9%98%9F%E7%BB%84%E5%BB%BA.md)

- 3、[Investigation 项目前期调研](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/3.%E9%A1%B9%E7%9B%AE%E9%9C%80%E6%B1%82%E8%B0%83%E7%A0%94%E5%88%86%E6%9E%90.md)

- 4、[Vision 项目愿景](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/4.%E9%A1%B9%E7%9B%AE%E6%84%BF%E6%99%AF.md)

- 5、[Product Backlog 产品特性](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/5.%E4%BA%A7%E5%93%81%E7%89%B9%E6%80%A7.md)

- 6、Requirement specification 需求规格说明

    - 6.1 [Usecase Diagram](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E9%9C%80%E6%B1%82%E8%A7%84%E6%A0%BC%E8%AF%B4%E6%98%8E/%E7%94%A8%E4%BE%8B%2B%E6%B4%BB%E5%8A%A8%E5%9B%BE.png)
    - 6.2 [Usercase Diagram and UML Activity Diagram 用例+活动图](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E9%9C%80%E6%B1%82%E8%A7%84%E6%A0%BC%E8%AF%B4%E6%98%8E/%E7%94%A8%E4%BE%8B%2B%E6%B4%BB%E5%8A%A8%E5%9B%BE.png)
    - 6.3 [Domian Model 领域模型](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E9%9C%80%E6%B1%82%E8%A7%84%E6%A0%BC%E8%AF%B4%E6%98%8E/%E9%A2%86%E5%9F%9F%E6%A8%A1%E5%9E%8B.png)
    - 6.4 [State Model 状态模型](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E9%9C%80%E6%B1%82%E8%A7%84%E6%A0%BC%E8%AF%B4%E6%98%8E/%E7%8A%B6%E6%80%81%E6%A8%A1%E5%9E%8B.md)
    - 6.5 [System Sequence Diagram 功能模型](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E9%9C%80%E6%B1%82%E8%A7%84%E6%A0%BC%E8%AF%B4%E6%98%8E/%E5%8A%9F%E8%83%BD%E6%A8%A1%E5%9E%8B.md)
    - 6.6 Supplementary Requirements 补充性说明

- 7、Design 设计
    - 7.1 UX design UX 交互设计
        - 7.1.1 [全局 UX 设计](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/7.1.1Jingle%20%E5%85%A8%E5%B1%80%E4%BA%A4%E4%BA%92%E8%AE%BE%E8%AE%A1.md)
        - 7.1.2 [各页面 UX 设计](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/7.1.2Jingle%20%E5%90%84%E9%A1%B5%E9%9D%A2%E4%BA%A4%E4%BA%92%E8%AE%BE%E8%AE%A1.md)
    - 7.2 [Prototype and UI Design 原型与UI设计](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/7.2Jingle%20%E5%8E%9F%E5%9E%8B%E4%B8%8EUI%E8%AE%BE%E8%AE%A1.md)
    - 7.3 [Database design 数据库设计](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1%E6%96%87%E6%A1%A3/%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1%E6%96%87%E6%A1%A3.md)
    - 7.4 [模块及API 设计](https://github.com/systemanalyse/raiseMoney/blob/master/docs/Design%20%E8%AE%BE%E8%AE%A1/%E6%A8%A1%E5%9D%97-API%E8%AE%BE%E8%AE%A1%E6%96%87%E6%A1%A3.md)
    - 7.5 [软件架构文档](https://github.com/systemanalyse/raiseMoney/blob/master/docs/Design%20%E8%AE%BE%E8%AE%A1/%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E8%AF%B4%E6%98%8E%E6%96%87%E6%A1%A3.md)
    - 7.6 [用例设计](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E9%9C%80%E6%B1%82%E8%A7%84%E6%A0%BC%E8%AF%B4%E6%98%8E/%E7%94%A8%E4%BE%8B%2B%E6%B4%BB%E5%8A%A8%E5%9B%BE.png)

- 8、生产规范与指南

    - 8.1 [代码规范](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/8.1%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83.md)
    - 8.2 [REST API设计规范](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E7%94%9F%E4%BA%A7%E8%A7%84%E8%8C%83%E4%B8%8E%E6%8C%87%E5%8D%97/API_RaiseMoney.md)
    - 8.3 框架目录设计与逻辑架构与 ECB 的关系
    - 8.4 [部署文档](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E5%AE%89%E8%A3%85%E9%83%A8%E7%BD%B2%E8%AF%B4%E6%98%8E.md)
- 9、 [Software Test 软件测试文档](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E6%96%87%E6%A1%A3.md)

- X1 meet_recording
    - [Meeting Recording](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/%20MeetingRecording.md)
    - [Iteration X Meeting](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%BA%A7%E5%93%81%E6%96%87%E6%A1%A3/IterationXMeeting.md)

- X2 Tech/Work Report

    - [16340003-互联网产品设计和用户体验小科普](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E6%8A%80%E6%9C%AF%E5%8D%9A%E5%AE%A2/TechReport16340003BaiYuge.md)
    - [16340003-如何进行可用性测试](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E6%8A%80%E6%9C%AF%E5%8D%9A%E5%AE%A2/TechReport2_16340003BaiYuge.md)
    - [16340241-Android开发 Fragment的子Fragment+TabLayout+ViewPager 的使用](https://blog.csdn.net/wxlSAMA/article/details/94357598)
    - [16340241-Android开发 TabLayout 选中改变字体大小颜色、指示线](https://blog.csdn.net/wxlSAMA/article/details/94358759)
    - [16340241-Android开发 实现点击缩略图查看大图的功能](https://blog.csdn.net/wxlSAMA/article/details/94355377)
    - [16340241-Android开发 图片加载库 Glide 的使用](https://blog.csdn.net/wxlSAMA/article/details/94352501)
    - [使用swagger编写TESTFul的API文档](https://blog.csdn.net/Yanzu_Wu/article/details/94354972)

- X3 Final Report
    - [16340118-CarolSum](https://blog.csdn.net/bkjs626/article/details/94137876)
    - [16340003-BaiYuge](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%B8%AA%E4%BA%BA%E6%8A%A5%E5%91%8A/16340003-BaiYuge.md)
    - [16340227-wyj16340227](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%B8%AA%E4%BA%BA%E6%8A%A5%E5%91%8A/%E4%B8%AA%E4%BA%BA%E6%8A%A5%E5%91%8A-%E7%8E%8B%E6%B0%B8%E6%9D%B0-16340227.md)
    - [16340098-Chris-Ju](https://github.com/systemanalyse/raiseMoney/blob/master/docs/%E4%B8%AA%E4%BA%BA%E6%8A%A5%E5%91%8A/16340098_jubo.md)
    - 16340220-WangPerryWPY
    - [16340241-blesswxl](https://blog.csdn.net/wxlSAMA/article/details/94360793)

- X4 Supplement

    - [Jingle 产品需求文档（完整）](https://github.com/systemanalyse/raiseMoney/blob/master/docs/Jingle%E8%BD%AF%E4%BB%B6%E9%9C%80%E6%B1%82%E8%AF%B4%E6%98%8E%E4%B9%A6.md)

    

