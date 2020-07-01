# TISTORY_JB_SKIN_167_with_TOC
Adjusting Table Of Contents to TISTORY BLOG skinned with JB SKIN 167

## 개요
[JB FACTORY](https://www.jbfactory.net/) 에서 제공하는 skin(`JB SKIN 167`) 을적용한 [tistory.com](tistory.com) 블로그에 Table Of Content 를 적용하는 방법에 대해 소개합니다.

## 참조
tistory 에 Table Of Content 를 적용하는 방법은 다음 글을 참고하였습니다.

- [Tistory TOC(Table Of Contents) 구현기](https://www.wbluke.com/21)
- [wbluke/tistory-table-of-contents github repository](https://github.com/wbluke/tistory-table-of-contents)

## 적용방법
대체적으로 참조에 링크된 [tistory-table-of-contents](https://github.com/wbluke/tistory-table-of-contents)와 동일합니다.
파일업로드와 HTML 수정 부분만 아래 소개된 방법대로 진행합니다.

### toc.js & toc.css 파일 업로드

`toc.js` 파일 및 `toc.css` 파일은 본 Repository 에서 다운로드받은 뒤 Tistory 스킨편집에서 업로드해야합니다.

### tistory 스킨편집 - HTML 수정
HTML 수정에서 다음 코드에 해당하는 부분을 찾아 `Custom for TOC - coldMater` 부분으로 감싸진 부분을 추가합니다.
```html
	<div class="jb-background jb-background-main-top">
		<!--Custom for TOC - coldMater START-->
		<div id="toc-elements"></div>
		<!--Custom for TOC - coldMater END-->
		<div class="jb-container jb-container-main-top">
			<div class="jb-row jb-row-main-top">
        
      <!-- 이하 코드 생략-->
```
