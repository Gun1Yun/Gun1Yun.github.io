---
title: Markdown 사용법
author:
  name: Geonil Yun
  link: https://github.com/Gun1Yun
date: 2021-01-03 18:32:00 -0500
categories: [Blogging, Tutorial]
tags: [markdown, md]
---

# 1. markdown 이란
markdown은 텍스트 기반의 **마크업 언어(markup language)** 이다. 
>ddd

# 2. 마크다운 문법
## 2.1 헤더 (Headers)
- 글머리(Headers)는 **1 ~ 6** 까지 지원한다.  
      
  ```
  # This is a H1
  ## This is a H2
  ### This is a H3
  #### This is a H4
  ##### This is a H5
  ###### THis is a H 6
  ####### This is not working
  ```
  > 사용
  # This is a H1
  ## This is a H2
  ### This is a H3
  #### This is a H4
  ##### This is a H5
  ###### THis is a H 6
  ####### This is not working

## 2.2 줄바꿈 및 강조 표시
 - 줄바꿈 : markdown은 일반적인 줄바꿈은 인식하지 않는다. 문장의 끝에 스페이스(space) 두개 이상(`  `)을 사용하여 줄바꿈을 표현한다.
    
    ```
    일반적인 줄 바꿈(Enter)을 사용한
    경우 입니다.  

    markup 문법의 줄 바꿈(space 두개)을 사용한  
    경우 입니다.
    ```
    > **사용**  
    일반적인 줄 바꿈(Enter)을 사용한
    경우 입니다.  

    markup 문법의 줄 바꿈(space 두개)을 사용한  
    경우 입니다.

- 강조 표시 : 강조는 asterisks(`*`), underscores(`_`), tilde(`~`)를 사용해 표현한다.
  ```
  *single asterisks*  
  _single underscores_  
  **double asterisks**  
  __double underscores__  
  ~~cancelline~~
  ```
  > 사용

  *single asterisks*  
  _single underscores_  
  **double asterisks**  
  __double underscores__  
  ~~cancelline~~

## 2.3 인용 (Quote)
- `>`문자를 이용해 **Quote** 를 표현한다.  
  ```
  > This is a first blockquote
  >> This is a second blockquote
  >>> This is a third blockquote
  ```
  > This is a first blockquote
  >> This is a second blockquote
  >>> This is a third blockquote

## 2.4 목록 (Lists)
- 순서 있는 목록(정렬 목록 : Ordered list)는 숫자 기호(`0~9`)를 이용해 표현한다. 숫자 순서가 맞지 않아도 자동으로 정렬된다.  
  
  ```
  1. First  
     1. First in First  
     2. First in Second  
  2. Second  
  3. Third  
  4. Fourth  
  5. Fifth  
  ```
  1. First  
     2. First in First  
     3. First in Second  
  1. Second  
  2. Third  
  3. Fourth  
  4. Fifth  


<details>
<summary>상세 내용 확인</summary>
<div markdown="1">
ggg


</div>
</details>