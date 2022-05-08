---
title: Security Script Tool
layout: post
post-image: "/assets/images/pj1"
description: Linux 보안 점검 자동화 툴
tags:
- ShellScript
- Security
- Linux
---

Linux 환경에서 일반 사용자의 su 명령어 사용 여부, umask 값 이상 여부, PATH 환경 변수 점검, SUID/SGID/Sticky Bit 설정 점검 스크립트를 작성했다. 기본적인 시스템 환경 설정 파일 점검을 할 수 있으며 로그 및 결과 파일을 출력하는 하나의 자동화 툴로 만들었다.

---

## 기간
##### 2020. 04 ~ 2020. 07
#

## 기능
##### 1. 일반 사용자의 su 명령어 사용 여부 점검
##### 2. umask 값 점검
##### 3. PATH 환경 변수 특수 문자 점검
##### 4. 일반 사용자의 Cron Tab 접근 권한 제한 점검
##### 5. SUID, SGID, Sticky Bit 설정 점검
#
![Tool img](/assets/images/pj1-1.png)
실제 구동 모습

