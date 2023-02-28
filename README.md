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

*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
