# markdown 문서 작성법(Bug Fixed)

## 1. Heading

> 문서 제목이나 글머리를 만들때 사용한다.  
> 글자 크기는 1 ~ 6개의 #을 사용하여 지정한다.  

    # Heading1
    ## Heading2
    ### Heading3
    #### Heading4
    ##### Heading5
    ###### Heading6

# Heading1
## Heading2
### Heading3
#### Heading4
##### Heading5
###### Heading6
<br>

>h1과 h2는 다음과 같은 방법으로도 표현할 수 있다.

    Heading1
    ===
    Heading2
    ---

Heading1
===
Heading2
---

<br>
<br>

***

## 2. Paragraph

> 문단을 구분할 때 Enter 2번으로 구분한다.

    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    
    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<br>
<br>

***

## 3. Line Break

> 줄 바꿈을 넣기 위해서는 문장 끝에 스페이스 2번을 넣거나 \<br>태그를 사용한다.

    Lorem ipsum dolor sit amet, consectetur adipisicing elit,  //스페이스 두번
    sed do eiusmod tempor incididunt<br>
    ut labore et dolore magna aliqua.

Lorem ipsum dolor sit amet, consectetur adipisicing elit,  
sed do eiusmod tempor incididunt<br>
ut labore et dolore magna aliqua.

<br>
<br>

***

## 4. Emphasis

> 텍스트 강조에는 볼드와 이탤릭이 있다.

- Bold : 볼드를 넣고 싶은 텍스트를 **로 감싼다.
- Italic : 기울임을 넣고 싶은 텍스트를 *로 감싼다.
- Bold & Italic : 둘다 넣고 싶을 경우 ***로 감싼다.  

***

    This is **BOLD**.  
    This is *ITALIC*.  
    This is ***BOLD & ITALIC***.

This is **BOLD**.  
This is *ITALIC*.  
This is ***BOLD & ITALIC***.

<br>
<br>

***

## 5. Blockquotes

> 텍스트를 인용하거나 특수한 강조를 넣고 싶을 때 사용한다.  
> 인용구에 인용구를 중첩할 수 있다.

    > Hello
    >> My name is
    >>> Yeong Jin Cho

> Hello
>> My name is
>>> Yeong Jin Cho

<br>
<br>

***

## 6. List

> 리스트에는 번호가 있는 리스트와 없는 리스트가 있다.  
> Ordered list는 (숫자.)으로 구분, Unordered list는 (*, + , -)로 구분한다.

    1. Ordered List
        1. A
            1. a
            3. b        // 숫자를 잘못 적어도 자동으로 바뀜
        2. B
    2. Unordered List   // *, +, -를 섞어 사용해도 상관없음.
        - C
            - c
            - d
        * D
        + E

1. Ordered List
    1. A
        1. a
        3. b
    2. B
2. Unordered List
    + C
        - c
        - d
    - D
    * E

<br>
<br>

***

## 7. Code

> 코드를 삽입하고 싶을때 사용한다.

- 인라인 코드 : 짧은 코드를 사용하고 싶을때 \`으로 감싼다.
- 코드 블럭 : 여러줄의 코드를 사용하고 싶을때 코드인 부분 앞쪽에 공백 4개나 tab을 넣어준다.

***

    If you want to use `printf()` you should write `#include <stdio.h>` on top

        #include <stdio.h>  //공백 4칸 or tab
        int main(){
            printf("Hello World\n");
            return 0;
        }

If you want to use `printf()` you should write `#include <stdio.h>` on top

    #include <stdio.h>
    int main(){
        printf("Hello World\n");
        return 0;
    }

<br>
<br>

***

## 8. Horizontal Rules

> 가로줄을 만들고 싶을때 (***, ---, ___)를 사용한다.

    a

    --- //가로줄 앞뒤는 비워두는 것이 좋다. (h2로 인식될 수 있음)
    
    b

a

---

b

<br>
<br>

***

## 9. Links

> URL이나 e-mail을 삽입할 때 사용한다.  
> \[대체텍스트](주소) 또는 <주소> 형식으로 사용한다.

    Life is short, You need [Python](https://www.python.org/)  
    <https://google.com>  
    My e-mail is <choyj2012@gmail.com>

Life is short, You need [Python](https://www.python.org/)  
<https://google.com>  
My e-mail is <choyj2012@gmail.com>

<br>
<br>

***

## 10. Images

> 이미지를 삽입할 때 사용한다.  
> !\[이름](이미지URL "설명") 형식으로 사용한다.
>
> - 이름 : 이미지 로딩에 실패시 나오는 텍스트
> - 설명 : 마우스를 이미지에 올렸을 때 나오는 텍스트

    ![Markdown Icon](markdown.png)
    [![Markdown Icon](markdown.png)](https://www.markdownguide.org/ "Markdown Guide") //이미지 하이퍼링크
    ![](markdown.png) //이름과 설명은 생략가능

![Markdown Icon](markdown.png)
[![Markdown Icon](markdown.png)](https://www.markdownguide.org/ "Markdown Guide")
![](markdown.png)

<br>
<br>

***

## 11. Escapeing Characters

> 마크다운 문법에 사용되는 특수문자들을 텍스트로 사용하려면 \를 앞에 사용해야 한다.  
> \\ , \* , \` , \_ , \[ , \] 등등

    I want use *^*  //Italic으로 적용
    I want use \*^\*

I want use *AAA*  
I want use \*AAA\*

<br>
<br>

***

## 12. HTML

> 많은 마크다운 프로그램은 HTML 태그를 지원한다.  
> 단, HTML태그 안쪽에 마크다운 문법을 사용할 수 없다.

<br>
<br>

***

## [github repository](https://github.com/choyj2012/GFM_Test)
