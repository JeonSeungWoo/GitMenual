# GitMenual


## README.md  다루기

##HEADER
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```

# This is a H1

## This is a H2

### This is a H3

#### This is a H4

##### This is a H5

###### This is a H6


## 강조
```
커리퀸은 **아주** 맛이 있다.
```
커리퀸은 **아주** 맛이 있다.

## 기울림
```
커리퀸은 ***아주*** 맛이 있다.
```
커리퀸은 ***아주*** 맛이 있다.


## 목록
```
* 1단계
  * 2단계
    * 3단계

+ 1단계
  + 2단계
    + 3단계

- 1단계
  - 2단계
    - 3단계
```
* 1단계
  * 2단계
    * 3단계

+ 1단계
  + 2단계
    + 3단계

- 1단계
  - 2단계
    - 3단계
```
혼합해서 사용가능.
* 1단계
    - 2단계
    	+ 3단계
            = 4단계
```	
* 1단계
    - 2단계
    	+ 3단계
            = 4단계	

## 코드
### 코드를 보여줄수 있다.

```

``` java
public static void main(String[] args){
System.out.println("커리퀸 맛있다");
}
```

```bash
$ npm install test.css
```

```html
<div>
  <link rel="stylesheet" href="test.css">
</div>
```

```css
.test {
  width : 1px;
}
```

```

``` java
public static void main(String[] args){
System.out.println("커리퀸 맛있다");
}
```

```bash
$ npm install test.css
```

```html
<div>
  <link rel="stylesheet" href="test.css">
</div>
```

```css
.test {
  width : 1px;
}
```

### 테이블 만들기
```
| 컬럼1      | 컬럼 2     |
| ---------- | ---------- |
| `레코드`   | `레코드`   |
| `레코드`   | `레코드`   |
```


| 테이블            |                    |                     |                      |
| ----------------- | ------------------ | ------------------- | -------------------- |
| `레코드`          | `레코드`           | `레코드`            | `레코드`             |
| `레코드`          | `레코드`           | `레코드`            | `레코드`             |
| `레코드`          | `레코드`           | `레코드`            | `레코드`             |
| `레코드`          | `레코드`           | `레코드`            | `레코드`             |

| 컬럼1      | 컬럼 2     |
| ---------- | ---------- |
| `레코드`   | `레코드`   |
| `레코드`   | `레코드`   |


### git 태그   https://shields.io/ 사용법
# https://shields.io/ 에 들어가면 다양한 태그들을 사용
```
https://img.shields.io/badge/"laber" - "message"  -  "color"  

__ = "밑줄"  ,  -- = "대시"   ,   _ = "공백"


badge 스타일 
style=plastic ,flat , flat-square  ,for-the-badge   ,social

logo 설정(페이스북 로고 , 색상, 가로크기)
logo=facebook&logoColor=white&logoWidth=40

url로 최종을 확인 한다음 적용한다.
https://img.shields.io/badge/label-message--v0.1-blue?style=flat&logo=facebook




최종 : 
[![GitHub message](https://img.shields.io/badge/label-message--v0.1-blue?style=flat&logo=facebook)]
(https://github.com/JeonSeungWoo/GitMenual/releases)

```
[![GitHub message](https://img.shields.io/badge/label-message--v0.1-blue?style=flat&logo=facebook)](https://github.com/JeonSeungWoo/GitMenual/releases)


## Shield의 특수한 기능
### Shield에서 Github나 여러 다른 사이트와 연동하여 Build의 상태나, Code Coverage, 프로젝트의 사이즈 등등 여러가지를 자동화하여 뱃지로 보여줄 수 있다.
```
//깃헙 레포 사용 언어 수
https://img.shields.io/github/languages/count/beygee/survive 
//깃헙 레포 최다빈도 언어
https://img.shields.io/github/languages/top/beygee/survive
//깃헙 레포 코드 용량
https://img.shields.io/github/languages/code-size/beygee/survive
//깃헙 레포 용량
https://img.shields.io/github/repo-size/beygee/survive
//깃헙 레포 오픈 이슈 개수
https://img.shields.io/github/issues/beygee/survive
//깃헙 레포 닫힌 이슈 개수
https://img.shields.io/github/issues-closed/beygee/survive
//깃헙 레포 주간 커밋 수
https://img.shields.io/github/commit-activity/w/beygee/survive
//깃헙 레포 라스트 커밋 날짜
https://img.shields.io/github/last-commit/beygee/survive
```
[https://img.shields.io/github/languages/count/beygee/survive]

[https://img.shields.io/github/languages/top/beygee/survive]

[https://img.shields.io/github/languages/code-size/beygee/survive]

[https://img.shields.io/github/repo-size/beygee/survive]

[https://img.shields.io/github/issues/beygee/survive]

[https://img.shields.io/github/issues-closed/beygee/survive]

[https://img.shields.io/github/commit-activity/w/beygee/survive]

[https://img.shields.io/github/last-commit/beygee/survive]


### note 사용법
```
> _**Note**: 나는 `커리퀸을` 좋아`한다`.
```

> _**Note**: 나는 `커리퀸을` 좋아`한다`.


### link 사용법 

## text
```
1.text : [`BHC` 커리퀸](https://www.bhc.co.kr/menu/chicken.asp?menuCate=B0201008)

2.url : (https://www.bhc.co.kr/menu/chicken.asp?menuCate=B0201008)
```

[`BHC` 커리퀸](https://www.bhc.co.kr/menu/chicken.asp?menuCate=B0201008)

## url
(https://www.bhc.co.kr/menu/chicken.asp?menuCate=B0201008)




## img
```
<img src="/img/1.jpg" width="40%" height="30%" title="catsize" alt="cat"></img>
```
<img src="/img/1.jpg" width="40%" height="30%" title="catsize" alt="cat"></img>

README.md...
