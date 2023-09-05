# 🏫 Bucky Education Platform


<img width="1000" alt="image" src="https://github.com/Tyler03118/Edu_SpringCloud/assets/113784268/6c129f6a-3c06-488f-9f3d-4b8f7c24cbce">



## 🧮 Project Introduction
The Guli Education project is dedicated to building a B2C model for vocational skills online education systems, using popular technologies at this stage and adopting a front-end and back-end separation approach. 

It is a comprehensive online education platform, including both front-end systems and back-end management systems, implemented based on SpringCloud, SpringCloud Alibaba, and MyBatis Plus. The front-end system includes modules such as user login, registration, teacher list, teacher details, course list, course details, and online video playback. The back-end management system includes modules such as home, permission management, lecturer classification, course classification, course management, and statistical analysis.
<br>
(Only backend source code are included)
## :accessibility: Backend Structure
```
guli-parent
├─common  
├─service-acl -- access management
├─service-teacher -- instructor module
├─service_cms -- slides management
├─service_common -- common module
├─service_msm -- message module
├─service_order -- order module
├─service_oss -- OSS module
├─service_statistics -- statistics module
├─service_ucenter -- user module
├─service_vod -- video module
└─infrastructure
    └─api_gateway -- gateway module
```
## 🪗 Frontend Structure
```
guli-web
├─ guli_admin  -- backend UI
└─ guli_front  -- fronend UI
```
## 🩹 Skills
### Backend
| Skills         | Usage | Official Website         |
| ------------------ | ------------- | ----------------------------------------------- |
| SpringBoot         | Container+MVC Framework | https://spring.io/projects/spring-boot          |
| SpringCloud        | Microservices | https://spring.io/projects/spring-cloud         |
| SpringCloudAlibaba | Components | https://spring.io/projects/spring-cloud-alibaba |
| MyBatis-Plus       | ORM Framework     | https://mp.baomidou.com                         |
| Mysql   | Database            | https://www.mysql.com                    |
| Redis   | Database for cache        | https://redis.io/download                |
| Nginx   | Loadbalance          | http://nginx.org/en/download.html        |
| OSS                | Object Storage Service | https://github.com/aliyun/aliyun-oss-java-sdk   |
| EasyExcel          | Excel Manipulation | https://www.yuque.com/easyexcel/doc             |
| Docker             | Container | https://www.docker.com                          |
| jenkins            | Automation Deploy | https://www.jenkins.io/                         |

### Frontend
| Skills         | Usage | Official Website         |
| ---------- | -------------- | ---------------------------------------- |
| Vue        | Frontend Framework   | https://vuejs.org                        |
| Element-ui | Frontend UI Framework | https://element.eleme.cn/#/zh-CN         |
| Nuxt       | Frontend UI Framework | https://zh.nuxtjs.org/                   |
| node.js    | JS on service-side| https://nodejs.org/en                    |
| Echarts    | Data Visualization | https://echarts.apache.org/zh/index.html |

## 🚡 Project Highlights
- Responsible for backend RestFul API development and management using Swagger for rapid development.
- Adopted Nacos as a registration and configuration center, with Gateway for microservices authentication.
- Employed Feign with HttpClient for remote calls and Ribbon for load balancing.
- Implemented login functionality and authentication between microservices using JWT, enhancing
user experience.
- Conducted basic flow control tests and fallback programs to ensure service degradation feasibility.
- Utilized Alibaba Cloud technologies for object storage, video-on-demand, and SMS verification services.
