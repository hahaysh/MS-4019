# 데모 3. Agent 관리

## 목표

- Agent 운영
- Agent 제거
- Agent 삭제
- Agent 공유 방식 이해

---

## 실습 대상 환경

- Microsoft 365 Copilot 라이선스 없이 Copilot Chat 사용 가능
- Copilot Chat 기반 Agent 관리
- Agent 공유 화면 확인 가능
- SharePoint Agent 관리 실습 제외

---

## 데모 3-1. Agent 편집

### 참고 자료

#### Microsoft Learn

Build and manage an agent

https://learn.microsoft.com/training/modules/build-manage-no-code-copilot-agent-sharepoint/

### Learn Unit

- Test and edit your agents
- Validate and improve agent responses
- Modify agent components

### 진행

기존 Agent 열기

수정

- Name
- Description
- Instructions

### 설명 포인트

- 운영 중 수정 가능
- Instructions 변경 시 응답 변화 확인
- Agent는 지속적으로 개선하는 대상
- Agent Lifecycle 시작 단계

---

## 데모 3-2. Agent 제거 (Uninstall)

### 참고 자료

#### Microsoft Learn

Build and manage an agent

https://learn.microsoft.com/training/modules/build-manage-no-code-copilot-agent-sharepoint/

#### Microsoft Learn 문서

Create and manage agents in Copilot Chat

https://learn.microsoft.com/microsoft-365-copilot/extensibility/create-agents-copilot-chat

### Learn Unit

- Manage your agents
- Review agent lifecycle options

### 진행

Agent 제거 메뉴 확인

제거 전 확인

- 라이브러리에서 현재 Agent가 노출되는지 확인

### 설명

- 내 Agent 목록에서 제거
- Agent 자체는 유지
- 필요하면 다시 설치 가능
- 설정 및 구성 유지

제거 후 확인

- 라이브러리에서 내 목록 기준으로 노출 상태가 어떻게 바뀌는지 확인
- 검색의 과거 대화 기록과 Agent 설치/제거 상태는 별개임을 확인

### 설명 포인트

- Delete와 차이
- Agent Library 정리 목적
- 임시 비활성화 개념
- 운영 중인 Agent 보관 방법

---

## 데모 3-3. Agent 삭제 (Delete)

### 참고 자료

#### Microsoft Learn

Build and manage an agent

https://learn.microsoft.com/training/modules/build-manage-no-code-copilot-agent-sharepoint/

#### Microsoft Learn 문서

Create and manage agents in Copilot Chat

https://learn.microsoft.com/microsoft-365-copilot/extensibility/create-agents-copilot-chat

### Learn Unit

- Manage your agents
- Agent lifecycle management

### 진행

삭제 화면 확인

삭제 전 확인

- 라이브러리에서 삭제 대상 Agent를 정확히 선택했는지 확인

### 설명

- Agent 영구 삭제
- Instructions 삭제
- Starter Prompts 삭제
- 구성 정보 삭제

삭제 후 확인

- 라이브러리에서 해당 Agent가 더 이상 재진입 불가한지 확인
- 검색으로 과거 대화를 찾더라도 동일 Agent 실행은 불가할 수 있음을 안내

### 설명 포인트

- 복구 어려움
- Uninstall과 차이
- Agent 수명주기 관리
- 테스트용 Agent 정리 방법

---

## 데모 3-4. Agent 공유

### 참고 자료

#### Microsoft Learn

Share and use agents

https://learn.microsoft.com/en-us/training/modules/use-no-code-agents-sharepoint/

### Learn Unit

- Share agents with others
- Share agents in Microsoft Teams
- Permissions and access considerations

### 진행

공유 메뉴 확인

### 설명

공유 범위

- Only me
- Specific users
- Entire organization

### 추가 설명

- Agent를 공유해도 데이터 권한은 공유되지 않음
- 사용자는 자신의 권한 범위 내 정보만 조회 가능
- Agent 권한과 데이터 권한은 별개

### 설명 포인트

- Agent 공유
- Teams 공유
- 권한 상속 개념
- 협업 시나리오

### 주의사항

- 실제 공유 실습은 진행하지 않음
- 공유 화면만 시연
- Teams 공유 화면만 확인

---

## 데모 3-5. 모듈 정리

### 참고 자료

#### Microsoft Learn

Build and manage an agent

https://learn.microsoft.com/training/modules/build-manage-no-code-copilot-agent-sharepoint/

#### Microsoft Learn

Share and use agents

https://learn.microsoft.com/training/modules/share-use-agents/

### Learn Unit

#### Module 3

- Test and edit your agents
- Manage your agents

#### Module 4

- Share agents with others
- Share agents in Microsoft Teams
- Interact with agents

### 핵심 메시지

- Agent 생성보다 운영이 더 중요하다.
- 좋은 Agent는 테스트와 개선을 반복하면서 완성된다.
- Uninstall과 Delete는 서로 다른 개념이다.
- Agent는 공유할 수 있지만 데이터 권한은 공유되지 않는다.
- Agent는 개인 생산성 도구를 넘어 팀 협업 도구로 확장될 수 있다.

---

## 강사 참고

### MS-4019 Module 3

Build and manage an agent

https://learn.microsoft.com/training/modules/build-manage-no-code-copilot-agent-sharepoint/

### MS-4019 Module 4

Share and use agents

https://learn.microsoft.com/training/modules/share-use-agents/

### 관련 Learning Path

Implement no-code Copilot agents in Microsoft 365 SharePoint

https://learn.microsoft.com/training/paths/implement-no-code-copilot-agents-microsoft-365-sharepoint/

---

## 실습 범위

### 실습 진행

- Agent 편집
- Agent 테스트
- Agent 제거(Uninstall)
- Agent 삭제(Delete)

### 화면 시연

- Agent 공유
- Teams 공유

### 제외

- SharePoint Agent 생성
- SharePoint Agent 관리
- Copilot Studio
- Researcher
- Analyst