# GuliEducationPlatform_SpringCloud

# Project Introduction
The Guli Education project is dedicated to building a B2C model for vocational skills online education systems, using popular technologies at this stage and adopting a front-end and back-end separation approach. 

It is a comprehensive online education platform, including both front-end systems and back-end management systems, implemented based on SpringCloud, SpringCloud Alibaba, and MyBatis Plus. The front-end system includes modules such as user login, registration, teacher list, teacher details, course list, course details, and online video playback. The back-end management system includes modules such as home, permission management, lecturer classification, course classification, course management, and statistical analysis.

# Backend Structure
guli-parent
├─common  
├─service-acl -- 权限管理模块
├─service-teacher -- 讲师模块
├─service_cms -- 幻灯片管理模块
├─service_common -- 公共模块
├─service_msm -- 阿里短信模块
├─service_order -- 订单模块
├─service_oss -- 阿里OSS模块
├─service_statistics -- 数据统计模块
├─service_ucenter -- 会员模块
├─service_vod -- 阿里视频点播模块
└─infrastructure 
    └─api_gateway -- 网关模块
