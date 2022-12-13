# yarn 이란?

```
Yarn is a package manager that doubles down as project manager.
Whether you work on one-shot projects or large monorepos,
as a hobbyist or an enterprise user, we've got you covered.
```

위 설명은 [yarn](https://yarnpkg.com/) 홈페이지에 접속 시 제일 먼저 볼 수 있는,<br/>
yarn 에 대한 설명이다.<br/>
해석하자면 아래와 같다,<br/>

```
Yarn은 프로젝트 관리자의 역할도 겸하는 패키지 관리자입니다.
일회성 프로젝트 또는 대규모 단일 리포지토리 작업,
취미로 하는 사람 또는 엔터프라이즈 사용자에게 모두 도움이 되어줍니다!
```

# yarn 을 사용하는 이유

필자는 지금까지 yarn 을 사용해본 적이 없다. <br/>
yarn 이 필요한 프로젝트를 딱히 해본적이 없기 때문이다. <br/>
하지만 최근, 여러 라이브러리들의 존재를 알게 되고, <br/>
유용한 라이브러리들을 내가 하고자 하는 프로젝트를 진행하면서 하나씩 추가하다가 보니, 문제가 생겼다.<br/>
<br/>
각 라이브러리는 해당 라이브러리에 맞는 노드 버전이 존재한다. <br/>
모든 라이브러리들이 사용하는 노드 버전이 같다면 정말 좋겠지만, <br/>
안타깝게도 현실은 그렇지 못하다. <br/>
때문에, 개발을 하면 할수록 점점 버전 충돌에 의한 에러를 많이 보게 될 것이다. <br/>
하지만 yarn 을 이용한다면 그에 대한 걱정은 잠시 내려둘 수 있다.

```
Yarn guarantees that an install that works now will
continue to work the same way in the future
```

위는 yarn 공식 홈페이지에 있는 yarn에 대한 설명 중 하나이다. <br/>
해석하자면, yarn 은 지금 동작하는 작업들을 이후에도 계속 동작하도록 보장해 준다는 뜻이다. <br/>
쉽게 말해, 버전 충돌을 없애준다는 것이다. <br/>

# yarn 사용법

## 1. 디렉토리 생성

```bash
$ mkdir yarn
```

원하는 위치에 디렉토리를 생성한다.

## 2. npm 설정

```bash
$ cd yarn
$ npm init
```

생성한 디렉토리에 접근 이후, 명령어를 통해 package.json 을 생성해준다.

## 3. yarn 설정

```bash
$ yarn
```

명령어를 통해 yarn.lock 을 생성해준다.
