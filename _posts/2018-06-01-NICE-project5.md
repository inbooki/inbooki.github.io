---
layout: post
title: 중요단말기 망분리 구축
date: 2018-06-01 12:00 +0800
last_modified_at: 2019-10-10 12:00 +0800
tags: [project]
toc: false
---

#### 프로젝트 역할: 기획/PM/운영

- 전자금융감독규정 제12조 (단말기 보호대책)의 “중요단말기 지정”에 따른 사내 망분리 서비스 기획/보안성 검토 수행
- **망분리 서비스(VDI, VPN, 망연계 솔루션, 500user)** 설계 및 구축(PM) 수행
    + VDI(VMware), VDI 자동배포 솔루션(Powershell script, VMWare API, Web admin), 망연계 솔루션, 사용자 환경 마이그레이션 기획/수행
- **성과**
    + 신규 입사자 초기 환경셋팅 시간 1일 → 0일(즉시 업무 시작)
    + 단말간 클립보드 제공을 통한 업무 편의 증대(text 전송 소요 시간 약 40초 → 5초)
    + 서비스의 안정적 도입을 위한 현업/개발/운영 부서와의 협조를 통한 communication skill 향상