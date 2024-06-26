# 마크다운 사용법

## 제목
'#' 을 앞에 달면 제목이 된다. 6번째 제목까지 허용  

## 강조
별 기호 혹은 언더바 한번 사용은 *기울임체*  
두번 사용은 __강조체__  
물결 기호는 ~~취소선을~~ 의미한다.

## 목록
대시는 순서가 없는 목록으로, 숫자는 순서가 있는 목록으로 구분된다.  

1. 순서가 있는 항목
  1. 순서가 있는 항목
  2. 순서가 있는 항목

- 순서가 없는 항목
  - 순서가 없는 항목

## 링크
[이름](링크 "설명")  
[Github](https://github.com/limEnough "나의 깃헙")  

## 블록
백틱을 3번 이상 입력하고, 언어(코드)이름을 명시해, 코드 '블록(Block)'을 표현한다.  
코드블록의 시작 백틱 갯수와 종료 백틱 갯수는 같아야 한다.  

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

## 수평선
대시 혹은 언더바 혹은 별 기호를 3개 이상 입력한다.  
---
___
***

## 줄바꿈
문장 마지막에서 <br>태그를 직접 입력하거나, 문장 마지막에서 띄어쓰기를 2번 이상한다.  

## 주석
html에서 사용하는 주석으로 표현한다.  
<!-- 주석 -->

## 인용문 작성
> 인용문은 이렇게 작성한다.  
> (인용문 내용)
이것은 어떻게 나올까?