## 초기 세팅
1. github 로그인 / 아이디가 없다면 회원가입
2. 구글에 `github desktop` 검색후 앱 설치 -> 앱 실행후 본인 깃허브 계정으로 로그인하기
3. https://github.com/cpprhtn/AI-Learning-Guide 해당페이지에서 오른쪽 위에 `Fork` 버튼 클릭
4. 왼쪽 아래 `Create Fork` 버튼 클릭 -> 자동으로 본인 깃허브 계정에 해당 레포지토리 복제
5. 본인의 복제된 레포지토리에서 녹색 `Code` 버튼 클릭 -> `Open with GitHub Desktop` 버튼 선택
6. 옵션 건들필요없이 파란색 `Clone` 버튼 클릭
7. How are you planning to use this fork? -> To contribute to parent project 버튼을 클릭후 `Continue` 버튼 선택

## PR전 cpprhtn/AI-Learning-Guide와 동기화 시켜주기
1. 본인의 AI-Learning-Guide 레포로 이동
2. `main` branch 선택후 Code 버튼 밑에있는 `Fetch upstream` 클릭
3. `Update branch` 버튼을 클릭 (parent project에서 업데이트 된 파일들이 있다면 여러분의 계정에도 반영시키는 작업)
4. Github Desktop 앱을 실행후 Current branch가 `main`인지 확인후 `Fatch origin` 버튼을 한번 클릭
5. 받아올 파일이 있다면 Pull origin 버튼으로 바뀌며, 해당 버튼을 클릭해서 cpprhtn/AI-Learning-Guide와 동기화 시켜준다.

## PR하는법
1. 새로운 branch를 만든다. (ex. 본인의 계정명이든, 추가할 용어명이든 브랜치명은 main만 아니면 상관없음)
2. 파일을 만들거나 수정하거나 삭제한다.
3. 변경된 파일들이 Github desktop Change에 기록된다.
4. Summary 섹션에서 "단어사전 추가" 와 같이 본인이 작업한 활동을 적어준다.
5. "Commit to 브랜치명" 버튼을 클릭한다.
6. Push origin(또는 Publish branch으로 떠있는 경우도 있다.)버튼을 눌러준다.
7. Create Pull Request 버튼을 눌러준다.
8. 어떤 내용으로 PR했는지 내용을 간단하게 작성해준 후 Create Pull Request 버튼을 눌러준다.
9. 녹색은 cpprhtn/AI-Learning-Guide 레포에 문제없이 합칠 수 있는 상태 / 보라색은 cpprhtn/AI-Learning-Guide레포에 합쳐진 상태 / 빨간색은 cpprhtn/AI-Learning-Guide레포에 합쳐지지 못하거나 거절당한 상태.
10. 보라색으로 변해서 무사히 합쳐졌다면(merge) 합쳐진 브랜치는 지워도 무방하다.
11. 새로운 PR을 하려고 한다면, "## PR전 cpprhtn/AI-Learning-Guide와 동기화 시켜주기"부터 다시 따라서 진행한다.