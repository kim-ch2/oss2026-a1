# A1 리포트

- 이름: 김창현 
- 학번: 2022202019
- GitHub ID: kim-ch2

## 어디를 둘러봤는지

열어본 awesome-nodejs 카테고리, 터미널에서 써본 검색어, 링크를 따라간 경로 등을 적습니다.
https://www.npmjs.com/package/supports-color
https://www.npmjs.com/package/cli-boxes
https://www.npmjs.com/package/string-width
---

## 선정한 패키지

### 1. `<supports-color>`
**선정 이유:**
터미널이 색상을 지원한다는 것이 궁금해서 선정하였다.
**이것으로 무엇을 할 수 있을지:**
터미널 색상을 지원하면 디렉토리나 실행 파일 등에 컬러를 갖게하여 출력하게 할 수 있을것이다.
**확인 결과:**
$ npm view supports-color version time.modified license dependencies
$ npm view supports-color deprecated
확인 결과, 최근인 2026년 7월에 마지막으로 수정되었고 MIT 라이선스가 명시되어있다. 또한
deprecated 출력 결과가 없는 것으로 보아 지원이 중단되지 않고 잘 관리되고 있는 패키지이다. 의존성 또한 출력되지 않았다.
```
**출력을 보고 알게 된 것:**
비교적 최근까지 수정되어 관리하고 있다는 것이 인상적이었다.
---

### 2. `<cli-boxes>`
**선정 이유:**
텍스트만있는 콘솔 창에 사각형 테두리를 그릴 수 있다는것이 신기하여 선정하였다.
**이것으로 무엇을 할 수 있을지:**
네트워크 서버에서 서버의 포트번호, 주소 등을 사각형 테두리 안에 감싸서 출력하면 가독성이 좋을 것 같다.
**확인 결과:**
$ npm view cli-boxes version time.modified license dependencies
$ npm view cli-boxes deprecated
```
마지막 수정일은 2024년 8월이고 MIT 라이선스이다. deprecated 명령에는 아무것도 출력되지 않았다. 의존성 항목 또한 출력되지 않았다.
```
**출력을 보고 알게 된 것:**
마지막 수정일이 2024년 8월로 약 2년 전이지만 deprecated 출력이 없는 것으로 보아 방치된 것이 아니라 이미 기능이 완성되어 더 이상 수정할 필요가 없는 상태로 추정된다.
---

### 3. `<string-width>`
**선정 이유:**
단순히 글자 개수가 아니라 화면에 시각적인 실제 폭을 계산해준다는 것이 신기하여 선정하였다.
**이것으로 무엇을 할 수 있을지:**
터미널에서 한글이나 기호들이 섞여 있어도 터미널 화면을 차지하는 길이를 계산하여 간격이 어긋나지 않고 반듯하게 표가 유지될 수 있도록 할 수 있다.
**확인 결과:**
```
$ npm view string-width version time.modified license dependencies
$ npm view string-width deprecated
```
마지막 수정일은 2026년 7월이며 MIT 라이선스이다. 2개의 의존성을 가지고 있으며 deprecated 출력이 없다.
**출력을 보고 알게 된 것:**
최근까지 업데이트가 이루어지고 있는 패키지이다. 앞의 두 패키지는 의존성이 없었는데, 이 패키지는 다른 패키지에 의존하여 동작하는 것을 알 수 있었다.
---

## 설치해본 패키지
string-width
```
$ npm install string-width
$ node try.js

```
kch@DESKTOP-GVMLOF8 MINGW64 ~/Desktop/oss_a1/oss2026-a1 (main)
$ node try.js
hello의 폭: 5
안녕하세요의 폭: 10
---

## 막혔던 부분 (채점하지 않음)
에러 메시지든 헷갈렸던 부분이든 하나. 두 문장이면 됩니다. 없었으면 없었다고 적습니다.
없었다.

## AI 사용
사용했다면 프롬프트와, AI의 설명이 실제와 달랐던 부분을 적습니다.
사용하지 않았다면 "사용하지 않음"이라고만 적으면 됩니다.
사용하지 않음.
---

## 제출 전 확인

- [ ] 저장소 이름이 `oss2026-a1`, 공개 범위가 Public
- [ ] `git status` 결과가 `nothing to commit, working tree clean`
- [ ] `node_modules` 폴더를 지우고 `npm install` → `node try.js` 를 다시 해도 실행됨
- [ ] 마지막 커밋을 push함
