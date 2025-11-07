---
title: "[New ABAP] VALUE #( )"
excerpt: "VALUE #( )"

categories:
  - SAP ABAP
tags:
  - [ABAP, VALUE #]

permalink: /sapabap/value

toc: true
toc_sticky: true

date: 2025-11-07
last_modified_at: 2025-11-07
---

## 🦥 본문

### VALUEㅤ#
#### 개념
타입 추론(type inference) 을 통해, 변수의 선언된 타입에 맞게 초기값을 자동으로 생성해요.
'#'은 컴파일러가 데이터 타입을 유추하도록 하는 기호에요.
'#'자리에 type ( 예를 들어, TY_S_DATA, LS_DATA, I, WERTV12 )가 들어갈 수도 있어요.


#### 목적
1. 코드 가독성 향상
2. 타입 명시 없이 안전하게 초기화
3. 내부 테이블/구조 초기 선언 시 편리


#### 예시
'''abap
DATA(ls_emp) = VALUE ty_employee( id = 100 name = 'LEE' ).
DATA(lt_emp) = VALUE ty_employee_tab( ( id = 100 name = 'KIM' )
                                      ( id = 200 name = 'PARK' ) ).
'''

<script src="https://gist.github.com/heyhyo-dev/cf584feca24bfc4af65b16eb755af9bb.js"></script>



