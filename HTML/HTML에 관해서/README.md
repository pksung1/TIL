# HTML에 관해서

Created: February 3, 2022 12:52 AM
작성상태: 작성 중
주제: HTML
카테고리: FrontEnd

## HTML이란?

HTML은 Hyper Text Markup Language로 웹페이지를 위한 **마크업 언어**이다.

## 마크업 언어?

태그 등을 이용하여 문서나 데이터의 구조를 명기하는 언어의 한 가지이다.

## HTML 전송

### HTTP (HyperText Transfer Protocol)

W3상에서 정보를 주고받을수 있는 프로토콜. 주로 HTML을 보낸다.

보통 TCP와 80포트를 사용하고, HTTP/3 부터는 UDP를 사용한다

### HTML 전자우편

메일에 HTML을 보낼수있다.

## HTML 과 XML의 차이

| HTML (Hyper Text Markup Language) | XML (Extensible Markup Language) |
| --- | --- |
| 데이터를 보여주기 위해 만들어짐 | 데이터를 전송하기위해 만들어짐 |
| 대소문자를 구분하지 않음 | 대소문자 구분 |
| 형식 기반 | 컨텐츠 기반 |
| 닫는태그가 필수적이지 않음 ex) <br> | 닫는 태그가 필수적임 |
| 네임스페이스 X | 네임스페이스 O |

## HTML DOM Tree

HTML을 사용하는 클라이언트는 마크업을 파싱하여 [DOM(Document Object Model)](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)트리로 변환합니다.

DOM Tree란 메모리 안에서 표현되는 document입니다.

DOM Tree는 여러가지 Node로 구성되어 있습니다.

- Document Type node
- Element nodes : 요소 노드(태그)
- Text nodes : 텍스트 노드
- Comment nodes : 주석노드
- ProcessingInstruction nodes :  XML에 있음

---

참고

[https://techterms.com/definition/markup_language](https://techterms.com/definition/markup_language)

[https://www.guru99.com/xml-vs-html-difference.html](https://www.guru99.com/xml-vs-html-difference.html)

[https://developer.mozilla.org/en-US/docs/Web/API](https://developer.mozilla.org/en-US/docs/Web/API)