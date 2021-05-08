# markdown 문서 작성법

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
