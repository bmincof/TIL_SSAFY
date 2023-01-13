# Markdown 문법

## Heading

> h1 : `#`
>
> h2 : `##` 
>
> h3 : `###` 
>
> h4 : `####` 
>
> h5 : `#####`
>
> h6 : `######`

`<h1>내용</h1>`

`ctrl` + `숫자` 로도 만들 수 있음

## List

### Unordered List

> - : `*` /`-` 
> - a
>   - b
>     - c
>       - d
>         - e
>           - ...

`<ul></ul>`

### Ordered List

> 1. : `숫자` +`.`
>    1. 리스트 1의 1
> 2. 리스트 2
>    1. 리스트 2의 1
>    2. 리스트 2의 2

`<ol></ol>`

## Text Style

### Bold

> **내용** : `**내용**` /`ctrl` + `b` 

### Italic

> *내용* : `*내용*` / `ctrl` + `i`

ex) ***안녕하세요*** : `***내용***`

## Hyperlink

### Link

[구글](https://www.google.com) : `[텍스트](링크 주소)` - `ctrl` + `click` 으로 이동

### Img

![...](C:\Users\SSAFY\Desktop\TIL\assets\images.jpeg)

: `![대체 텍스트](이미지 주소)`

이미지 크기 변경 불가능

## Code Block

### Inline Code Block

글1, 글2, 글3, `코드1`

: 빽킷(`)을 활용해서 인라인 코드 작성 가능

들여쓰기 표시 x

### Code Block

```java
/* 블럭 주석 */
class Sample{  
    public static void main(String args[]){  
    	System.out.println("Hello Java");	// 라인 주석  
    }  
}  
```

: 빽킷 3번 입력 후 코드 작성

들여쓰기 표시 가능

## Table

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |

:`| | | |` 로 3열 테이블 만들 수 있음