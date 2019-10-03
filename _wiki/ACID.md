---
layout  : wiki
title   : ACID
summary : 트랜잭션의 중요한 네 가지 속성
date    : 2019-10-03 00:33:18 +0900
updated : 2019-10-03 00:44:57 +0900
tag     : 
toc     : true
public  : true
parent  : proverb
latex   : false
---
* TOC
{:toc}

# 개요

네 가지 속성의 이니셜을 따서 ACID라 부른다.

다음은 "트랜잭션 처리의 원리"에서 인용한 것이다.[^list]

>
* 원자성(atomicity): 트랜잭션은 모두 실행되거나 아예 실행되어서는 안된다.
* 일관성(consistency): 트랜잭션은 데이터베이스의 내부 일관성을 지켜야 한다.
* 고립성(isolation): 트랜잭션은 독립적으로 실행되어야 하고, 다른 트랜잭션과 섞여 실행되면 안된다.
* 영속성(durability): 트랜잭션의 결과는 시스템 실패로 유실되면 안된다.




# 참고문헌

* 트랜잭션 처리의 원리 / 필립 A. 번스타인, 에릭 뉴코머 공저 / 한창래 역 / KICC(한국정보통신) / 1판 1쇄 2011년 12월 19일

# 주석

[^list]: 트랜잭션 처리의 원리. 1.3 원자성, 일관성, 고립성, 영속성. 26쪽.