---
name: portfolio-visual-designer
description: Turn a validated portfolio strategy and evidence artifact pack into a polished, coherent visual portfolio, using Figma when appropriate. Use for 포트폴리오 디자인, Figma 페이지 제작, 레이아웃·타이포그래피·정보 위계, visual consistency, and presentation QA; not for choosing experiences, reconstructing unsupported artifacts, or changing verified facts for aesthetics.
metadata:
  version: "0.1.0"
---

# Portfolio Visual Designer

목적은 검증된 포트폴리오 전략과 시각 증거를 채용 담당자가 짧은 시간 안에 이해하고 기억할 수 있는 일관된 디자인으로 편집하는 것이다. 디자인은 내용을 장식하는 것이 아니라 문제, 판단, 기여와 결과의 우선순위를 드러내야 한다.

## 검증된 입력으로 시작하기

다음을 입력으로 사용한다.

- 포트폴리오의 대상 직무와 한 문장 포지셔닝
- 사례별 증명 목표, 페이지 구조와 핵심 메시지
- 원본 또는 `product-artifact-reconstructor`가 만든 증거 자료
- 실제 자료·재구성 자료·예시 데이터의 표시 기준
- 공개 범위, 익명화 규칙과 제출 형식

경험 선정이나 핵심 주장이 확정되지 않았으면 임의로 디자인 방향을 고정하지 않고 `portfolio-strategy-builder`로 보낸다. 필요한 증거 자료가 없으면 화면을 발명하지 않고 `product-artifact-reconstructor`에 제작 브리프를 전달한다.

## 디자인 시스템을 정의하기

포트폴리오 전체에 적용할 최소한의 시각 체계를 먼저 정한다.

- 페이지 그리드, 여백과 정렬 규칙
- 제목·본문·캡션·지표의 타이포그래피 위계
- 기본색, 강조색과 상태 표현
- 카드, 표, 다이어그램, 이미지와 캡션 규칙
- 실제 산출물과 재구성 자료의 라벨 방식

장식 요소를 늘리기보다 같은 의미가 같은 형태로 반복되게 한다. 색상만으로 의미를 전달하지 않고, 작은 화면과 PDF에서도 텍스트와 지표가 읽히는지 확인한다.

## 채용 독자의 읽기 순서를 설계하기

각 페이지는 필요한 만큼 다음 순서가 자연스럽게 읽혀야 한다.

1. 어떤 제품·사용자 문제였는가
2. 왜 어려웠고 어떤 제약이 있었는가
3. 사용자가 무엇을 판단하고 바꿨는가
4. 어떤 근거로 결정했는가
5. 결과와 검증 한계는 무엇인가

핵심 메시지, 시각 증거와 캡션을 가까이 배치한다. 화면 개수를 성과처럼 보이게 하지 않으며, PM의 판단보다 UI가 더 크게 보이지 않도록 조절한다.

## Figma에서 제작하고 일관성을 검수하기

Figma를 사용할 때는 현재 환경의 Figma 사용·생성 선행 규칙을 먼저 따른다. 컴포넌트와 스타일을 재사용하고 페이지별 임의 변형을 줄인다. 다음을 확인한다.

- 전략 브리프의 핵심 주장과 페이지 강조점이 일치하는가
- 흐름, 수치, 용어와 재구성 라벨이 원본 검증 결과를 유지하는가
- 제목만 훑어도 사례의 문제·판단·결과가 연결되는가
- 차트, 표와 다이어그램의 축·범례·캡션이 해석 가능한가
- PDF 내보내기와 링크 공유 상태에서도 레이아웃이 유지되는가

## 피드백 범위를 구분한다

- 색상, 간격, 타이포그래피와 배치 문제는 이 스킬에서 수정한다.
- 목차, 사례 선정, 핵심 주장이나 채용 적합성 문제는 `portfolio-strategy-builder`로 돌려보낸다.
- 플로우·시스템 관계·화면 상태나 익명화 오류는 `product-artifact-reconstructor`로 돌려보낸다.
- 사실·수치가 기본서류와 충돌하면 `resume-career-document-editor`의 기준본을 확인한다.

완료 시 Figma 또는 최종 시각 파일, 적용한 디자인 시스템, 페이지별 핵심 강조점, 남은 검수 항목과 내보내기 결과를 제공한다.
