# 포트폴리오를 GitHub Pages에 올리기

`index.html`에 페이지, 스타일, 스크립트와 이미지 5장이 들어 있습니다. Pretendard 글꼴은 인터넷에서 불러옵니다.

## 처음 게시할 때

1. ZIP 파일의 압축을 풉니다.
2. GitHub에서 새 저장소를 만듭니다. GitHub Free를 사용한다면 공개 저장소(Public)를 선택합니다.
3. 저장소의 **Add file → Upload files**에서 `index.html`과 `README.md`를 올리고 **Commit changes**를 누릅니다. 빈 저장소에서는 **uploading an existing file** 링크로 같은 화면을 열 수 있습니다.
4. 두 파일이 `main` 브랜치의 최상위에 있는지 확인합니다.
5. **Settings → Pages → Build and deployment**에서 **Deploy from a branch**를 선택합니다.
6. **Branch**를 `main`, 폴더를 `/(root)`로 선택하고 **Save**를 누릅니다. 브랜치 이름이 다르면 `index.html`이 올라간 브랜치를 선택합니다.
7. 배포가 끝나면 **Settings → Pages**에 표시된 주소로 접속합니다.

공개 페이지에는 현재 포트폴리오의 프로필 사진, 이메일, 전화번호가 표시됩니다. 공개 범위를 바꾸려면 저장소에 올리기 전에 `index.html`을 수정하세요.

[GitHub Pages 게시 설정 공식 안내](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
