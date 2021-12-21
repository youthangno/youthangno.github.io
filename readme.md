안녕하세요 반갑습니다. youthangno의 블로그 입니다.
Jekyll theme인 minimal-mistakes를 사용합니다. (https://github.com/mmistakes/minimal-mistakes)

사용법에 대한 설명을 저도 보고, 다른 분들도 보시라고 적어놓습니다.
변경사항이 있거나, 추가되는것이 있다면, 차례대로 기록해 두겠습니다.

```javascript
//파일경로
_post / file.md;


---
layout: single; //포스트를 클릭했을때, 이 페이지만 뜨게 하겠다.
title: "your title"; //포스트 제목
categories: categoryName; //카테고리이름
tag: tagName; //태그 명
toc: true; //오른쪽에 포스트별로 목차 사이드 바를 띄우겠다.
toc_sticky: true  // 오른쪽 목차 사이드 바가 마우스 스크롤과 함께 붙어 내려갈 것인지 설정
author_profile: false; //포스트를 볼때, 왼쪽 사이드바 프로필을 없애겠다.
search: false; //해당 포스트를 찾지 못하게 하겠다. 지우면 검색가능.
---


```

```
폰트변경
_sass/minimal-mistakes.scss

=> _variables.scss => /* system typefaces */
밑에 폰트 추가.

```

포스트에 글에 색깔 넣기

```
<span style="color:yellow">노란 글씨입니다.</span>
```

```
powershell 깃허브 폴더 안으로 들어가서

$ bundle exec jekyll serve

라고 쳐 준뒤, 로컬 주소 복사!
그리고 수정 후 F5로 리프레시 해주면 실시간 변경을 볼 수 있다.

```
