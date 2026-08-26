# Changelog

이 파일에는 `pm-experience-mentor`의 사용자 또는 에이전트 동작에 의미가 있는 변경사항을 기록합니다.

형식은 [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)의 원칙을 간단히 따르며, 버전 번호는 [Semantic Versioning](https://semver.org/)을 사용합니다.

## [Unreleased]

### Added

- 비공개 Google Drive 등 외부 저장소에 원자료를 보관하고, 실제 위치는 로컬 프로젝트 안내 파일에만 기록하는 방법을 문서화했습니다.
- 사람을 위한 스킬별 `README.md`를 추가했습니다.
- 향후 버전별 변경을 기록하기 위한 `CHANGELOG.md`를 추가했습니다.
- 로컬 학습자료 보관, 일반화, 검증 및 버전 업데이트 절차를 문서화했습니다.

## [0.0.1] - 2026-08-26

### Added

- 대화를 통해 IT Product Manager 경험을 발굴하는 초기 스킬을 추가했습니다.
- 사용자의 직전 답변에서 다음 질문을 선택하는 적응형 멘토링 방식을 정의했습니다.
- 문제 발견 근거, 지표 논리, 우선순위, 트레이드오프, 기여도 및 피드백 루프를 탐색하는 기준을 추가했습니다.
- 솔직하고 직설적이되 사용자를 공격하지 않는 멘토링 말투를 정의했습니다.
- 원문을 보존하고 삭제, 재작성, 새로 발굴한 정보와 확인이 필요한 내용을 시각적으로 구분하는 규칙을 추가했습니다.
- 상담 녹취와 개인 경험 원문을 배포용 스킬에서 제외하는 개인정보 보호 원칙을 추가했습니다.

### Files

- `SKILL.md`
- `agents/openai.yaml`
- `references/mentor-style.md`
- `references/pm-story-rubric.md`
- `references/visual-revision.md`

## 변경 기록 방법

아직 릴리스하지 않은 변경은 먼저 `[Unreleased]` 아래에 기록합니다.

- 새 기능 또는 새 동작: `Added`
- 기존 동작 변경: `Changed`
- 오류 수정: `Fixed`
- 기능 제거: `Removed`
- 개인정보 또는 안전 관련 변경: `Security`

새 버전을 릴리스할 때 `[Unreleased]`의 항목을 새 버전과 날짜 아래로 이동합니다.

```markdown
## [0.0.2] - YYYY-MM-DD

### Changed

- 새로운 멘토링 자료에서 반복 확인된 질문 패턴을 반영했습니다.
```

그다음 `SKILL.md`의 `metadata.version`, `README.md`의 현재 버전, Git 태그를 같은 버전으로 맞춥니다.
