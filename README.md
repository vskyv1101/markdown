## 📎 Markdown이란? 
![image](https://user-images.githubusercontent.com/105197487/202189318-7833c9de-8259-4098-99a2-8ad5f698a406.png)<p>
마크다운(Markdown)의 창시자 John Gruber 은 마크다운을 text-to-HTML conversion tool for web writers, 즉 텍스트를 HTML로 변환해 주는 도구라고 정의하고 있다.<p>
easy-to-read (읽기 쉽고) easy-to-write (쓰기 쉬운) 간단한 문법의 텍스트 형식으로 글을 작성하면 HTML의 구조로 변환해 주기 때문에 HTML의 문법을 배우지 않은 사람들도 쉽게 사용할 수 있다.<p>
개발자라면 흔히 사용하는 Github의 README.md 도 Markdown문서이다.<p>

## HTML과의 차이? 
HTML(HyperText Markup Language) 은 Markup 언어로, Markup과 Markdown의 차이를 이해해야 한다. 마크다운(markdown)은 일반 텍스트 문서의 양식을 편집하는 문법이고, 마크업 언어(markup language)는 태그 등을 이용하여 문서나 데이터의 구조를 명기하는 언어의 한 가지이다.<p>
사용자가 문서를 작성시 구조를 직접 웹페이지가 알아들을 수 있는 문법으로 표시하느냐의 차이이다.<p>
HTML을 사용할 줄 아는 사람이면 HTML→웹에 표현이 가능하지만, 그렇지 않더라고 훨씬 단순한 Markdown 을 사용할 줄 안다면<br>
HTML→HTML로의 변환→웹에 표현 이 충분히 가능하다.<p>
## Markdown의 사용
- README 파일
- 각종 텍스트에디터
## Markdown 문법
#### 헤더
```bash
# 가장 큰 제목
## 두번째 큰 제목
### 세번째 큰 제목
#### 네번째 큰 제목
##### 다섯번째 큰 제목
###### 여섯번째 큰 제목
```
#### 목록
```bash
- 동양미래대학교
- 컴퓨터공학과
- 인공지능소프트웨어
 
1. 동양미래대학교
2. 컴퓨터공학과
3. 인공지능소프트웨어
 
* 동양미래대학교
  * 컴퓨터공학과
* 인공지능소프트웨어
```
#### 강조
1. 기울임<br>
* 혹은 _으로 감싸준다.<br>
```bash
동양미래대학교 *인공지능소프트웨어학과 22학번* 입니다.
```
2. 주석<br>
주석은 >기호를 이용하여 작성할 수 있다.<p>
3. 링크 
```bash
[Github](http://github.com/vskyv1101)
 ```
4. 이미지 삽입
 ```bash
![이미지이름](이미지 경로)
  ```
5. 표
  ```bash
| 헤더1    |  헤더 2  |   헤더 3  |
|:---|:---:|---:|
| 셀 1    | 셀 2    |   셀 3    |
| 셀 4    | 셀 5    |   셀 6    |
| 셀 7    | 셀 8    |   셀 9    |
| 셀 10   | 셀 11   |   셀 12   |
   ```
 ```bash
헤더1	 헤더 2	 헤더 3
셀 1	  셀 2	  셀 3
셀 4	  셀 5	  셀 6
셀 7	  셀 8	  셀 9
셀 10	  셀 11	  셀 12
   ```
6. 코드삽입
 ```bash
 int main(void) {
 printf("Hello, world!\n");
 return 0;
}
 ```
 ```bash
 <?
  echo("Hello, world!"); // php
?>
  ```
  ```bash
 <!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Insert Code</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
 ```
 
 
 
 
 
 
[참고] : (http://leechoong.com/posts/2017/markdown_intro/)
