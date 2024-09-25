# markdown 이란?
 - 텍스트를 서식 잇는 문서로 쉽게 변환할 수 있는 마크업 언어.
 - HTML으로 변환하기 쉽게 설계되어있다.

# 마크업 언어란?
 - 텍스트에 태그를 사용하여 문서의 구조와 서식을 정의하는 언어.
 - 문서를 체계적으로 작성하고 읽을 수 있도록 함.(HTML, XML ...)

1. **헤더(Headers)** :
```
  백틱(`) <-- 3개 코드라인 markdown 문법이 적용 안되는 영역
  # 헤더1
  ## 헤더2
  ### 헤더3
```

## 헤더2

2. 굵게

```
  **굵게**
```
**굵게**

3. 기울임

```
  *기울임*
```
*기울임*

4. 목록
#### 순서가 있는
```
 1.첫 번째
 2.두 번째
```
 1. 첫 번째
 2. 두 번째
#### 순서가 없는
```
 - 1
 - 2
```
 - 1
 - 2

5. 링크
```
  [링크 텍스트](https://www.naver.com)
```
[네이버로 가기](https://www.naver.com)

6. 이미지
```
 ![이미지 설명](https://~)
```
 ![영화포스터](https://i.namu.wiki/i/c9gdR0HcjS2l9C_u9jD2SfTQ1tyvMAsNpg6lK3A-f8C-Hsx5cKQHf98MtWc-07NEuoPnMBYPB4xRhJ27R1tvPv81C4lnVjcdRYGOz9aEXsSNu4lqkC9gLhjwAAuwZoAyQ2EAVLzglfAOG8ce0x5NSg.webp)

7. 인용구

```
  > 이것은 인용구 입니다.
  >> 중첩된 인용구 입니다.
```
> 이것은 인용구 입니다.
  >> 중첩된 인용구 입니다.

8. 특정언어의 코드 블록

```python
  print('hi')
```
9. 구분선

```---```

---

10. 체크박스

``` - [] 할일 - [x] 완료한 일 ```

- [ ] 할일 
- [x] 완료한 일

11. 테이블

| 제목1 | 제목2 |
|-------|-------|
| 내용1 | 내용2 |

12. 이모지 추가하기

[이모지 검색](https://emojipedia.org)

- 오늘 날씨는?🌞
- 오늘 저녁에 🍺!? or 💻

13. 배지 추가

[배지 추가](https://simpleicons.org)

[배지 추가2](https://shields.io/)

<img src="https://img.shields.io/badge/gitbut-black?style=for-the-badge&logo=gitgit&logoColor=white">