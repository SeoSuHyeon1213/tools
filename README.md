# tools

Tools for programming with AI.
AI와 함께 프로그래밍할 때 쓰는 지침 파일 모음입니다.

## How to use / 사용법

Each file comes in Korean (`.kr`) and English (`.en`). Pick one and remove the language tag from the name.
각 파일은 한국어(`.kr`)와 영어(`.en`) 버전이 있습니다. 하나를 골라 이름에서 언어 표시를 지우세요.

```
CLAUDE.kr.md     →  CLAUDE.md
AGENTS.kr.md     →  AGENTS.md
CHECKLIST.kr.md  →  CHECKLIST.md
SKILL.kr.md      →  SKILL.md
```

Place the files in the root of each project, not in a drive root containing several projects.
여러 프로젝트가 있는 드라이브 루트가 아니라 각 프로젝트 루트에 두세요.

## Files / 파일

### CLAUDE.md
- **Role:** The main rulebook Claude reads automatically when it works in the project. It defines how Claude, as the developer, works with ChatGPT, as the artist: roles, the shared "mailbox" folder, the order → artwork → review workflow, when to ask the human, and the rule that nothing is released without the human saying "release it."
- **역할:** 클로드가 프로젝트에서 작업할 때 자동으로 읽는 기본 규칙서입니다. 개발 담당 클로드와 그림 담당 챗지피티의 협업 방법을 정합니다. 역할 분담, 공유 "우편함" 폴더, 지시서 → 그림 → 검수 흐름, 사람에게 물어야 하는 일, 사람이 "출시해"라고 하기 전에는 출시하지 않는 규칙이 들어 있습니다.

### AGENTS.md
- **Role:** Common working rules for any AI agent (Claude, Codex, etc.). It covers checking the project before editing, keeping changes in scope, protecting existing work, verifying honestly, and recording progress. Its orchestration section holds the core collaboration rules every agent must follow, with details in CLAUDE.md.
- **역할:** 클로드, 코덱스 등 어떤 AI 에이전트든 따르는 공통 작업 규칙입니다. 수정 전 프로젝트 확인, 요청 범위 지키기, 기존 작업 보호, 정직한 검증, 진행 기록을 다룹니다. 오케스트레이션 항목에는 모든 에이전트가 지켜야 할 협업 핵심 규칙이 있고, 자세한 내용은 CLAUDE.md를 따릅니다.

### CHECKLIST.md
- **Role:** A template for tracking one task. It records the goal, current status, steps, verification results, decisions, and remaining work, so the AI (or you) can pick up where it left off. The orchestration section tracks each mailbox job by its job ID, from order to release.
- **역할:** 작업 하나의 진행을 기록하는 템플릿입니다. 목표, 현재 상태, 실행 단계, 검증 결과, 결정 사항, 남은 작업을 적어 AI나 사람이 중간에 이어서 작업할 수 있게 합니다. 오케스트레이션 섹션은 우편함 작업을 작업 번호로 지시서부터 출시까지 추적합니다.

### SKILL.md
- **Role:** A skill that teaches the AI *when* to use the other files: read guidelines and checklists at the start, check again when scope changes or work resumes, create AGENTS.md or CHECKLIST.md if missing, and follow the orchestration steps when working with the artist.
- **역할:** 다른 파일들을 *언제* 쓸지 AI에게 알려주는 스킬입니다. 작업 시작 시 지침과 체크리스트 읽기, 범위가 바뀌거나 작업을 재개할 때 다시 확인하기, AGENTS.md나 CHECKLIST.md가 없으면 만들기, 그림 담당과 협업할 때 오케스트레이션 순서 따르기를 다룹니다.

## How they fit together / 파일 간 관계

| File | Keeps | 담는 내용 |
|---|---|---|
| `CLAUDE.md` / `AGENTS.md` | Lasting rules | 오래 유지할 규칙 |
| `CHECKLIST.md` | Current task status | 현재 작업 상태 |
| `SKILL.md` | When to read and update the others | 다른 파일을 언제 읽고 갱신할지 |

## Notes / 참고

- Fill in items marked `[To confirm]` / `[확인 필요]` with facts verified from your project.
  `[To confirm]` / `[확인 필요]` 표시는 프로젝트에서 확인한 사실로 채우세요.
- Do not put secrets (keys, tokens, passwords) in these files.
  비밀키, 토큰, 비밀번호는 이 파일들에 넣지 마세요.
