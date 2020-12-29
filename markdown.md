# 마크다운 문법

## 제목(heading)

제목은 `#`을 통해 표현한다. 제목의 레벨은 h1~h6까지 표현 가능하다.

### 제목3

#### 제목4

##### 제목5

###### 제목6

## 목록

1. 순서가 있는 목록 엔터
2. 순서가 있는 목록
   1. tab을 누르면 하위 레벨에서 작성
   2. 하위 레벨
3. shift+tab을 누르면 상위 레벨로 올라옴

* 순서가 없는 목록
* 순서가 없는 목록
  * tab을 누르면 하위레벨에서 작성
  * 하위레벨
* shift+tab을 누르면 상위 레벨로 올라옴

## 코드블록

```python
print('hi')
# 파이썬 주석
```

```html
<!-- HTML 주석 -->
print('hi')
<h1>
    hi
</h1>
```

## 링크

[구글!](https://google.com)

주석으로 작성하고 싶다면, 아래 처럼

구글[^1]

[^1]: https://google.com

## 표

| 순번 | 이름   | 비고 |
| ---- | ------ | ---- |
| 1    | 홍길동 |      |
| 2    | 김철수 |      |
| 3    |        |      |

## 그림

![Jean-Michel-Basquiat-Skull-Broad-Collection-LA](C:\Users\inter\Desktop\바탕화면\그림\Jean-Michel-Basquiat-Skull-Broad-Collection-LA.jpg)

* typora 설정을 통해 상대 경로로 이미지를 관리해야 Github 통해서 깨지지 않고 활용 가능하다.

 ![Jean-Michel-Basquiat-Skull-Broad-Collection-LA](md-images/Jean-Michel-Basquiat-Skull-Broad-Collection-LA.jpg)

## 기타

*기울임(이탤릭)*

**굵게(볼드)**

~~취소선~~

수평선

---



> 인용문