+++
title = '240703 Write Blog'
date = 2024-07-03T17:14:25+09:00
draft = false
author = "Honux"
+++


안녕하세요? 코드스쿼드 호눅스입니다.

두 번째 블로그에서는 Hugo로 세팅한 이 사이트에 글을 쓰는 방법을 적어 보려고 합니다.

먼저 hugo를 설치합니다.

```sh
brew install hugo
````

다음으로 저장소를 클론하고 저장소 안으로 이동합니다.

```sh
git clone https://github.com/woowa-techcamp-2024/woowa-techcamp-2024.github.io
cd woowa-techcamp-2024.github.io
```

새로운 포스팅을 생성합니다.

```sh
hugo new post/240703-write-blog.md
```

에디터로 글을 적당히 편집합니다.

**주의할 점이 하나 있는데 draft = true 로 수정해야 출판이 됩니다.**

글이 잘 써졌나 로컬에서 확인합니다.

```
hugo server -D
```

이제 깃헙에 올릴 정적 페이지를 생성합니다.

```sh
hugo
```

마지막으로 커밋을 하고 main 브랜치로 PR을 올리면 끝!
