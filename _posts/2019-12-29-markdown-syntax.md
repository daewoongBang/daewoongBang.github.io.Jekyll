---
title: "markdown 문법"
categories: Blog
tags: markdown
---

기본적인 텍스트 표기 방식.  
마크다운은 줄바꿈을 인식하지 않는다.

줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번 입력한다.

강조표시를 하는 방법에는 여러가지가 있다.

1. _single asterisks_
2. _single underscores_
3. **double asterisks**
4. **double underscores**
5. ~~cancleline~~

---

**글머리**

#개수가 1개면 H1, 2개면 H2, 6개면 H6

# This is a H1

###### This is a H6

---

**단계별 인용**

> This is a first blockqute.
>
> > This is a second blockqute.
> >
> > > This is a third blockqute.

**코드 인용**

```
function test() {
    console.log('test');
}
```

---

**링크**

```
링크 표시법 : [Title](link)
```

[Google 링크](https://google.com)

---

**표 만들기**

```
| 항목 | 가격 | 개수 |
| :--- | :---: | ---: |
| 라면 | 800원 | 10개 |
| 과자 | 900원 | 20개 |
```

| 항목 | 가격  | 개수 |
| :--- | :---: | ---: |
| 라면 | 800원 | 10개 |
| 과자 | 900원 | 20개 |
