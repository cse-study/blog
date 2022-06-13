+++

+++

<!--more-->

> 스터디에 도움이되는 자료들을 모아둡니다. 좋은 자료가 있다면 아래에 계속 추가해주세요 🙌

- [DAILY PAPERS](https://papers.labml.ai/papers/daily/): 최신 인기있는 AI 논문을 찾아주는 웹 사이트입니다.
- [YannicKilcher youtube](https://www.youtube.com/c/YannicKilcher/videos): 최신 AI 기술을 요약하여 설명해주는 유튜브 채널입니다.
- [Reddit, ML 카테고리](https://www.reddit.com/r/MachineLearning/): AI 관련 소식을 공유하는 커뮤니티입니다.
- [Papers with Code, 뉴스레터](https://paperswithcode.com/newsletter): 최신 인기있는 AI 자료들을 공유해주는 뉴스레터입니다.
- AI 블로그: [OpenAI Blog](https://openai.com/blog/), [Meta Research Blog](https://research.facebook.com/blog/), [Google AI Blog](https://ai.googleblog.com)

### How to post

![img](/assets/img/notice1.png)

```sh
+++
title = "제목을 입력하세요."
date = "2022-01-01"
[profile]
	enable = true
	avatar = "/assets/img/profile.jpg"
	name = "홍길동"
	email = "hong-gildong@gmail.com"
+++

포스팅의 미리보기 입니다.
<!--more-->

<mark>본문입니다.</mark>
![img](/assets/img/posting_image.png)
```

- 마크다운 파일의 제목은 `작성날짜-제목.md`의 형태로 설정해주시면 좋습니다. 
- 각 스터디의 github repository에 마크다운 파일을 push하여 블로그에 포스팅을 업로드 할 수 있습니다. 
- **(Notice)** 자동화가 아직 적용되지 않았습니다. 배포까지의 자세한 과정은 관리자에게 문의해주세요!

### Image upload

프로필 이미지 사용 방법은 다음과 같습니다.

1. `static/assets/img/` 디렉토리에 프로필 이미지를 업로드 합니다.
2. 포스팅 정보 입력란의 avartar 항목에 `/assets/img/이미지이름` 을 기입합니다.

게시글 이미지 업로드 방법도 동일합니다. 'How to post' 마크다운 예시의 제일 마지막 줄을 참고하시면 좋습니다.

1. `static/assets/img/` 디렉토리에 이미지를 업로드 합니다.
2. 마크다운의 이미지 경로에 `/assets/img/이미지이름` 을 기입합니다.

