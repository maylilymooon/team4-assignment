# 4팀 취미 모음 사이트

팀원들이 좋아하는 취미를 소개하는 간단한 정적 웹사이트입니다.

## 구조

```
index.html              홈 (팀원 카드 목록)
style.css               홈 스타일
members/
  maylilymooon/         팀장 페이지 (index.html, style.css, 이미지 등)
  bluerose219/          팀원 페이지
```

각자 **자기 폴더(`members/<GitHub 아이디>/`) 안의 파일만** 수정해 주세요. 그러면 서로 충돌 없이 작업할 수 있습니다.

## 작업 규칙

`master` 브랜치에는 직접 올릴 수 없습니다. 자기 브랜치를 만들어 올린 뒤 PR을 만들면 팀장이 검토하고 합칩니다.

```bash
git clone https://github.com/maylilymooon/team4-assignment.git
cd team4-assignment
git switch -c <내-브랜치-이름>

# members/<내 아이디>/ 폴더 꾸미기

git add .
git commit -m "내 취미 페이지 작성"
git push -u origin <내-브랜치-이름>
# GitHub에서 Pull Request 생성 → 팀장 검토 후 merge
```

## 미리 보기

`index.html`을 브라우저로 열면 바로 볼 수 있습니다.
