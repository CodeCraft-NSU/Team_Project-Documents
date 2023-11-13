Markdown Syntax 정리
=============

> Github에서는 Issues나 PR등 사용자가 글을 작성할 수 있는 페이지에선 Markdown 문법을 사용할 수 있다. (이 문서 또한 Markdown으로 작성됨.)

- 문법 소개에 들어가기 앞서, 작성중인 내용을 코드가 아닌 실제 모습대로 보고 싶다면 Write 탭을 Preview로 바꿔서 보면 된다.

![image](https://github.com/kimch0612/OOP2_Project/assets/10193967/7aef862c-498b-4b4f-bdc2-d2c41bdcafb5)

---

- 문서의 제목

```
Example Title
=============
```

Example Title
=============

- 문서의 부제목 (소제목)

```
# Size1
## Size2
### Size3
#### Size4
##### Size5
```

# Size1
## Size2
### Size3
#### Size4
##### Size5

---

- 순서를 매겨 목차 등을 구성하기

```
1. Test1
2. Test2
3. Test3
```

1. Test1
2. Test2
3. Test3
 
---

- 일반 문단

```
- Example Text
  - 들여쓰기도 가능하다.
```

- Example Text
  - 들여쓰기도 가능하다.

---

- 글 강조

```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

~~cancelline~~

---

- 코드 블럭

```
자신이 작성하고자 하는 코드를 ``` ``` 로 감싼다.
만약 특정 언어로 된 코드를 작성하는 경우, 처음 ``` 옆에 프로그래밍 언어를 작성한다.
ex. ```C++ cout << Hello World! << endl;```
```

```C++
cout << "Hello World!" << endl;
```

---

- 표 작성 방법

```
| Type | Content |
|:---|:---|
| Type1 | Content1 |
| Type2 | Content2 |
| Type3 | Content3 |

| Type | Name | Purpose |
|:---|:---|:---|
| - | - | - |
| - | - | - |
| - | - | - |
| - | - | - |
```

| Type | Content |
|:---|:---|
| Type1 | Content1 |
| Type2 | Content2 |
| Type3 | Content3 |

| A | B | C |
|:---|:---|:---|
| - | - | - |
| - | - | - |
| - | - | - |
| - | - | - |

---

- 하이퍼링크

```
[표시할 내용](연결할 웹페이지)
ex. [Naver Web](www.naver.com)
```

[Naver Web](www.naver.com)

```
아래와 같이 같은 Repository 내에 있는 문서로 이동시킬 수도 있다.
[README.md](README.md) / [Issue Template](./.github/ISSUE_TEMPLATE.md)
```

[README.md](README.md) / [Issue Template](./.github/ISSUE_TEMPLATE.md)

---

- 수평선

```
---
```

---

---

- 이미지 첨부

```
이미지가 클립보드에 있는 상태에서 Ctrl V 또는 드롭다운
그럼 아래와 같은 이미지 URL이 삽입될 것임
![image](https://github.com/kimch0612/OOP2_Project/assets/10193967/6815a768-7bd7-461f-be7d-c468c7b2b133)
```

![image](https://github.com/kimch0612/OOP2_Project/assets/10193967/6815a768-7bd7-461f-be7d-c468c7b2b133)

---