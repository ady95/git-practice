# git-practice

AI 에이전트와 함께 문서와 웹페이지를 만들며 Git과 GitHub를 배우는 연습용 저장소입니다.

## 이 저장소의 목적

자기소개 문서를 Git으로 관리하면서 기본 명령어(add, commit, push)와 GitHub 사용법을 익히는 것이 목표입니다.
지금은 자기소개 마크다운 문서들과, 그 내용을 보여 주는 소개 웹페이지(index.html)가 들어 있습니다. 브랜치를 만들어 작업한 연습 기록은 커밋 기록(`git log`)과 Pull Request 목록에서 볼 수 있습니다.

## 들어 있는 파일

| 파일 | 내용 |
| --- | --- |
| [README.md](README.md) | 지금 보고 있는 저장소 안내 문서 |
| [profile.md](profile.md) | 자기소개: 이름, 하는 일, 관심 분야 |
| [hobby.md](hobby.md) | 취미 소개: 글쓰기 · 읽기 · 산책 · 사진 찍기 |
| [todo.md](todo.md) | 앞으로 할 일 목록 (Git 연습과 다음 목표) |
| [books.md](books.md) | 읽은 책 목록 (제목과 저자) |
| [index.html](index.html) | 소개 웹페이지. profile.md, hobby.md, todo.md, books.md 내용을 담았습니다 |
| [AGENTS.md](AGENTS.md) | AI 에이전트 작업 지침 (프로젝트 설명, 규칙, 작업 후 보고 방법) |
| [CLAUDE.md](CLAUDE.md) | Claude Code용 지침 파일. AGENTS.md를 불러옵니다 |
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

Windows에서는 PowerShell이나 명령 프롬프트에서도 위의 명령을 그대로 사용할 수 있습니다.

## 설정 파일 만들기

설정 값이 필요한 경우 예제 파일을 복사해서 `.env`를 만들고 값을 채웁니다.

```bash
cp .env.example .env
```

Windows PowerShell에서는 `Copy-Item .env.example .env`를 사용합니다.
