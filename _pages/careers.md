---
layout: single
title: Careers
permalink: /careers/
author_profile: true
read_time: false
comments: false
share: false
related: false
---

* Jinhyuck Kim
* Software Engineer
* Email: [bluerivers.starkid@gmail.com](mailto:bluerivers.starkid@gmail.com)


## Interest

* Organization - Leadership, Culture, Performance Management, Communication
* Software Developer - Software Craftsmanship, Agile, Professionalism, DevOps, Large-scale system, Reactive system
* Private - Major League Baseball(including [sabermetrics](https://en.wikipedia.org/wiki/Sabermetrics)), Fitness, Fashion, Liquor


## Work Experience

### FingerPlus, Seoul, Korea
* Position
  * Senior Engineer - 2017.04 ~ 2018.01
  * Lead Engineer - 2018.02 ~
* Achievements
  * Migrate EC2 and other component into VPC in AWS and setup VPN server/client to enhance service security
    * AWS VPC, AWS EC2, Network, OpenVPN
  * Design and implement [Player API v1](https://developer.video-tag.kr/player/overview.html)
    * Replace old Player API beta to avoid exposing API key externally
    * Issue page view token through server-to-server communication to use for client to request API server
    * Define new player user log format and modify Player API backend to send new log stream to make log analysis deepen
    * AWS API Gateway, AWS Lambda, AWS DynamoDB, [Serverless Framework](https://serverless.com/), JWT(Json Web Token)
    * Heading to construct [reactive system](https://www.reactivemanifesto.org/)
  * Change deployment from VM to Docker
    * AWS ECS, Docker
  * Design and implement [Advertiser API v1](https://developer.video-tag.kr/advertiser/overview.html)
    * Integrate another AD system by integrating API
    * Implement Bulk Request API
    * HapiJS, OAuth 2.0 (Client Credentials), JWT
  * Restructuring legacy system
    * Overcome slower developing speed, frequent unintended errors due to monolithic and tightly-coupled legacy system
    * Motivated from optimistic concurrency, state management in the [Kubernetes](https://kubernetes.io)
    * De-couple video meta, advertisement, and statisitics system respectively
      * Event driven - AWS SQS
      * Detect state change as compared with latest data
    * De-couple system to use not [SMR](http://www.smartmediarep.com) clip, also general-purpose video clip (In progress)
  * Substitute AWS Lambda into server in Player API backend (In progress)
    * Overcome the limitations with AWS Lambda - unknown error, and slow scaling speed, and hard to customize configuration
    * Achieve both 100 TPS and ~100ms response time per 1 application in peak time
  * Etc
    * Define code, API, and message convention for engineers
    * Introduce jira and confluence into company
    * Organize monthly study sessions (OpenLab) in engineering group
      * Make engineer [blog](https://fingerplus.github.io/) using Jekyll


### Opensurvey(ex. IDINCU), Seoul, Korea
* Position
  * Senior Engineer - 2016.04 ~ 2017.03
  * CTO - 2012.04 ~ 2016.03
  * iOS Developer - 2011.07 ~ 2012.03
* Achievements
  * Design new survey/response data structure and relationship between modules
  * Develop functions to use external survey reference in legacy response modules
  * OPENSURVEY
    * From 1.0 to 2.0
    * Manage OPENSURVEY accounts including registration, authentication and authority
    * Spring (Spring Boot), MyBatis, JPA, HTML/CSS, LESS, Javascript, jQuery, Redis, Spring Security, Spring Session
  * Common Questionnaire Modules
    * Improve performance function to store responses asynchronously using RabbitMQ
    * Implement _Question Group Rotation_ feature and _External Questionnaire Reference_ feature and so on
    * Re-design front/backend module
    * Spring, Struts2, MyBatis, Javascript, jQuery, RabbitMQ, Node.js, React, Kafka
  * OVEY
    * Develop and maintain OVEY 1.0 iOS Application
    * Develop single sign on system related with OPENSURVEY and OVEY
    * Develop shop and account managing system in OVEY
    * Spring (Spring Boot), MyBatis, HTML/CSS, LESS, Javascript, jQuery
  * Re-construct legacy system (From monolithic to MSA)
    * Adapt REST API
    * Introduce Apache Kafka for messaging system
    * Introduce Netflix Eureka for service registry/discovery system
  * Etc
    * Introduce gerrit, jira and confluence into engineering team
    * Establish code conventions including Java, Javascript, html/css
    * Introduce ployglot (Java, Javascript, Python)


### Memory Division, Samsung Electronics, Hwasung, Korea
* Position
  * Associate Software Engineer - 2010.03 ~ 2011.07
  * Software Engineer - 2008.02 ~ 2009.02
* Achievements
  * Develop and maintain NAND Flash Firmware (FTL, Flash Translation Layer) - applied to embedded storage, especially, OneNAND and Flex-OneNAND
    * STL (Sector Translation Layer) from 1.1 to 1.2
      * Improve wear-leveling algortithm (10% improvement) - count/store wearing(erase) count per block and calculate a minimum erase count block to use next block to use
    * Maintain BML(Block Management Layer) and LLD (Low-Level Device layer)
  * Develop UFD(USB Flash memory Drive) UA1
    * Study existing FTL technologies
    * Design architectures for next generation storage device


## Education

### Master's degree, Computer Science and Engineering, Seoul National University (2006 - 2008)
* Mobile Embedded System Lab.
* Achievements
  * Implement NAND flash driver and block device driver
  * Implement the static analyzer of C-- (Subset of C) and that of Effective Inference
  * Research towards obtaining IPRs for mobile applications (with Pantech)
    * Patent - _통합 IP 메시지 시스템의 일대다 파일전송 방법(Method for Transmitting a File or More from One Device to Many under the Converged IP Messaging System)_
  * 지상파 DTV 방송프로그램 보호 기술 개발 (with ETRI, 한국전자통신연구원)
  * Research media sharing and multi-device support protocol within CPM system (with Samsung Electronics)
  * Research for next generation flash memory storage (with Archi Lab. in SNU, Samsung Electronics, Hanyang University, M-tron, and so on)
* Publication
  * Enhancement of CPM (Converged IP Messaging) System - 2008.02
* Awards
  * Samsung Electronics Scholarship, Samsung Electronics - 2007.03


### Bachelor's degree, Computer Science and Engineering, Seoul National University (2002 - 2006)
* Publication
  * Implementation of GTP(Game Transport Procotol) - 2006.02
* Awards
  * Graduation with Honors (Cum Laude), Seoul National University - 2006.02


## Skills & Expertise
* Programming Languages
  * Java
  * Javascript
  * C/C++
  * Groovy (Elementary)
  * Python (Elementary)
  * Objective-C
  * nML
* Deployment
  * Docker
  * AWS ECS
  * Kubernetes (in Study)
* Framework / Library
  * Java
    * Spring Framework - Spring Boot, Spring Security, Spring Session, Spring Cloud
    * Test Framework - JUnit, Spock, and so on
  * JS (Javascript)
    * Front
      * jQuery
      * React (Elementary)
    * NodeJS
      * ExpressJS
      * HapiJS
    * Test framework - mocha, chai, jest, and so on
* Markup - HTML/CSS/LESS/SCSS
* Databases
  * MySQL
  * DynamoDB in AWS
* Embedded System
  * Trace32
  * ARM architecture


## Languages
* Korean (Native)
* English (Intermediate)


## Publications

### Translation
* [테스트 주도 iOS 애플리케이션 개발](http://www.acornpub.co.kr/book/test-driven-ios) - ACORN, 2013.11.20
* [새로 보는 프로그래밍 언어 \[개발자의 가치를 높이는 프로그래밍 언어 대백과\]](http://www.acornpub.co.kr/book/programming-language) - ACORN, 2008.08.21
* [TCP/IP 완벽 가이드](http://www.acornpub.co.kr/book/tcpip) - ACORN, 2007.01.22
