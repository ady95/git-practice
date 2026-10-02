# git-practice

AI와 함께 문서와 웹페이지를 만들며 Git을 배우는 연습용 저장소입니다.

## 이 저장소의 목적

자기소개 문서를 Git으로 관리하면서 기본 명령어(add, commit, push)와 GitHub 사용법을 익히는 것이 목표입니다.
지금은 마크다운 문서만 들어 있고, 앞으로 브랜치 작업을 연습하고 소개 문서를 작은 웹페이지로 바꿔 볼 계획입니다.

## 들어 있는 파일

| 파일 | 내용 |
| --- | --- |
| [README.md](README.md) | 지금 보고 있는 저장소 안내 문서 |
| [profile.md](profile.md) | 자기소개: 이름, 하는 일, 관심 분야 |
| [hobby.md](hobby.md) | 취미 소개: 글쓰기 · 읽기 · 산책 |
| [todo.md](todo.md) | 앞으로 할 일 목록 (Git 연습과 다음 목표) |
| [index.html](index.html) | 소개 웹페이지. profile.md와 hobby.md, todo.md 내용을 담았습니다 |
| [.env.example](.env.example) | 설정 파일 예제. 복사해서 `.env`를 만들고 실제 값을 넣습니다 |
| [.gitignore](.gitignore) | Git이 추적하지 않을 파일 목록 (`.env`, 개인 메모, 임시 파일, 로그 등) |

`.env` 파일은 비밀 정보를 담으므로 저장소에 올리지 않습니다. `.gitignore`에 이미 등록되어 있습니다.

## 내려받는 방법

Git이 설치되어 있다면 터미널에서 다음 명령을 실행합니다.

```bash
git clone https://github.com/ady95/git-practice.git
cd git-practice
```

Git 없이 받으려면 GitHub 저장소 페이지에서 **Code → Download ZIP**을 눌러 압축 파일로 내려받을 수 있습니다.

## 설정 파일 만들기

설정 값이 필요한 경우 예제 파일을 복사해서 `.env`를 만들고 값을 채웁니다.

```bash
cp .env.example .env
```

Windows PowerShell에서는 `Copy-Item .env.example .env`를 사용합니다.
