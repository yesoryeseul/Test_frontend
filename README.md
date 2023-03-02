[![Github Badge](https://img.shields.io/badge/-Github-24292F?style=flat-square&logo=Github&logoColor=white&link=https://github.com/yesoryeseul/)](https://github.com/hidongmin37) <a href="https://blog.naver.com/jangdm37"><img src="https://img.shields.io/badge/Naver-03C75A?style=flat-square&logo=Naver&logoColor=white"/></a>[![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jjuhee0913@gmail.com)](mailto:jangdm37@gmail.com)[![Instagram Badge](https://img.shields.io/badge/-Instagram-dd2a7b?style=flat-square&logo=instagram&logoColor=white&link=https://www.instagram.com/zuzu_zzing/)](https://www.instagram.com/hi_dongmin__37/)
<a href="https://velog.io/@jangdm37"><img src="https://img.shields.io/badge/Velog-3DDC84?style=flat-square&logo=Blogger&logoColor=white"/></a>
181717
24292F
# Test_frontend
프론트엔드 테스트용 레퍼지토리입니다


큰제목: 문서 제목
=============

작은제목: 문서 부제목
-------------

# h1
## h2
### h3
#### h4
##### h5
###### h6

- - - 

> first BlockQuote
> > second BlockQuote
> > > third BlockQuote

---------------------------------------

### 순서있는 목록(번호)
##### - 어떤 번호를 입력해도 내림차순 정의
1. first
2. second
3. third

4. 네번째
6. 여섯번째
5. 다섯번째

* * *

### 순서없는 목록(글머리 기호: *, +, - 지원)
* red
  * blue
    * red

*****

### 들여쓰기
들여쓰기 적용해보자.
 들여쓰기 적용해보자.
아마 안될 것이다 ㅋ

들여쓰기 적용해보자.
######
　들여쓰기 적용해보자.

---------------------------
### 코드 블럭

#####  ```<pre><code>{code}</code></pre>``` 이용

<pre>
<code>
 public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }

}
</code>
</pre>

##### 블럭코드("\```") 을 이용

```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

##### 깃헙에서는 코드블럭코드("\```") 시작점에 사용하는 언어를 선언하여 문법강조(Syntax highlighting)이 가능

```javascript
 var yeseul = {
  body: {
    height: 167.6,
    weight: 49.5
  }
};
```

***

### 수평선 ```<hr/>```
```
 * * *

 ***

 *****

 - - -

 ---------------------------------------
```

- - -

### 링크
+ 참조링크
```
 [link keyword][id]

 [id]: URL "Optional Title here"

 // code
 Link: [Google][googlelink]

 [googlelink]: https://google.com "Go google"
```

Link: [김예슬의 깃허브][yeseul_github]

[yeseul_github]: https://github.com/yesoryeseul

- 외부링크
```
사용문법: [Title](link)
적용예: [Google](https://google.com, "google link")
```

###### [김예슬의 깃허브](https://github.com/yesoryeseul)

* 자동연결
```
 일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성한다.

 * 외부링크: <http://example.com/>
 * 이메일링크: <address@example.com>
```

* 외부링크: <https://www.naver.com/>
* 이메일링크: <yesoryeseul07@gmail.com>

- - -

### 강조
```
 *single asterisks*
 _single underscores_
 **double asterisks**
 __double underscores__
 ~~cancelline~~
```

* *single asterisks*
* _single underscores_
* **double asterisks**
* __double underscores__
* ~~cancelline~~

-----

### 이미지
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0)
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0 "RubberDuck")

사이즈 조절 기능은 없기 때문에 ```<img width="" height=""></img>```를 이용한다.

예)
```
<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="/path/to/img.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
```

<img src="http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="Rubberduck"></img><br/>
<img src="http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0" width="40%" height="30%" title="%(비율) 크기 설정" alt="Rubberduck"></img>


-----

### 중바꿈
3칸 이상 띄어쓰기(` `)를 하면 줄이 바뀐다.

```
* 줄바꿈을 하기 위해서는 문장 마지막에서 3칸이상 띄어쓰기해야 한다.
이렇게

* 줄바꿈을 하기 위해서는 문장 마지막에서 3칸이상 띄어쓰기해야 한다.___\\ 띄어쓰기
이렇게
```

* 줄바꿈을 하기 위해서는 문장 마지막에서 3칸이상 띄어쓰기해야 한다. 이렇게

* 줄바꿈을 하기 위해서는 문장 마지막에서 3칸이상 띄어쓰기해야 한다.   \
이렇게
