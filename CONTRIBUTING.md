# Fi Chart Project 기여 가이드라인

Fi Chart Project에 관심을 가져주셔서 감사합니다! 이 문서는 프로젝트에 기여하는 방법에 대한 가이드라인을 제공합니다.

## 목차

- [행동 규범](#행동-규범)
- [프로젝트 구조](#프로젝트-구조)
- [기여 방법](#기여-방법)
  - [이슈 제출](#이슈-제출)
  - [Pull Request 제출](#pull-request-제출)
- [개발 가이드라인](#개발-가이드라인)
- [문서화 가이드라인](#문서화-가이드라인)
- [커뮤니케이션](#커뮤니케이션)

## 행동 규범

Fi Chart Project는 개방적이고 존중하는 커뮤니티를 지향합니다. 모든 참여자는 [Contributor Covenant](https://www.contributor-covenant.org/version/2/0/code_of_conduct/) 행동 규범을 준수해야 합니다.

## 프로젝트 구조

Fi Chart Project는 여러 하위 프로젝트로 구성된 메타 저장소입니다:

- **fi_chart_project** (이 저장소): 전체 프로젝트의 메타 정보와 문서를 포함합니다.
- **go_fi_chart**: 전통 금융 자산 데이터 처리 백엔드입니다.
- **cryptolytica**: 암호화폐 데이터 수집 및 분석 시스템입니다.
- **flutter_fi_chart**: 사용자 인터페이스 및 시각화 애플리케이션입니다.

각 프로젝트에는 고유한 기여 가이드라인이 있을 수 있으므로, 특정 프로젝트에 기여할 때는 해당 저장소의 CONTRIBUTING.md 파일도 참조해 주세요.

## 기여 방법

### 이슈 제출

Fi Chart Project에 기여하기 전에, 먼저 해당 이슈가 이미 존재하는지 확인해 주세요. 이슈가 없다면 다음 정보를 포함하여 새 이슈를 제출해 주세요:

- 명확한 제목
- 상세한 설명
- 재현 단계 (버그 리포트의 경우)
- 예상되는 결과와 실제 결과
- 관련 스크린샷 또는 코드 스니펫
- 적절한 레이블 (bug, enhancement, documentation 등)

### Pull Request 제출

Pull Request를 제출하기 위한 단계:

1. 이 저장소를 포크하세요.
2. 적절한 브랜치를 생성하세요 (예: `feature/새기능` 또는 `fix/버그수정`).
3. 변경 사항을 구현하세요.
4. 문서와 테스트를 업데이트하세요.
5. Pull Request를 제출하세요.
6. PR 설명에 관련 이슈 번호를 포함시키세요 (예: "Closes #42").

## 개발 가이드라인

### 아키텍처 가이드라인

- 모든 설계 결정은 `architecture/decisions` 디렉토리에 기록해야 합니다.
- 시스템 간 인터페이스는 명확하게 문서화되어야 합니다.
- 모든 주요 아키텍처 변경은 먼저 이슈로 제안되어야 합니다.

### 문서화 가이드라인

문서화는 Fi Chart Project의 핵심 부분입니다:

- 모든 주요 설계 결정은 문서화되어야 합니다.
- 다이어그램은 [C4 모델](https://c4model.com/)을 따라야 합니다.
- 마크다운 파일은 [Google Markdown 스타일 가이드](https://google.github.io/styleguide/docguide/style.html)를 따라야 합니다.
- 코드 예제는 실행 가능하고 최신 상태여야 합니다.

## 커뮤니케이션

질문이나 제안이 있으신가요? 다음 채널을 통해 연락하실 수 있습니다:

- 이슈 트래커: [GitHub Issues](https://github.com/kimjooyoon/fi_chart_project/issues)
- 이메일: your.email@example.com

---

여러분의 기여는 Fi Chart Project를 더 좋게 만드는 데 큰 도움이 됩니다. 참여해 주셔서 감사합니다!