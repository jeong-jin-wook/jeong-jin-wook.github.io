---
layout: post
title: "패키지 매니저(Package Manager)"
author: "jjw"
tags: [npm, yarn]
---

## ● 패키지 매니저

패키지(라이브러리)를 다루는 작업을 편리하고 안전하게 수행하기 위한 툴

패키지(라이브러리)를 다루는 작업은 설치, 업데이트, 삭제 등의 작업을 의미한다.

## ● Dependency

많은 패키지들은 다른 패키지가 설치되어 있어야만 제대로 동작한다.

이 경우에 기존 패키지를 제대로 동작시키기 위해 필요한 다른 패키지를 'dependency'라고 말한다.

각각의 패키지가 자신의 dependency에 대한 정보를 가지게 한다면, 사용자가 사용하고자 하는 패키지의 dependency를 패키지 매니저를 통해 쉽게 설치하도록 도울 수 있다.

## ● Software repository

패키지를 저장하고 관리되는 저장소

커뮤니티에 기여하는 것을 목적으로 다른 사용자들을 위해 패키지를 등록 할 수도 있다.

## ● 패키지 매니저의 역할

1. 패키지의 dependency 관리
2. 패키지의 보안관리 ( 인증, 무결성 보장)
3. 패키지 기능에 따라 그룹으로 묶어서 정리
4. 패키지 압축 해제
5. Software repository로부터 패키지를 찾고, 다운로드, 설치, 업데이트 역할 수행

## ● 패키지 매니저의 예

패키지 매니저는 운영체제와 프로그래밍 언어에서 사용되는 툴이다.

Ubuntu 운영체제의 apt(Advanced Package Tool)가 대표적인 운영체제 패키지 매니저의 예다.

| Language | Package manager  | software repository |
| -------- | ---------------- | ------------------- |
| node.js  | npm,yarn         | npm,yarn            |
| java     | maven,gradle     | maven               |
| python   | pip              | PyPI                |
| php      | composer         | packagist           |
| ruby     | rybygems,bundler | rubyGems,bundler    |

<br/>
<br/>
<br/>
출처 :

https://aahc.tistory.com/14
